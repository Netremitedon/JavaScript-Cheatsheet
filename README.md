# JavaScript-Cheatsheet
<img src="http://pixeltocode.co/images/logo.png" width="100px">

<img src="https://www.pixeltocode.co/images/mission-statement.png">

  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1024px-Unofficial_JavaScript_logo_2.svg.png" alt="JavaScript Logo" width="200px">


## Array(s)

```
  ['a', 'b' ].concat(['c'])                   // ['a', 'b', 'c']
  
  [ 'a', 'b' ].join('-')                      // 'a-b'
  
  [ 'a', 'b', 'c'].slice(1)                   // [ 'b', 'c' ]
  
  [ 'a', 'b', 'b' ].indexOf('b')              // 1
  
  [ 'a', 'b', 'b' ].lastIndexOf('b')          // 2
  
  [ 'a', 'b' ].length                         // 2

  let arr = [ 'a', 'b', 'c' ];
      arr.forEach( x => console.log( x ) );
  let newArr =  arr.join('-');
      console.log( newArr );
```

```
  [ 1, 2, 3 ].map( a => a * 2 );              // [ 2, 4, 6 ]
  
  [ 1, 2, 3 ].filter( a => a <= 2 );          // [ 1, 2 ]
  
  [ 1, 2, 3 ].reduce( ( a, b ) => a + b );    // 6
  
  [ 1, 2, 3 ].every( a => a > 5 );            // false
  
  [ 1, 2, 3 ].some( a => a <= 1 );            // true
  
  [ 1, 2, 3 ].reverse();                      // [ 3, 2, 1 ]
  
  [ 2, 12, 3 ].sort();                        // [ 12, 2, 3 ]
```

## Object(s)

```
  const zoo = {
    panda: '🐼',
    lion:  '🦁',
  }
  
  
  // Show keys
  
  Object.keys(zoo)    // ['panda', 'lion']
  
  
  // Show values
  
  Object.values(zoo)  // [ '🐼', '🦁' ]
  
  
  // Keys & Values
  
  Object.entries(zoo) // [[ 'panda, '🐼'], [ 'lion', '🦁' ]]
  
  
```

## Convert Float to Integer

```

const int = 13.7 | 0  // int = 13

```

## Convert to Boolean

```

let isTrue = !0
// isTrue = true
// typeof isTrue : boolean

```

## Convert to String

```

let value = 11 + ''
// value = '11'
// typeof value : string

```

## Covert to Integer

```

let int = +'15'
// int = 15
// typeof int : number

```
