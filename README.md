# pageination JS实现自动分页按钮
## html
				
```
<!--分页-->
<div class="myFY">  
  <div class="ui circular labels">
    <a class="ui label" onclick="pageLeft();">&lt;&lt;</a>
    <span id="fys"></span>
    <a class="ui label" onclick="pageRight();">&gt;&gt;</a>
  </div>
</div>
```

## js
```
//分页
var pageIn = pageInaTion('<a class="ui label">','</a>','#fys',5,22);
pageIn.inits();
pageLeft = function(){
pageIn.pageLeft();
}
pageRight = function(){
pageIn.pageRight();
}
```
## 依赖于
```
<script type="text/javascript" src="js/jquery-3.3.1.min.js" ></script>`
<script src="js/pagination.js" type="text/javascript" charset="utf-8"></script>
```
