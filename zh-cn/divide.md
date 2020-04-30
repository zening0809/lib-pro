`divide` 两个数相除。

> 两个数相除（divide）

> *描述*

```javascript
两个数相除。 可以满足js高精度计算 两个大数相除 
```

> *入参*

```javascript
dividend (number): 相除的第一个数。
divisor (number): 相除的第二个数。
```

> *返回值*

```javascript
(number): 返回商数。
```

> *类型定义*

```javascript
type divideType = (v: number, x: number) =>  number;
```

> *例子*


```javascript
_nv.divide(6, 4);
// =>  1.5
```
```javascript
_nv.divide(12, 3);
// => 4
```