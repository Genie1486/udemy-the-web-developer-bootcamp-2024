# 1. td, tr, th

```
- <td> element는 data를 포함하고 있는 셀을 의미함
- <th> element는 header 역할을 하는 셀을 의미함.
- <tr> element는 table의 row를 의미함.
```

```html
<table>
    <tr>
        <th>Animal</th>
        <th>Average mass[kg(lb)]</th>
        <th>Maximem mass[kg(lb)</th>
        <th>Flighted</th>
    </tr>
    <tr>
        <td>Ostrich</td>
        <td>104(230)</td>
        <td>156.8(346)</td>
        <td>No</td>
    </tr>
    <tr>
        <td>Somali Ostrich</td>
        <td>90(200)</td>
        <td>130(287)</td>
        <td>No</td>
    </tr>
    <tr>
        <td>Wild Turkey</td>
        <td>13.5(29.8)</td>
        <td>39(86)</td>
        <td>Yes</td>
    </tr>
</table>
```

<br><br><br>

# 2. thead, tbody, tfoot

```
- thead, tbody, tfoot은 table의 tr들의 역할을 직접적으로 명시해주는 역할을 함
- 예를 들어 tr을 thead로 묶어주면 이 부분은 table의 header 역할을 한다고 이해할 수 있음
```

```html
<table>
    <thead>
        <tr>
            <th>Animal</th>
            <th>Average mass[kg(lb)]</th>
            <th>Maximem mass[kg(lb)</th>
            <th>Flighted</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Ostrich</td>
            <td>104(230)</td>
            <td>156.8(346)</td>
            <td>No</td>
        </tr>
        <tr>
            <td>Somali Ostrich</td>
            <td>90(200)</td>
            <td>130(287)</td>
            <td>No</td>
        </tr>
        <tr>
            <td>Wild Turkey</td>
            <td>13.5(29.8)</td>
            <td>39(86)</td>
            <td>Yes</td>
        </tr>
    </tbody>
</table>
```

<br><br><br>

# 3. colspan, rowspan

```
- th, td의 속성으로 colspan, rowspan을 지정해주면 셀의 가로 길이과 세로길이를 지정해줄 수 있다.
- colspan은 셀의 가로길이
- rowspan은 셀의 세로길이
```

```html
<table border="1">
    <thead>
        <tr>
            <th rowspan="2">Animal</th>
            <th colspan="2">Average Mass</th>
            <th rowspan="2">Flighted</th>
        </tr>
        <tr>
            <th>KG</th>
            <th>LB</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Ostrich</td>
            <td>104</td>
            <td>230</td>
            <td>No</td>
        </tr>
        <tr>
            <td>Somali Ostrich</td>
            <td>90</td>
            <td>200</td>
            <td>No</td>
        </tr>
        <tr>
            <td>Wild Turkey</td>
            <td>13.5</td>
            <td>29.8</td>
            <td>Yes</td>
        </tr>
    </tbody>
</table>
```
