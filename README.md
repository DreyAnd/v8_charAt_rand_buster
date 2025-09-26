# v8_charAt_rand_buster

Implementation of [v8_rand_buster](https://github.com/JorianWoltjer/v8_rand_buster/) when `Math.random()` is used to generate string-based codes in the following way:
```js
CHARSET.charAt(Math.floor(Math.random() * CHARSET.length))
```



