# Century From Year [8 kyu] #1

```js
function century(year) {
return Math.ceil(year / 100);
}
```

# Ones and Zeros [7 kyu] #2

```js
const binaryArrayToNumber = arr => {
  arr = arr.join('');
  console.log(parseInt(arr));
  return parseInt(arr, 2);
};

```

# You're a square! [7 kyu] #3

```js
const isSquare = n => n >= 0 && Number.isInteger(Math.sqrt(n));
```

# Simple multiplication [8 kyu] #4

```js
function simpleMultiplication(number) {
return number % 2 == 0 ? number * 8 : number * 9;
}

```

# Beginner - Lost Without a Map [8 kyu] #5

```js
function maps(x){
return x.map((x) => x * 2);
}

```

# Vowel Count [7 kyu] #6

```js
function getCount(str) {
  //let vowels = ['a', 'e', 'i', 'o', 'u'];
let count = 0;
  const wovels = "aeiou";
  for (let i = 0; i < str.length; i++) {
    if (wovels.includes(str[i]))
      count++;
  } 
  return count;
  //return str.split('').filter((char) => vowels.includes(char)).length;
  
}
```

