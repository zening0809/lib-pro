`dateFormat` 日期格式化。

> 日期格式化（dateFormat）

> *描述*

```javascript
日期格式化。
```

> *入参*

```javascript
[param = ''] (any): 要转化的日期。
```

> *返回值*

```javascript
(string): 返回格式化的日期。
```

> *类型定义*

```javascript
type dateFormatType = (v: date, x: any) =>  string;
```

> *例子*

```javascript 
_nv.dateFormat(1585899104);
// => '2020-04-03'
```

```javascript 
_nv.dateFormat(1585899104373);
// => '2020-04-03'
```

```javascript 
_nv.dateFormat(1585899104373, 'yyyy-MM-dd hh:mm:ss');
// => '2020-04-03 15:31:44'
```