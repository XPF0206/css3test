# css3test

> 学习css3时的笔记。


--------------------------------------------

## css3选择器

1.  css3后代选择器
	- .list li:only-child 选中在list中作为唯一的li子元素存在<br>

	- .list :only-child 选中list中的只有唯一一个子元素的 元素
	------------------------------------
	

3. 伪类选择器
	- :focus 匹配获得焦点的input元素
	- :first-letter 匹配p标签的第一个文字
	- :first-line 匹配p标签的第一行文字
	- :before 在每个 <p>元素的内容之前插入内容。(行内标签)
	- :after 在每个 <p> 元素的内容之后插入内容。(行内标签)

> :before、:after 功能
> 1. 清除浮动
```css
/*清除浮动*/
.clf:after,.clf:before{
	content:"";
	display:block;
	clear:both;
}
```
> 2. 做一些常用效果  “”    加上图标


4. 属性选择器
- [attr] 选中带有指定属性的元素
- [attr=value]  选中带有指定属性和值的元素
- [attribute~=value] 选中值中含有指定字符的元素
- [attribute|=value] 选中以某个字符开头的元素



5. 伪类选择器
