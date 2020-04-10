`repeat` 重复 N 次字符串。

> 重复 N 次字符串（repeat）

```javascript
又称重复 N 次字符串法，是电脑程式编写时的一套命名规则（惯例）。是指混合使用大小写字母来构成变量和函数的名字。
```
> *描述*

```javascript
将字符串转换为以特定字符重复 N 次的字符串。
```

> *入参*

```javascript
[string=''] (string) : 要重复的字符串。
[n=0] (number) (number) : 重复的次数。
```

> *返回值*

```javascript
(string): 返回以特定字符特定长度从中间填充的字符串。

```

> *类型定义*

```javascript
type repeatType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.repeat('*', 3);
// => '***'
```

```javascript
_nv.repeat('abc', 2);
// => 'abcabc'
```

```javascript
_nv.repeat('abc', 0);
// => ''
```


