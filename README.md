# node-sass-promise

A simple promise wrapper for node-sass

[Documentation](https://github.com/sass/node-sass) for node-sass

# installation

`npm install --save node-sass-promise`

# usage

```javascript
const NSP = require("node-sass-promise")

NSP.render({options})
.then(result => {
  //node-sass result
})
.catch(err => {
  //node-sass error
})
```
