`multiply` 两个数相乘。

> 两个数相乘（multiply）

> *描述*

```javascript
两个数相乘。可以满足js高精度计算 两个大数相乘
```

> *入参*

```javascript
augend (number): 相乘的第一个数。
addend (number): 相乘的第二个数。
```

> *返回值*

```javascript
(number): 返回乘积。
```

> *类型定义*

```javascript
type multiplyType = (v: number, x: number) =>  number;
```

> *例子*

```javascript
_nv.multiply(3, 2);
// => 6
```
```javascript
_nv.multiply(12,2);
// => 24
```