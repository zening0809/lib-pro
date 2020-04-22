`pad` 以特定字符从中间填充。

> 以特定字符从中间填充（pad）

```javascript
又称以特定字符从字符串中间自动填充法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为以特定字符特定长度从中间填充的字符串。
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
[length=0] (number) : 字符串的长度。
[chars=' '] (string) : 用来填充的字符。
```

> *返回值*

```javascript
(string): 返回以特定字符特定长度从中间填充的字符串。

```

> *类型定义*

```javascript
type padType = (v: string, x: number, y: string) =>  string;
```

> *例子*

```javascript
_nv.pad('abc', 8);
// => '  abc   '
```

```javascript
_nv.pad('abc', 2);
// => 'abc'
```

```javascript
_nv.pad('abc', 8, '_-');
// => '_-abc_-_'
```


