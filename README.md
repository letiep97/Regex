# Regex for validation


## Email

```js
/^(?=.*\d)(?=.*[a-z])(?=.*[A-Z])(?=.*[a-zA-Z])(?=.*[*.!@$%^&(){}[\]:;<>,.?/~_+\-=|\\]).{8,}$/g
```

- `(?=.*\d)` : At least one digit 
- `(?=.*[a-z])` : At least one lowercase character
- `(?=.*[A-Z])` : At least one uppercase character
- `(?=.*[a-zA-Z])` : 
- `(?=.*[*.!@$%^&(){}[\]:;<>,.?/~_+\-=|\\])` : At least on special character
- `.{8,}` : Min eight character


## Password

`/^[A-Za-z -']+$/g`

- `A-Za-z`
- space 
- dash
- single quote 
