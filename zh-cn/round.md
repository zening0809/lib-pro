`round` 计算最小值。

> 四舍五入（round）

> *描述*

```javascript
根据 precision（精度） 四舍五入 number。
```

> *入参*

```javascript
number (number): 要四舍五入的数字。
[precision=0] (number): 四舍五入的精度。
```

> *返回值*

```javascript
(number): 返回四舍五入的数字。
```

> *类型定义*

```javascript
type roundType = (v: number, x: number) =>  number;
```

> *例子*

```javascript 
_nv.round(4.786, 2);
// => 4.79
```
```javascript
_nv.round(4060, -2);
// => 4100
```