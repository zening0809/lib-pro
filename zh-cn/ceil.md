`ceil` 向上舍入。

> 向上舍入（ceil）

> *描述*

```javascript
根据 precision（精度） 向上舍入 number。
```

> *入参*

```javascript
number (number): 要向上舍入的值。
[precision=0] (number): 向上舍入的的精度。
```

> *返回值*

```javascript
(number): 返回向上舍入的值。
```

> *类型定义*

```javascript
type ceilType = (v: number, x: number) =>  number;
```

> *例子*

```javascript
_nv.add(6.004, 2);
// => '6.01'
```
```javascript
_nv.add(12.67, 1);
// => '12.7'
```
```javascript
_nv.add(-12.67, 1);
// => '-12.6'
```
```javascript
_nv.add(12.805, 2);
// => '12.81'
```