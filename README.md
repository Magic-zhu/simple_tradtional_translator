#  网页简繁体中文转换 -改

 + 原作者信息
  + https://github.com/hustlzp/jquery-s2t
 +  Tested in IE6+, Chrome, Firefox.
  + Copyright 2013-2014 hustlzp
 + Released under the MIT license

>剥离了jquery，改写了使用方式

```javascript
//引入文件
<script type='text/javascript' src="./s2t.js"></script>
```
```javascript
    var dom = document.getElementsByTagName("html")[0];
    var tr = new translator();
    /*
    * dom-> dom元素 或者字符串  第二个参数0 ->简转繁 1反过来
    */
    tr.init(dom,0);
```
 
