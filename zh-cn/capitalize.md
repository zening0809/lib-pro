`capitalize` 仅字符串首字母大写。

> 仅首字母大写命名法（capitalize）

```javascript
又称仅首字母命名法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为仅首字母大写的字符串
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
```

> *返回值*

```javascript
(string): 返回仅首字母大写的字符串。
```

> *类型定义*

```javascript
type capitalizeType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.capitalize('FRED');
// => 'Fred'
```

```javascript
_nv.capitalize('znK');
// => 'Znk'
```

```javascript
_nv.capitalize('Wss');
// => 'Wss'
```


