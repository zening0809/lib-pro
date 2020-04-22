`trimEnd` 去除尾部空格。

> 从字符串中移除后面的空白 或 指定的字符（trim-End）

> *描述*

```javascript
从字符串中移除后面的空白 或 指定的字符 
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
type trimEndType = (v: string, x: string) =>  string;
```

> *例子*

```javascript
_nv.trimEnd('-_-abc-_-', '_-');
// => 'c-_-abc'
```
```javascript
_nv.trimEnd('  abc  ');
// => '  abc'
```
```javascript
_nv.map(['  foo  ', '  bar  '], _nv.trimEnd);
// => ['  foo', '  bar']
```
