# 2-9 基础语法复习

|本期版本|上期版本
|:---:|:---:
`Thu Dec  8 23:52:31 CST 2022` | -


```js
const func = (str: string):number => {
  return parseInt(str, 10);
}

// 参数一般需要类型注解， 返回值类型可以通过类型推断出来
const func = (str: string) => {
  return parseInt(str, 10);
}
```

```js
const func: (str: string) => number = (str) => {
  return parseInt(str, 10);
}
```


```js
interface Person {
  name: 'string'
}
const rawData = '{"name": "dell"}';
const newData: Person = JSON.parse(rawData);
```


```js
let tmp: number | string = 123;
```