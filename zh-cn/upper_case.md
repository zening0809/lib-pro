`upperCase` 空格分隔大写单词

> 空格分隔大写单词（upperCase）

> *描述*

```javascript
转换字符串string为 空格 分隔的大写单词。
```

> *入参*

```javascript
[string=''] (string): 要转换的字符串。
```

> *返回值*

```javascript
(string): 返回大写单词。
```

> *类型定义*

```javascript
type upperCaseType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.upperCase('--foo-bar');
// => 'FOO BAR'
 
_nv.upperCase('fooBar');
// => 'FOO BAR'
 
_nv.upperCase('__foo_bar__');
// => 'FOO BAR'
```


