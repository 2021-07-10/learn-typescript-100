# 4-13 描述文件中的全局类型（下）

|本期版本|上期版本
|:---:|:---:
`Sat Jun 11 23:39:25 CST 2022` | -


```js
interface JQuery {
	(readyFunc: ()=>void): void;
	(selector: string): JqueryInstance
}
```