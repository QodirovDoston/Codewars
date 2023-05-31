# [1. Codewars1](https://www.codewars.com/kata/55b42574ff091733d900002f/train/javascript)


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


# [2. getMiddle](https://www.codewars.com/kata/56747fd5cb988479af000028/train/javascript)

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


# [3. A Needle in the Haystack](https://www.codewars.com/kata/56676e8fabd2d1ff3000000c/train/javascript)
## *answer*

```js

function findNeedle(haystack) {
  for (let i = 0; i < haystack.length; i++) {
    if (haystack[i] ==="needle"){
      return `found the needle at position ${i}`;
    }}return `needle not found`;
    }
console.log(findNeedle(["doston","doston","sardor","doston","doston","sardor","needle","doston"]));

// ?////////////////// BU INTERNETDAN
function findNeedle(haystack = []) {
  return haystack.indexOf('needle') !== -1
    ? `found the needle at position ${haystack.indexOf('needle')}`
    : 'needle not found';
}
```


# [3. A Needle in the Haystack](https://www.codewars.com/kata/56676e8fabd2d1ff3000000c/train/javascript)
## *answer*


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

# [4.  5 without numbers !! ](https://www.codewars.com/kata/59441520102eaa25260000bf/train/javascript)

## **Answer**

```js
function unusualFive() {
  return ("dosto").length;
}
```



# [5.  Highest and Lowest](https://www.codewars.com/kata/554b4ac871d6813a03000035/train/javascript)

## **Answer**

```js
function highAndLow(numbers){  
  const num = numbers.split(' ').map(Number);
  const hig = Math.max(...num);
  const low = Math.min(...num);
  return `${hig} ${low}`;
}
console.log(highAndLow("1 2 3 4 23 5"))

```
# [6.  Is it even?](https://www.codewars.com/kata/555a67db74814aa4ee0001b5/train/javascript)

## **Answer**

```js
function testEven(n) {
  return n % 2 === 0 ? true : false
}
```