# 4-6 函数泛型

|本期版本|上期版本
|:---:|:---:
`Sat Jun 11 23:39:25 CST 2022` | -

* 单个范型

```js
function join<T>(first: T, second: T){

}
join<number>(1,1)
```

```js
function map<T>(params: T[]){
}
function map<T>(params: Array<T>){
}
map<string>(['123'])
```

* 多个泛型

```js
function join<T, P>(first: T, second: P){

}

join<number,string>(1, '1')
join(1, '1')		// 推断
```
