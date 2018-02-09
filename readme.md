# fresh-require

A require that watches for changes and reloads modules. Simply call again to get the latest module changes.

Useful while developing server-side single page applications.

```js
const freshRequire = require('fresh-require')

let module = freshRequire('./module')

// change module.js

// reload changes
module = freshRequire('./module')
```

## We're Hiring!
Featurist provides full stack, feature driven development teams. Want to join us? Check out [our career opportunities](https://www.featurist.co.uk/careers/).
