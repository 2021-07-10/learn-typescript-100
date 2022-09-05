# 4-12 描述文件中的全局类型（上）

|本期版本|上期版本
|:---:|:---:
`Sat Jun 11 23:39:25 CST 2022` | -


> `jquery.d.ts`

定义变量

```js
declare var $: (params: ()=> void) => void
```

定义函数

```js
declare function
```


优化

```js
interface JqueryInstance
{
	html: (html: string) => {}
}
```