`mean` 计算平均值。

> 计算最大值（mean）

> *描述*

```javascript
计算 array 中的最大值。 如果 array 是 空的或者假值将会返回 undefined。
```

> *入参*

```javascript
array (Array): 要迭代的数组。
```

> *返回值*

```javascript
(number): 返回平均值。
```

> *类型定义*

```javascript
type meanType = (v: number, x: number) =>  number;
```

> *例子*

```javascript 
_nv.max([4, 2, 8, 6]);
// => 5
```
```javascript
_nv.max([3, 4, 5]);
// => 4
```