# grayscale
浏览器界面统一变灰色（兼容ie）
因为2020年4月4号的特殊需求，网站需要进行全部变灰显示，以下代码可在多数浏览器试用

滤镜 ：filter

html{
    -webkit-filter:grayscale(100%);
    filter:grayscale(100%);
}

ie浏览器兼容方案

可以引入grayscale.js，但是有个弊端就是轮播跟界面的动态效果一并消失了。如有其它方案，可在评论区交流。
