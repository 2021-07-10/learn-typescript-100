# 2-10 数组和元组

|本期版本|上期版本
|:---:|:---:
`Sun Jun 12 13:19:56 CST 2022` | -

## 数组

```js
number[]
(number | string)[]
```

对象数组

```js
{name: string}[]
```

`type alias` 类型别名

```js
type User = {name: string, age: number}
User[]
```

```js
class Teacher {
  name: string;
  age: number;
}
```

## 元组 tuple

```js
[string, string, number]
```

```js
const teacherList: [string, string, number][] = [
  ['dell', 'male', 19],
  ['sun', 'female', 26],
  ['jeny', 'female', 38]
]
```