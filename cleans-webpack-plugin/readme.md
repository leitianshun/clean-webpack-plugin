#Clean plugin for wepack

A webpack plugin to clean output.path folder for webpack project.

## Installtion

```bash
npm install --save-dev cleans-webpack-plugin
```

##Usage
```js
const EmptyWebpackPlugin = require('empty-webpack-plugin');
 
module.exports = {
    ...
 
    plugins: [
      // clean out.path folder
        new EmptyWebpackPlugin()
    ]
 
    ...
}
 
module.exports = {
    ...
 
    plugins: [
      // exclude .git folder
        new EmptyWebpackPlugin({ exclude: '.git' })
    ]
 
    ...
}
```