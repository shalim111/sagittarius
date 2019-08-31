# sagittarius
A list of javascript most used utils

<center><img src="https://github.com/Gherciu/sagittarius/blob/master/sagittarius-logo.png" alt="sagittarius" width="150px" height="150px"/></center>

---
#### Data generation

- Random number generation from range
```js
const random = (min, max) => Math.random() * (max - min) + min
```

#### Data validation

- Empty data validation
```js
const isEmpty = value => {
  if(Array.isArray(value))
    return !value.length
  return value === null || value === '' || value === undefined || (typeof value === 'object' && !Object.keys(value).length)
}
```

#### User inputs validation

- Email validation
```js
const validateEmail = email => /^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/.test(email)
```
- Password validation
```js
const validatePassword = password => /^(?=.*[a-z])(?=.*[0-9])(?=.*[A-Z])(?=.*[#$^+=!*()@%&]).{8,20}$/.test(password)
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

**@Gherciu/sagittarius** © [GHERCIU](https://github.com/Gherciu), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by GHERCIU with help from contributors ([list](https://github.com/Gherciu/sagittarius/contributors)).

#### If you like this repository star⭐ and watch👀 on [GitHub](https://github.com/Gherciu/sagittarius)
