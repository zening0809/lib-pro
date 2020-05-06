 `dateRange` 时间日期范围。

> 时间日期范围（dateRange）

> *描述*

```javascript
获得时间日期范围。
```

> *入参*

```javascript
[range = 'day'] (string): 要转化的时间范围。
[t = false] (boolean): 是否有具体到时分秒。
```

> *返回值*

```javascript
(array): 返回日期范围的数组。
```

> *类型定义*

```javascript
type dateRangeType = (v: string, t:boolean ) =>  array;
```

> *例子*

```javascript 
_nv.dateRange('day', true);
// => ['2020-04-03 00:00:00', '2020-04-03 23:59:59']
```

```javascript 
_nv.dateRange('week');
// => ['2020-03-27','2020-04-03']
```

```javascript 
_nv.dateRange('month');
// => ['2020-03-03','2020-04-03']
```