# Thursday 07.21.22

## Print Special Numbers

```js script
for (let i = 0; i < 100; i++) {
  if(i%2 == 0){
    console.log(i)
  }
}
```

## Bad Code 

The code to correct is:

```js script
var cond = false;

if ((cond = true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```

Corrected code: 
```js script
var cond = false;

if ((cond == true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}
```

## Bad Code 2 

This is the code to correct: 

```js script
var n = 100;

if (n == 100) {
  console.log('This is a special number!');
}
if (n < 1000) {
  console.log('');
} else {
  console.log('Just a regular number');
}
if (n % 10 == 0) {
  console.log('This number is multiple of 10');
}
```

Corrected code: 

```js script
```
