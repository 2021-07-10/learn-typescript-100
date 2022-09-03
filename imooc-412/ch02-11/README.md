# 2-11 Interface接口 

|本期版本|上期版本
|:---:|:---:
`Sun Jun 12 14:41:16 CST 2022` | -


* 优先使用接口，其次使用类型别名
* 以字面量直接传递对象会进行强校验

```js
interface Person {
  readonly name: string; 
  age?: number;
  \[propName: string]: any; # 其他属性
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