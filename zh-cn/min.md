`min` 计算最小值。

> 计算最小值（min）

> *描述*

```javascript
计算 array 中的最小值。 如果 array 是 空的或者假值将会返回 undefined。
```

> *入参*

```javascript
array (Array): 要迭代的数组。
```

> *返回值*

```javascript
(*): 返回最小的值。
```

> *类型定义*

```javascript
type maxType = (v: number, x: number) =>  number;
```

> *例子*

```javascript 
_nv.max([4, 2, 8, 6]);
// => 2
```
```javascript
_nv.max([]);
// => 'undefined'
```