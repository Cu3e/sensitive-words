# Example

```shell
$ npm install sensitive-words --save
```

```javascript
const sensitiveWords = require('sensitive-words').default
// ES2015modules
import sensitiveWords from 'sensitive-words/default'

const filtered = sensitiveWords(
  'The new apple macbook pro will have a touchbar',
  ['pro','touchbar']
)
console.log(filtered)
//The new apple macbook *** will have a ***
```
