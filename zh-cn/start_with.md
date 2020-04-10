`endWidth` 是否以特定字符结尾。

> 是否以特定字符开头（end-Width）

> *描述*

```javascript
返回字符串是否以特定字符串开头的布尔值。
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
type startWidthType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.endWidth('abc', 'c');
// => 'false'
```

```javascript
_nv.endWidth('abc', 'a');
// => 'true'
```

```javascript
_nv.endWidth('abc', 'b', 1);
// => 'true'
```

```javascript
_nv.endWidth('abc', 'bc', 1.2);
// => 'true'
```

