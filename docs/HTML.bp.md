#HTML最佳实践
##目录

##保持标签闭合
```html
<!--bad-->
<li>Some text here.  
<li>Some new text here.  
<li>You get the idea.

<!--good-->
<ul>  
	<li>Some text here. </li>  
	<li>Some new text here. </li>  
	<li>You get the idea. </li>  
</ul> 
```

##不要使用内联样式
```html
<!--bad-->
<p style="color: #CCC; font-size:16px; font-family: arial">An example to illustrate inline style in html</p>

<!--good-->
<p class="html_bp">An example to illustrate inline style in html</p>
.html_bp{
	color:#CCC;
	font-size:16px;
	font-family: arial;
}
```

##使用连续的标题
```html
<!--bad-->
<h1>This is the topmost heading</h1>
<h3>This is a sub-heading underneath the topmost heading</h3>

<!--good-->
<h1>This is the topmost heading</h1>
<h2>This is a sub-heading underneath the topmost heading</h2>
```

##在合适的地方使用合适的标签
HTML标签是构造规范内容结构的关键。例如，`<em>`标签用来强调重点内容。`<p>`标签适用于突出文章段落。如果想要在段落间加空行，就不要使用`<br/>`标签。

```html
<!--bad-->
<p>段落一内容<br/>
    段落二内容</p>

<!--good-->
<p>段落一内容</p>
<p>段落二内容</p>
```

##为图片标签添加alt属性
```html
<!--bad-->
<img id="logo" src="images/bgr_logo.png" />

<!--good-->
<img id="logo" src="images/bgr_logo.png" alt="Anson Cheung - Web Development" />
```

##适当的添加title属性
```html
<!--bad-->
<a href="javascript:;">查看候选人张…</a>

<!--good-->
<a href="javascript:;" title="查看候选人张三的简历">查看候选人张…</a>
```

##给页面添加必要的meta
```html
<!--good-->
<meta name="author" content="John Doe">
<meta name="copyright" content="&copy; 1997 Acme Corp.">
<meta name="keywords" content="corporate,guidelines,cataloging">
<meta name="date" content="1994-11-06T08:49:37+00:00">
<meta name="description" content="Best practice for html"/>
```

##标签名使用小写
```html
<!--bad-->
<DIV>
<P>Here's an interesting fact about corn. </P>
</DIV>

<!--good-->
<div>
<p>Here's an interesting fact about corn. </p>
</div>
```

## 不要滥用<br />
```html
<!--bad-->
<span>abcde</span>
<br />
<em>def</em>


<!--good-->
<p>
Here's an interesting fact about corn. 
<br /> u a right;
</p>
```
