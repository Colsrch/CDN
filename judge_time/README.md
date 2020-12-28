## 使用方法

### 引入js
``` js
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/Colsrch/CDN@master/judge_time/js.js"></script>
```
### 配置js
``` js
var res = computeSunRiseSunSet(纬度,经度,8);
res.str; //日出时间 | 正午时间 | 日落时间
res.strSunRise; //日出时间
res.strNoon; //正午时间
res.strSunSet; //日落时间
res.SunRise; //Date型
res.SunSet; //Date型
```