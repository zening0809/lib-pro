`startCase` 转换字符串为 start case。

> 以 startCase 转换字符串为 start case

```javascript
又称字符串拆分法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为 snake case。
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串。
```

> *返回值*

```javascript
(string): 返回转换后的字符串。

```

> *类型定义*

```javascript
type startCaseType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.startCase('--foo-bar');
// => 'Foo Bar'
```

```javascript
_nv.startCase('fooBar');
// => 'Foo Bar'
```

```javascript
_nv.startCase('__foo_bar__');
// => 'Foo Bar'
```
