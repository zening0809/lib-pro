`getTNum` 日期转时间戳。

> 日期转时间戳（getTNum）

> *描述*

```javascript
指定日期转换为时间戳。
```

> *入参*

```javascript
[date = ''] (string): 要转化的日期时间戳。
```

> *返回值*

```javascript
(number): 返回时间戳。
```

> *类型定义*

```javascript
type getTNumType = (v: string) =>  number;
```

> *例子*

```javascript 
_nv.getTNum('2015-03-05 17:59:00.0');
// => 1425549540000
```
