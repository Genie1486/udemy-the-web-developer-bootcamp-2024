# 0. vscode 단축키 모음

```
alt + shift + ↑ : 한줄 복사해서 위에 붙임
alt + shift + ↓ : 한줄 복사해서 아래에 붙임
```

# 1. MDN

```
https://developer.mozilla.org/ko/

MDN은 개발자들이 만든 개발 관련 백과사전

HTML, CSS, Javascript 관련
모르는 것이 있으면 여기서 찾아보자
```

<br><br><br>

# 2. 단락요소 (p태그)

```
<!--p 태그 안에 내용을 쓰면 독립된 단락을 만들 수 있다. -->

<p>내용</p>
```

<br><br><br>

# 3. 제목요소 (h태그)

```
<h1>Beetles</h1>
<h2>External morphology</h2>
<h3>Head</h3>
<h4>Mouthparts</h4>
<h3>Thorax</h3>
<h4>Prothorax</h4>
<h4>Pterothorax</h4>

※약속: h1 태그는 한 페이지에 하나만 있어야 한다.
```

<br><br><br>

# 4. 자동포맷(VSCODE)

```
<방법1>
(window)
1. ctrl + shift + p
2. format Document 클릭
-> 자동으로 문서가 정렬된다.
```

```
<방법2>
(저장할 때마다 문서가 자동 정렬되도록 설정)
1. vscode 왼쪽에 설정버튼을 누른다. (또는 ctrl +,)
2. 설정창이 열리면 format on save 검색
3. format on save 옵션에 체크버튼 클릭
```

<br><br><br>

# 5. 목록만들기

```
목록에는
숫자없는 리스트, 숫자있는 리스트가 있다.

ul과 ol의 직속 자시은 li만 가능
```

```html
<!-- ul은 숫자가 없는 리스트 -->
<ul>
    <li>Silkie</li>
    <li>Polish</li>
    <li>Easter Egger</li>
    <li>Rhode Island Chicken</li>
</ul>

<!-- ol은 숫자가 있는 리스트 -->
<ol>
    <li>Silkie</li>
    <li>Polish</li>
    <li>Easter Egger</li>
    <li>Rhode Island Chicken</li>
</ol>
```

<br><br><br>

# 6. a태그

```html
<!-- a태그는 하이퍼링크를 만든느 태그 -->
<!-- href에는 연결시킬 링크주소를 적는다. -->
<a href="http://www.google.com">I AM A LINK!!</a>
```

<br><br><br>

# 7. img태그

```html
<!-- img 태그는 이미지를 불러오는 태그 -->
<!-- 속성 src에는 이미지 주소 -->
<!-- 속성 alt에는 이미지를 불러오지 못했을 때 사용할 대체텍스트를 입력 -->
<img src="이미지주소" alt="대체텍스트" />
```

<br><br><br>

# 8. 주석넣기

```html
<!-- 주석은 이렇게 넣으면 됨 -->
<!-- ctrl + / 주석으로 전환 -->
```
