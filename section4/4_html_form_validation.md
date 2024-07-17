# 1. form validation

```
- 값이 꼭 입력 되기를 바란다면 해당 input의 속성에 required를 주면 된다.
- input의 속성 중 min, max를 통해서 글자수를 지정할 수 있다.
- input의 pattern 속성으로 입력값의 형식을 지정할 수 있다.(정규표현식)
```

```html
<h2>Validations Demo</h2>
<form action="/dummy">
    <!-- required 속성을 통해 해당 input이 무조건 입력하도록 할 수 있다. -->
    <label for="first">Enter First Name</label>
    <input type="text" name="first" id="first" required />
    <!-- min, max 속성을 통해 입력받는 글자수의 범위를 지정할 수 있다. -->
    <p>
        <label for="username">Username</label>
        <input
            type="text"
            name="username"
            id="username"
            minlength="5"
            maxlength="20"
            required
        />
    </p>

    <!-- email, url 등 기본 pattern check type이 있다. -->
    <p>
        <input type="email" name="" id="" required />
        <input type="url" name="" id="" />
    </p>

    <button>Submit</button>
</form>
```
