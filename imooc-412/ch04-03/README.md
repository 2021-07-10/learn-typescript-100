# 4-4 联合类型和类型保护

|本期版本|上期版本
|:---:|:---:
`Sat Jun 11 23:39:25 CST 2022` | -


**联合类型**

```js
const user: string|array;
```

### 类型保护

**类型断言**

```js
user as string
```

**in语法**

```js
if('map' in user) {
	user.map()
}
```

**typeof 语法**

```js
if(typeof username === 'string')
```

```js

username instanceof