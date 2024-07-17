# 1. checkbox

```
- checkbox는 여러개를 선택해서 보내야 할 때 사용할 수 있음
- checked 속성을 주면 처음부터 해당 항목에 체크가 된 상태로 나옴
```

```html
<form action="/birds">
    <input type="checkbox" name="agree_tos" id="agree" checked />
    <label for="agree">I agree to everything</label>
    <button>Submit</button>
</form>
```

<br><br><br>

# 2. radio button

```
- radion button은 여러 개의 항목 중에서 오직 하나만 선택해야할 경우에 사용가능
- input의 name 속성을 동일하게 해주면 하나의 그룹으로 묶인다.
- input의 value 속성을 통해서 서버에 전달되는 값을 설정할 수 있다.
```

```html
<form action="/birds">
    <p>
        <label for="xs">XS:</label>
        <input type="radio" name="size" id="xs" value="xs" />
        <label for="s">S:</label>
        <input type="radio" name="size" id="s" value="s" />
        <label for="m">M:</label>
        <input type="radio" name="size" id="m" value="m" />
    </p>
    <button>Submit</button>
</form>
```

<br><br><br>

# 3. select

```
- 여러 옵션 중에서 하나를 선택하게 할 경우에 사용할 수 있다.
- 드롭다운 버튼을 누르면 여러 옵션들이 나온다.
- 서버에 전달될 때 key는 select의 name이고 value는 option의 name이다.
- option tag에 selected 속성을 줘서 미리 선택할 수도 있다.
```

```html
<form action="/birds">
    <p>
        <label for="meals">Please Select an Entree</label>
        <select name="meal" id="meal">
            <option value="fish">Fish</option>
            <option value="veg" selected>Vegetarian</option>
            <option value="steak">Steak</option>
        </select>
    </p>
    <button>Submit</button>
</form>
```

<br><br><br>

# 4. 기타 (range, textarea )

```html
<form>
    <!-- range는 사람들이 드래그를 통해 숫자를 입력할 수 있도록 하는 input -->
    <p>
        <label for="cheese">Amount of cheese:</label>
        <input
            type="range"
            id="cheese"
            min="1"
            max="100"
            step="1"
            value="75"
            name="cheese_level"
        />
    </p>

    <!-- textarea는 긴 글을 보내기 위한 input -->
    <p>
        <label for="requsts">Any Special Requests?</label>
        <textarea
            name="requests?"
            id="requsts"
            rows="10"
            cols="40"
            placeholder="Type something here"
        ></textarea>
    </p>
    <button>Submit</button>
</form>
```
