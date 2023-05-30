# [Codewars1](https://www.codewars.com/kata/55b42574ff091733d900002f/train/javascript)


## *Answer*

```js
function friend(friends){
  let newarr = []
    for(let name of friends){
      if(name.length === 4 ){
        newarr.push(name)
      }
    }
  return newarr
}
```


# [getMiddle](https://www.codewars.com/kata/56747fd5cb988479af000028/train/javascript)

## *Answer*

```js
function getMiddle(s) {
  const mind = Math.floor(s.length / 2);
  if (s.length % 2 === 1) {
    return s[mind];
  } else {
    return s[mind - 1] + s[mind];
  }
}
```
