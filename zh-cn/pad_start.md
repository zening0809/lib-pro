`padStart` 以特定字符从结尾填充。

> 以特定字符从结尾填充（pad-Start）

```javascript
又称以特定字符从字符串开头自动填充法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为以特定字符特定长度从开头填充的字符串。
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
[length=0] (number) : 字符串的长度。
[chars=' '] (string) : 用来填充的字符。
```

> *返回值*

```javascript
(string): 返回以特定字符特定长度从开头填充的字符串。

```

> *类型定义*

```javascript
type padStartType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.padStart('abc', 8);
// => '     abc'
```

```javascript
_nv.padStart('abc', 2);
// => 'abc'
```

```javascript
_nv.padStart('abc', 8, '_-');
// => '_-_-_abc'
```


