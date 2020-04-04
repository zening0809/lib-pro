`camelCase` 转换字符串string为 驼峰写法。

> 骆驼式命名法（Camel-Case）

```javascript
又称驼峰式命名法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为驼峰格式的字符串
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
```

> *返回值*

```javascript
(string): 返回驼峰写法的字符串。
```

> *类型定义*

```javascript
type camelCaseType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.camelCase('nv Lib');
// => 'nvLib'
```

```javascript
_nv.camelCase('--nv-lib--');
// => 'nvLib'
```

```javascript
_nv.camelCase('__NV_LIB__');
// => 'nvLib'
```


