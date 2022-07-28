# 记录前端学习
## 一、html
### 1、认识html结构
<details>
<summary>html结构示例</summary>

```html
<!DOCTYPE html>
<!-- 文档声明头，声明文档类型为html -->
<html lang="en">
<!-- 指定页面语言类型，en为英语，zh-CN为中文 -->

<head>
    <meta charset="UTF-8">
    <!-- 字符集(Character set)是多个字符的集合。 -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- X-UA-Compatible是针对IE8新加的一个设置，Edge 模式通知 Windows Internet Explorer 以最高级别的可用模式显示内容 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 视口 viewport，width=device-width ：表示视口宽度等于屏幕宽度。initial-scale=1.0：表示初始的缩放比例 -->
    <title>hulkyin</title>
    <!-- 指定整个网页的标题，在浏览器最上方显示，title标签也是有助于SEO搜索引擎优化的。 -->
    <base href="#">
    <!-- 为页面上的所有链接规定默认地址或默认目标 -->
    <meta name="Keywords" content="网易,邮箱,游戏,新闻,体育,娱乐,女性,亚运,论坛,短信" />
    <!-- 这些关键词，就是告诉搜索引擎，这个网页是干嘛的，能够提高搜索命中率。让别人能够找到你，搜索到你。 -->
    <meta name="Description" content="网易是中国领先的互联网技术公司，为用户提供免费邮箱、游戏、搜索引擎服务，开设新闻、娱乐、体育等30多个内容频道，及博客、视频、论坛等互动交流，网聚人的力量。" />
    <!-- 只要设置Description页面描述，那么百度搜索结果，就能够显示这些语句，这个技术叫做SEO（search engine optimization，搜索引擎优化）。 -->
    <meta http-equiv="refresh" content="300;http://www.baidu.com">
    <!-- 上面这个标签的意思是说，3秒之后，自动跳转到百度页面。 -->
</head>

<body link="red" alink="blue" vlink="green">
    <!-- link属性表示默认显示的颜色、alink属性表示鼠标点击但是还没有松开时的颜色、vlink属性表示点击完成之后显示的颜色 -->
    <h1><a href="#">hello</a> </h1>
    <br> hhh
</body>

</html>
```
</details>
