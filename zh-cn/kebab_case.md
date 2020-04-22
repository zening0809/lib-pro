`kebabCase` 转换string为 kebab case。

> 转换string为 kebab case（kebab-Case）

```javascript
转换字符串string为 kebab case。
```
> *描述*

```javascript
转换字符串string为 kebab case
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
type kebabCaseType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.kebabCase('Foo Bar');
// => 'foo-bar'
 
_nv.kebabCase('fooBar');
// => 'foo-bar'
 
_nv.kebabCase('__FOO_BAR__');
// => 'foo-bar'

_nv.lowerCase('__FOO_BAR__');
// => 'foo bar'
```


