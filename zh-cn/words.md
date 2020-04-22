`words` 拆分字符串为数组

> 拆分字符串为数组（words）

> *描述*

```javascript
拆分字符串string中的词为数组。
```

> *入参*

```javascript
[string=''] (string): 要拆分的字符串。
[pattern] (RegExp|string): 匹配模式。
```

> *返回值*

```javascript
(Array): 返回拆分string后的数组。
```

> *类型定义*

```javascript
type upperCaseType = (v: string, x: RegExp|string) =>  string;
```

> *例子*

```javascript
_nv.words('fred, barney, & pebbles');
// => ['fred', 'barney', 'pebbles']
 
_nv.words('fred, barney, & pebbles', /[^, ]+/g);
// => ['fred', 'barney', '&', 'pebbles']
```


