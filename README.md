#### get unix timestamp

`+new Date() / 1000 | 0`

`==`

`Math.floor(new Date().valueOf()/1000)

#### convert to array if single arg

`[].concat(x)`

Say, yo don't know if x is an array or single value, but you want to do an array function like map on it/them, either way. This will convert a single value to an array of the one item, if it's not an array, and is essentially a noop if it is an array
