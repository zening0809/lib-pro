`truncate` 字符串截断

> 字符串截断（truncate）

> *描述*

```javascript
截断string字符串，如果字符串超出了限定的最大值。 被截断的字符串后面会以 omission 代替，omission 默认是 "..." 
```

> *入参*

```javascript
[string=''] (string): 要截断的字符串。
[options={}] (Object): 选项对象。
[options.length=30] (number): 允许的最大长度。
[options.omission='...'] (string): 超出后的代替字符。
[options.separator] (RegExp|string): 截断点。
```

> *返回值*

```javascript
(string): 返回截断的字符串.
```

> *类型定义*

```javascript
type trnucateType = (v: string, x: object, y: number, z: string, q: RegExp|string) =>  string;
```

> *例子*

```javascript
_nv.truncate('hi-diddly-ho there, neighborino');
// => 'hi-diddly-ho there, neighbo...'
 
_nv.truncate('hi-diddly-ho there, neighborino', {
  'length': 24,
  'separator': ' '
});
// => 'hi-diddly-ho there,...'
 
_nv.truncate('hi-diddly-ho there, neighborino', {
  'length': 24,
  'separator': /,? +/
});
// => 'hi-diddly-ho there...'
 
_nv.truncate('hi-diddly-ho there, neighborino', {
  'omission': ' [...]'
});
// => 'hi-diddly-ho there, neig [...]'
```


