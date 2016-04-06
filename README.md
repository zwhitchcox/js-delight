#### get unix timestamp

`+new Date() / 1000 | 0`

`==`

`Math.floor(new Date().valueOf()/1000)

#### convert variable to array if not array, otherwise, keep it the same

`[].concat(x)`

`==`

```js
if (!Array.isArray(x)) x = [x]
```

