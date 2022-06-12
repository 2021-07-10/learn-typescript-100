# 2-8 函数相关类型

|本期版本|上期版本
|:---:|:---:
`Sun Jun 12 10:05:56 CST 2022` | -

函数执行不完

```js
function errorEmitter(): never {
  throw new Error();
  console.log('success')
}
```

解构语法

```js
function add({first, second}: {first: number, second: number}){
  return first + second;
}
```

