`stringRevert` 是否以特定字符结尾。

> 是否以特定字符开头（string-Revert）

> *描述*

```javascript
返回反转过的字符串。
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
```

> *返回值*

```javascript
(string): 返回已反转的字符串。
```

> *类型定义*

```javascript
type stringRevertType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.stringRevert('123', 'abc', '');
// => '321', 'cba', ''
```


