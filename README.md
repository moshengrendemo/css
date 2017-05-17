# css
有关css入门学习的小技巧

                  css如何让浮动元素水平居中
 对于定宽的非浮动元素我们可以在CSS中用 margin:0 auto 进行水平居中，对于不定宽的浮动元素我们也有一个常用的技巧解决它的水平居中问题。解决水平居中问题有很多种方法，下面先给大家分享一下三种方法
方法一：
1、HTML 部分：

<div class="box">
 <p>我是浮动的</p>
 <p>我也是居中的</p>
</div>
2、CSS 部分：
.box{
 float:left;
 position:relative;
 left:50%;
}
p{
 float:left;
 position:relative;
 right:50%;
}


