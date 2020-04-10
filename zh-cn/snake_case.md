`snakeCase` 转换字符串为 snake case。

> 转换字符串为 （snake-Case） 

```javascript
是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为 snake case。
```

> *入参*

```javascript
[string=''] (string) : 要转换的字符串
```

> *返回值*

```javascript
(string): 返回转换后的字符串。

```

> *类型定义*

```javascript
type snakeCaseType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.snakeCase('Foo Bar', 'fooBar', '--FOO-BAR--', 'foo2bar');
// => 'foo_bar', 'foo_bar', 'foo_bar', 'foo_2_bar'
```



