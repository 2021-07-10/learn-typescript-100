# 2-15 抽象类 

|本期版本|上期版本
|:---:|:---:
`Sun Jun 12 15:26:59 CST 2022` | -


```js
class Person
	public readonly name:string;
	constructor(name:string) {
		this.name = name
	}
end
```

抽象类

```js
abstract class Geom{
  abstract getArea(): number;
}
```

接口继承

```js
interface Person {
  name: string
}

interface User extends Person
{

}
``` 