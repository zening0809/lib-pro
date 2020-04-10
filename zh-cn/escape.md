`escape` 转特殊字符为HTML实体字符。

> 转义string中的 "&", "<", ">" , '"' , "'" , 和 "`" 字符为HTML实体字符（escape）

> *描述*

```javascript
转义string中的 "&", "<", ">" , '"' , "'" , 和 "`" 字符为HTML实体字符。不会转义其他字符。
虽然 ">" 是对称转义的，字符如 ">" 和 "/" 没有特殊的意义，所以不需要在 HTML 转义。 除非它们是标签的一部分，或者是不带引号的属性值。
```

> *入参*

```javascript
[string=''] (string) : 要转义的字符串。
```

> *返回值*

```javascript
(string): 返回转义后的字符串。
```

> *类型定义*

```javascript
type escapeType = (v: string) =>  string;
```

> *例子*

```javascript
_nv.escape('fred, barney, & pebbles');
// => 'fred, barney, &amp; pebbles'
```

```javascript
_nv.escape('<div>123</div>', '<span class="spanStyle">123&</span>', 'zn', '');
// => ''&lt;div&gt;123&lt;/div&gt;', '&lt;span class=&quot;spanStyle&quot;&gt;123&amp;&lt;/span&gt;', 'zn', '''
```


