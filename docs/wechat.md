# 关于微信公众号运营

## 目标

推进 Go 在国内的发展，将 GCTT 翻译的文章让更多人看到，同时增强 Go 中文网的知名度。

## 发布内容

公众号：Go 语言中文网 是一个订阅号，每天可以发布一篇消息。主要发布 GCTT 的译文，目前从 https://studygolang.com/subject/1 和 https://studygolang.com/subject/2 （这是一个教程系列） 获取文章，发布顺序按照从旧到新，避免发重复。后续看情况可以一次发多篇图文。

因为涉及到排版问题，而 GCTT 的原始译文都是 Markdown 格式，所以，推荐大家使用 Markdown-here 浏览器插件（参考：https://www.jianshu.com/p/4bbe8b439dad 和 https://www.jianshu.com/p/e766a7ea063a）。

说一下我的发布流程：

1. 确定这次需要发布的文章：查看上次发布的是哪篇，然后确定这次应该发布哪篇（可以选择 subject/1 或 subject/2 中的）；
2. 因为 studygolang.com 上面看到的是解析为 html 了的，为了方便处理，在 https://github.com/studygolang/GCTT/tree/master/published/tech 中找到原始 markdown 格式文章。（这块我考虑下怎么更方便的找到原始 markdown 文章）；
3. 微信中，标题以『GCTT 出品』开始（当然得是 GCTT 的文章），接上网站上发布时的文章标题，比如：『GCTT 出品』测试 Go 语言 Web 应用；
4. 复制原始 markdown 文章，粘贴到微信编辑框中。将正文最开始的标题去掉。然后安装 markdown-here 的要求转换；
5. 转换为 HTML 后，自己 review 一遍，代码可能需要加一些换行；如果文章有图片，图片需要重新上传；
6. 文章最后勾上 ”原始链接“，把在 studygolang.com 上文章对应的链接放上（可以一定程度为主站导流）；
7. 点击原创声明（对于 GCTT 译文，都可以加上原创声明），作者中写上：译者xxx；文章类别选择：科技互联网；
8. 设置封面：文章有图片，可以选择文中的图片做封面，没有的话，可以从图库中选择一张；
9. 复制文章开始的一些文本当做摘要；
10. 按照 https://mp.weixin.qq.com/s/bLpse9pVkj-Qa8Pqhej1kg 样子，在正文头尾加上关注公众号的文字和图片；
11. 保存，可以预览看看。没问题，保存并群发。

## 发布时间

时间一般在早上 8 点 到 10 点。

## 发布完后

可以转发朋友圈、微信群、qq 群，做推广。