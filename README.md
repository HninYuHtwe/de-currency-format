## Usage

```javascript
const changeFormat = require('hyh-de-currency-format')

const enStr = '1.000,00'
const deStr = '1,000.00'

const deR = changeFormat(enStr)
const enR = changeFormat(deStr)

console.log(enStr, deR)
console.log(deStr, enR)
```
## License

[MIT](https://choosealicense.com/licenses/mit/)