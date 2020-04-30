`floor` 向下舍入。

> 向下舍入（floor）

> *描述*

```javascript
根据 precision（精度） 向下舍入 number。
```

> *入参*

```javascript
number (number): 要向下舍入的值。
[precision=0] (number): 向下舍入的的精度。
```

> *返回值*

```javascript
(number): 返回向下舍入的值。
```

> *类型定义*

```javascript
type floorType = (v: number, x: number) =>  number;
```

> *例子*

```javascript
_nv.floor(6.004, 2);
// => '6.00'
```
```javascript
_nv.floor(12.67, 1);
// => '12.6'
```
```javascript
_nv.floor(-12.67, 1);
// => '-12.7'
```
```javascript
_nv.floor(12.805, 2);
// => '12.80'
```