`subtract` 两数相减。

> 两数相减（subtract）

> *描述*

```javascript
两数相减 可以满足js高精度计算 两个大数相减
```

> *入参*

```javascript
minuend (number): 相减的第一个数。
subtrahend (number): 相减的第二个数。
```

> *返回值*

```javascript
(number): 返回差。
```

> *类型定义*

```javascript
type subtractType = (v: number, x: number) =>  number;
```

> *例子*

```javascript 
_nv.subtract(5, 2);
// => 3
```
```javascript
_nv.subtract(40, 12);
// => 28
```