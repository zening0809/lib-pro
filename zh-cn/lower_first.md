`lowerFirst` 。

> 首字母小写（lower-First）

```javascript
又称首字母转小写命名法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为首字母小写的字符串
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
```

> *返回值*

```javascript
(string): 返回以首字母小写字符串。
```

> *类型定义*

```javascript
type lowerFirstType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.lowerFirst('Fred');
// => 'fred'
```

```javascript
_nv.lowerFirst('FRED');
// => 'fRED'
```



