`replace` 替换字符串。

> 替换字符串 （replace）

```javascript
是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为以特定字符的替代字符串。
```

> *入参*

```javascript
[string=''] (string) : 待替换的字符串
pattern (RegExp|string) : 要匹配的内容
(Function|string) : 要替换的内容
```

> *返回值*

```javascript
(string): 返回替换完成的字符串。

```

> *类型定义*

```javascript
type replaceType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.replace('Hi Fred', 'Fred', 'Barney');
// => 'Hi Barney'
```



