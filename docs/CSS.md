#CSS编码规范
##目录

##选择器
* 选择器不允许大写字母
* 使用中划线`-`作为连字符
* 选择器组大于一个时，每行一组
* 不允许使用`*`选择器

##属性
* 使用CSS缩写属性
* 小数点前如果是0，则省略
* 0后面不要添加单位
* 16进制颜色码可以使用缩写的必须使用缩写
* URL中不要使用引号
* 每个样式必须以`;`结尾

##缩进，空格，换行
* 一个缩进位4个空格
* 选择器与`{`之间必须添加一个空格
* `:`之前不能有空格，之后必须有空格
* 每行职能写一条样式

##书写顺序
1. 显示属性(position, top, right, z-index, display, float等)
2. 盒模型属性(width, height, padding, margin, border, background)
3. 文本属性(font, line-height, letter-spacing, color- text-align等)
4. 其他

##注释
###文件注释
```CSS
/*
 * @description: 中文说明
 * @author: name
 */
```
###单行注释
```CSS
/* 注意空格 */
```
###多行注释
```CSS
/*
 * 正文不能放在首尾位行，注意空格
 */
```

##其他
* 文件编码使用UTF-8无BOM
* 使用`'`,无特殊需要不允许使用`"`
* 字体族使用英文名（如：黑体(SimHei) 宋体(SimSun) 微软雅黑 (Microsoft Yahei））
* 禁止使用原生import（less，scss可用）
