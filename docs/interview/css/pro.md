# css高级面试题
dsf
##  如何实现不确定宽高的图片上下左右居中
```css
 img{
     position:absolute;
     top:0; /* 四周拉力相同 */
     right:0; /* 四周拉力相同 */
     bottom:0; /* 四周拉力相同 */
     left:0; /* 四周拉力相同 */
     margin:auto; /* 再设置 marign 自动 */
   }
```

## 纯css写倒三角的原理：
```css
.kailong{
	width:0;
    height:0;
	border-right:50px solid transparent;
	border-left:50px solid transparent;
	border-bottom:50px solid red;
}
```