`trim` 去除首尾空格。

> 从字符串中移除前面和后面的空白 或 指定的字符（trim）

> *描述*

```javascript
从字符串中移除前面和后面的空白 或 指定的字符 
```

> *入参*

```javascript
[string=''] (string) : 要处理的字符串
[chars=whitespace] (string) : 要处理的字符
```

> *返回值*

```javascript
(string): 返回处理后的字符串。
```

> *类型定义*

```javascript
type trimType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.trim('-_-abc-_-', '_-');
// => 'abc'
```
```javascript
_nv.trim('  abc  ');
// => 'abc'
```

