# 2-11 Interface接口 

|本期版本|上期版本
|:---:|:---:
`Sun Jun 12 14:41:16 CST 2022` | -

```js
interface Person {
  readonly name: string; 
  age?: number;
  [propName: string]: any;
  say(): string;
}
```

类应用接口

```js
class User implements Person
{

}
```

接口继承

```js
interface Teacher extends Person {
  teacher(): string;
}
```

定义函数

```js
interface SayHi {
  (word: string): string;
}
```

初始化项目

```js
tsc --init
```