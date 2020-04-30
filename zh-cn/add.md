`add` 两个数相加。

> 两个数相加（add）

> *描述*

```javascript
两个数相加。 可以满足js高精度计算 两个大数相加 
```

> *入参*

```javascript
augend (number): 相加的第一个数。
addend (number): 相加的第二个数。
```

> *返回值*

```javascript
(number): 返回总和。
```

> *类型定义*

```javascript
type addType = (v: number, x: number) =>  number;
```

> *例子*

```javascript
_nv.add(9999999999999999999999999999999999, 1);
// => '10000000000000000000000000000000000'
```
```javascript
_nv.add(12.67,13);
// => '25.67'
```
```javascript
_nv.add(-12.67,-13);
// => '-25.67'
```
```javascript
_nv.add(12.67,-130.7);
// => '-118.03'
```