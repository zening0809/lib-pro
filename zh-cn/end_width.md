`endWidth` 是否以特定字符结尾。

> 是否以特定字符结尾（end-Width）

```javascript
又称是否以特定字符结尾法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
返回字符串是否以特定字符串结尾的布尔值。
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
[target] (string) : 要匹配的字符串.
[position=string.length] (number) : 开始匹配的位置。
```

> *返回值*

```javascript
(boolean): 返回布尔值。
```

> *类型定义*

```javascript
type endWidthType = (v: string, x: string, y: number) =>  string;
```

> *例子*

```javascript
_nv.endWidth('abc', 'c');
// => 'true'
```

```javascript
_nv.endWidth('abc', 'b');
// => 'false'
```

```javascript
_nv.endWidth('abc', 'c', 4);
// => 'true'
```

```javascript
_nv.endWidth('abc', 'b', -2);
// => 'false'
```

