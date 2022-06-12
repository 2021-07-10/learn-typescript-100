# 2-14 静态属性，Setter和Getter

|本期版本|上期版本
|:---:|:---:
`Sun Jun 12 15:05:23 CST 2022` | -

```js
class Person{

  get name(){
    return this._name
  }

  set name(name:string) {
    this._name = name;
  }
}
```

单例模式

```js
class Demo{
  // 静态属性
  private static instance: Demo;
  private constructor(){}

  // 静态方法
  static getInstance(){
    if(!this.instance) {
      this.instance = new Demo();
    }
    return this.instance;
  }
}
```