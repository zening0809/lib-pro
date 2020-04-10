`string2Group` 字符串拆分。

> （string2-Group）

```javascript
是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为以特定长度的字符串数组。
```

> *入参*

```javascript
[string=''] (string) : 要转义的字符串。
[n=0] (number) (number) : 要分隔的长度。
```

> *返回值*

```javascript
(Array): 返回以以特定长度的字符串数组。

```

> *类型定义*

```javascript
type string2GroupType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.string2Group('1223456789',3);
// => ['122', '345', '678', '9']
```

```javascript
_nv.string2Group('abcsdadad',3);
// => ['abc', 'sda', 'dad']
```

```javascript
_nv.string2Group('',3);
// => []
```


