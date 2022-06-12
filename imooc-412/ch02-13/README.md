# 2-13 类中的访问类型和构造器

|本期版本|上期版本
|:---:|:---:
`Sun Jun 12 14:56:53 CST 2022` | -

* public 允许在类的外部调用
* private 允许在类的内部调用
* protected 允许在类内以及子类中使用

传统写法
 
```js
class Person {
  public name: string;

  constructor(name: string){
    this.name = name;
  }
}
```

简化写法

```js
class Person {

  constructor(public name: string){

  }
}
```

调用父类构造函数

```js
class Teacher extends Person {
  constructor(public age: number){
    super('xx')
  }
}
```
