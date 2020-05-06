`getDay` 指定天数后的日期。

> 指定天数后的日期（getDay）

> *描述*

```javascript
获得 指定天数后的日期格式。
```

> *入参*

```javascript
[compute = ''] (number): 要转化的日期时间戳。
[format = now()] (string): 要转化的日期时间戳。
```

> *返回值*

```javascript
(string): 返回时间戳。
```

> *类型定义*

```javascript
type getTNumType = (v: number, x: string) =>  string;
```

> *例子*

```javascript 
_nv.getDay(1);
// => '2020-04-04'
```
