`trimStart` 去除首部空格。

> 从字符串中移除前面的空白 或 指定的字符（trim-End）

> *描述*

```javascript
从字符串中移除前面的空白 或 指定的字符 
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
type trimStartType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.trimStart('-_-abc-_-', '_-');
// => 'abcc-_-'
```
```javascript
_nv.trimStart('  abc  ');
// => 'abcc  '
```
```javascript
_nv.map(['  foo  ', '  bar  '], _nv.trimStart);
// => ['foo  ', 'bar  ']
```
