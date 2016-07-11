# 国内社交关注按钮（ChinaSocialFollowUsButtons）
[![](http://www.wordpressleaf.com/logo.png)](http://www.wordpressleaf.com/)
<br/><br/> 
<a href="http://www.wordpressleaf.com/2016_24.html"><img align="right" src="http://www.wordpressleaf.com/logo-app.png" width="248" height="auto"/></a>
国内社交关注按钮（ChinaSocialFollowUsButtons）是一套灵活组合的社交关注按钮，支持国内外主要的社交网站，采用的是字体图标，你可以在这里看到按钮使用的实例。 [**这里**](http://www.wordpressleaf.com) 



你可以访问我们[**ChinaSocialFollowUsButtons**](https://github.com/yehaicao/ChinaSocialFollowUsButtons)项目获取源代码。





## 演示地址
> [**观看演示**](http://www.wordpressleaf.com/)

## 使用步骤
1) 在网页头部加载css样式和jquery.js。注意要加载font-awesome的CSS样式，在这之前要将FONT文件夹复制到静态文件夹中，与CSS文件夹同级:

```html
  <script src="js/jquery.js"></script>
  <link rel="stylesheet" href="css/csfub.css" />
  <link rel="stylesheet" href="css/font-awesome.min.css?ver=4.4.0'" />


```

2) 复制任意的 `.menu-social` 列表到所需的位置:

```html
<!-- 按钮从这里开始. 复制 div到你的文档. -->
<div id="menu-social" class="menu">
	<ul id="menu-social-items" class="menu-items" style="-webkit-padding-start: 0px;">
		<li class="menu-item">
			<a title="关注我们的新浪微博" target="_blank" rel="nofollow" href="http://weibo.com"><span class="screen-reader-text">新浪微博</span></a>
		</li>
		<li class="menu-item">
	    <a title="关注我们的腾讯微博" target="_blank" rel="nofollow" href="http://t.qq.com"><span class="screen-reader-text">腾讯微博</span></a>
	  </li>
		<li class="menu-item">
			<a title="关注我们的QQ空间" target="_blank" rel="nofollow" href="http://qzone.qq.com"><span class="screen-reader-text">QQ空间</span></a>
		</li>
		<li class="menu-item">
			<a title="关注我们的github主页" target="_blank" rel="nofollow" href="https://github.com/yehaicao/"><span class="screen-reader-text">github</span></a>
		</li>
				<li class="menu-item">
			<a title="关注我们的人人主页" target="_blank" rel="nofollow" href="https://zhan.renren.com/"><span class="screen-reader-text">github</span></a>
		</li>
		<li class="menu-item">
			<a title="关注我们的微信公众号" target="_blank" rel="nofollow" href="http://wx.qq.com"><span class="screen-reader-text">微信公众号</span></a>
		</li>
		<li class="menu-item">
			<a title="关注我们的百度空间" target="_blank" rel="nofollow" href="http://www.baidu.com"><span class="screen-reader-text">百度</span></a>
		</li>
		<li class="menu-item">
			<a title="关注我们的twitter" target="_blank" rel="nofollow" href="http://twitter.com"><span class="screen-reader-text">twitter</span></a>
		</li>
		<li class="menu-item">
			<a title="facebook" target="_blank" rel="nofollow" href="http://facebook.com"><span class="screen-reader-text">facebook</span></a>
		</li>
		<li class="menu-item">
			<a title="plus.google" target="_blank" rel="nofollow" href="http://plus.google.com"><span class="screen-reader-text">plus.google</span></a>
		</li>
		<li class="menu-item">
			<a title="pinterest" target="_blank" rel="nofollow" href="http://pinterest.com"><span class="screen-reader-text">pinterest</span></a>
		</li>
		<li class="menu-item">
			<a title="flickr" target="_blank" rel="nofollow" href="http://flickr.com"><span class="screen-reader-text">flickr</span></a>
		</li>
		<li class="menu-item">
			<a title="vimeo" target="_blank" rel="nofollow" href="http://vimeo.com"><span class="screen-reader-text">vimeo</span></a>
		</li>
		<li class="menu-item">
			<a title="youtube" target="_blank" rel="nofollow" href="http://youtube.com"><span class="screen-reader-text">youtube</span></a>
		</li>	
		<li class="menu-item">
			<a title="instagram" target="_blank" rel="nofollow" href="http://instagram.com"><span class="screen-reader-text">instagram</span></a>
		</li>		
		<li class="menu-item">
			<a title="youtube" target="_blank" rel="nofollow" href="http://youtube.com"><span class="screen-reader-text">youtube</span></a>
		</li>		
		<li class="menu-item">
			<a title="wordpress" target="_blank" rel="nofollow" href="http://wordpress.com"><span class="screen-reader-text">wordpress</span></a>
		</li>		
		<li class="menu-item">
			<a title="vk" target="_blank" rel="nofollow" href="http://vk.com"><span class="screen-reader-text">vk</span></a>
		</li>		
		<li class="menu-item">
			<a title="linkedin" target="_blank" rel="nofollow" href="http://linkedin.com"><span class="screen-reader-text">linkedin</span></a>
		</li>			
		
		<li class="menu-item">
			<a title="soundcloud" target="_blank" rel="nofollow" href="http://soundcloud.com"><span class="screen-reader-text">soundcloud</span></a>
		</li>			
		
		<li class="menu-item">
			<a title="tripadvisor" target="_blank" rel="nofollow" href="http://tripadvisor.com"><span class="screen-reader-text">tripadvisor</span></a>
		</li>			
		
		<li class="menu-item">
			<a title="yelp" target="_blank" rel="nofollow" href="http://yelp.com"><span class="screen-reader-text">yelp</span></a>
		</li>						
		<li class="menu-item">
			<a title="订阅我们" target="_blank" rel="nofollow" href="http://www.wordpressleaf.com/feed"><span class="screen-reader-text">订阅我们</span></a>
		</li>
		<li class="menu-item">
			<a title="给我们写信" target="_blank" rel="nofollow" href="mailto:admin@wordpressleaf.com"><span class="screen-reader-text">给我写信</span></a>
		</li>
	</ul>
</div>
<!-- 按钮代码结束 -->
```
- 这些 `<li>` 代码，你可以在 index.html 示例中找到。


3) 在你的网页上加上javascript文件，它们都在js的文件内。另外微信二维码使用了js来加载，所以你也需要加载csfub.js。

```html


  <script src="js/csfub.js"></script>
```


4) 在csfub.js中将图片地址改自己的图片地址。

```html


   var imgurl='img/weixin.png';
```






要注意的是国内社交关注按钮（ChinaSocialFollowUsButtons）支持的字体图标font-awesome。


## Other install options:

Service     | Link
:---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
官网 *      | [**官网**](http://www.wordpressleaf.com/)
github *    | [**github**](https://github.com/yehaicao/ChinaSocialFollowUsButtons)



## 支持
国内社交关注按钮（ChinaSocialFollowUsButtons）支持的字体图标font-awesome。



## 关于
国内社交关注按钮（ChinaSocialFollowUsButtons）为 [**WordPress Leaf**](http://www.wordpressleaf.com/)  荣誉出品。