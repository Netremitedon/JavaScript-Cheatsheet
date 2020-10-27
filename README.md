# JavaScript-Cheatsheet

## Array(s)

```
  ['a', 'b' ].concat(['c'])          // ['a', 'b', 'c']
  [ 'a', 'b' ].join('-')              // 'a-b'
  [ 'a', 'b', 'c'].slice(1)           // [ 'b', 'c' ]
  [ 'a', 'b', 'b' ].indexOf('b')      // 1
  [ 'a', 'b', 'b' ].lastIndexOf('b')  // 2
  [ 'a', 'b' ].length                 // 2

  let arr = [ 'a', 'b', 'c' ];
      arr.forEach( x => console.log( x ) );
  let newArr =  arr.join('-');
      console.log( newArr );
```
