`sum` 计算array中值的总和。

> 数组值总和（sum）

> *描述*

```javascript
计算 array 中值的总和 可以满足js高精度计算 多个大数相加。
```

> *入参*

```javascript
array (Array): 要迭代的数组。
```

> *返回值*

```javascript
(number): 返回总和。
```

> *类型定义*

```javascript
type sumType = (v: array) =>  number;
```

> *例子*

```javascript 
_nv.sum([4, 2, 8, 6]);
// => 20
```
```javascript
_nv.round(4060, -2);
// => 4100
```