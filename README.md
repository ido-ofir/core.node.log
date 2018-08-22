# core.node.log
easily log colorful messages to the NodeJS console

## Usage

This plugin enables easy logging of colorful messages to the NodeJS console.

It exposes a 'log' function on the core object. string arguments to this function are parsed and colored accordingly.

To color a piece of your string wrap it in parantheses and prepend with a '#' and then the name of the color you want.

```js
core.plugin([
  require('core.node.colors'),
  require('core.node.log')
]);

core.log(' #green(√) #yellow( Did the stuff! )')
```

Avilable colors:

#yellow
#purple
#blue
#red
#cyan
#grey
#green



