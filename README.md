fizzbuzz.js
===========

In case you were wondering...

```js
fizzBuzz = function(x, y, ans) {
	return x % y ? '' : ans;
}

for (var n = 1; n < 101; n++) {
	console.log(fizzBuzz(n, 3, 'Fizz') + fizzBuzz(n, 5, 'Buzz') || n);
} 
```

Go ahead, paste it into your js console. I'll be over here waiting...
