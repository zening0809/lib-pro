`split` 字符串拆分。

> 以 separator 拆分字符串 （split） 

```javascript
又称字符串拆分法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为 snake case。
```

> *入参*

```javascript
[string=''] (string) : 要拆分的字符串。
[separator] (RegExp|string) : 拆分的分隔符
[limit] (number) : 限制的数量
```

> *返回值*

```javascript
(string): 返回拆分部分的字符串的数组。

```

> *类型定义*

```javascript
type splitType = (v: string, x: RegExp|string, y: number) =>  string;
```

> *例子*

```javascript
_nv.split('a-b-c', '-', 2);
// => ['a', 'b']
```



