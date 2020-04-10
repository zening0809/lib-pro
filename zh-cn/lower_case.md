`lowerCase` 以空格分隔的小写字符串。

> 转小写（lower-Case）

```javascript
又称转小写命名法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为以空格分隔并去掉特殊字符的小写单词的字符串
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
```

> *返回值*

```javascript
(string): 返回以空格分隔的小写字符串。
```

> *类型定义*

```javascript
type lowerCaseType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.lowerCase('--Foo-Bar--');
// => 'foo bar'
```

```javascript
_nv.lowerCase('fooBar');
// => 'foo bar'
```

```javascript
_nv.lowerCase('__FOO_BAR__');
// => 'foo bar'
```


