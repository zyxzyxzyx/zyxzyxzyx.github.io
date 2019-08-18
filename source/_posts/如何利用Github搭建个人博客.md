---
title: 如何利用Github搭建个人博客
tags: [Github]
categories: Github
copyright: true
password: password
top: 100
---

# ****** 特别推荐 ******
# Ⅰ: 搭建指南：
## 1. [Hexo 博客搭建指南](https://github.com/limedroid/HexoLearning)
## 2. [【Hexo搭建独立博客全纪录】（三）使用Hexo搭建博客](https://baoyuzhang.github.io/2017/05/12/%E3%80%90Hexo%E6%90%AD%E5%BB%BA%E7%8B%AC%E7%AB%8B%E5%8D%9A%E5%AE%A2%E5%85%A8%E7%BA%AA%E5%BD%95%E3%80%91%EF%BC%88%E4%B8%89%EF%BC%89%E4%BD%BF%E7%94%A8Hexo%E6%90%AD%E5%BB%BA%E5%8D%9A%E5%AE%A2/)
# Ⅱ: 添加评论功能：
## 3. [hexo - Next 主题添加评论功能](https://yashuning.github.io/2018/06/29/hexo-Next-%E4%B8%BB%E9%A2%98%E6%B7%BB%E5%8A%A0%E8%AF%84%E8%AE%BA%E5%8A%9F%E8%83%BD/)
## 4. [Next主题增加Gitment评论系统](https://aoenian.github.io/2019/04/14/next-theme-gitment/)
## 5. [添加Gitment评论系统踩过的坑](http://xichen.pub/2018/01/31/2018-01-31-gitment/)
## 6. [Gitment评论功能接入踩坑教程](https://www.jianshu.com/p/57afa4844aaa)
# Ⅲ: 主题优化：
## 7. [hexo的next主题个性化教程:打造炫酷网站](http://shenzekun.cn/hexo%E7%9A%84next%E4%B8%BB%E9%A2%98%E4%B8%AA%E6%80%A7%E5%8C%96%E9%85%8D%E7%BD%AE%E6%95%99%E7%A8%8B.html)
# Ⅳ: 博客源备份：
## 8. [GitHub + Hexo搭建自己博客(三) 多设备管理](https://sandop.github.io/2019/02/21/GitHub-Hexo%E6%90%AD%E5%BB%BA%E8%87%AA%E5%B7%B1%E5%8D%9A%E5%AE%A2-%E4%B8%89-%E5%A4%9A%E8%AE%BE%E5%A4%87%E7%AE%A1%E7%90%86/)
<br>

# ****** 正文 ******
# 一、基础搭建
## 1. 注意事项:
**每次新增或更新博客时，要注意执行以下命令:**
```bash
$ hexo clean	//清除缓存文件db.json和已生成的静态文件public
$ hexo g	//生成网站静态文件到默认设置的public文件夹
$ hexo d	//部署网站到设定的仓库
```
**或把后两条命令合二为一:**

```bash
$ hexo clean	//清除缓存文件db.json和已生成的静态文件public
$ hexo d -g		//生成并上传
```
1. [Hexo博客搭建全攻略](https://github.com/limedroid/HexoLearning)
2. [【Hexo搭建独立博客全纪录】（三）使用Hexo搭建博客](https://baoyuzhang.github.io/2017/05/12/%E3%80%90Hexo%E6%90%AD%E5%BB%BA%E7%8B%AC%E7%AB%8B%E5%8D%9A%E5%AE%A2%E5%85%A8%E7%BA%AA%E5%BD%95%E3%80%91%EF%BC%88%E4%B8%89%EF%BC%89%E4%BD%BF%E7%94%A8Hexo%E6%90%AD%E5%BB%BA%E5%8D%9A%E5%AE%A2/)
3. [Hexo(2)-部署博客及更新博文](https://zhuanlan.zhihu.com/p/22498474)
4. [Hexo博客的搭建及同步更新](http://mrljdx.com/2015/02/09/Hexo%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E5%8F%8A%E5%90%8C%E6%AD%A5%E6%9B%B4%E6%96%B0/)
5. [如何快速搭建自己的github.io博客](https://keysaim.github.io/post/blog/2017-08-15-how-to-setup-your-github-io-blog/)
6. [持续更新】最全Hexo博客搭建+主题优化+插件配置+常用操作+错误分析](https://www.simon96.online/2018/10/12/hexo-tutorial/)
7. [免费个人博客搭建详解](https://www.jianshu.com/p/380290deb8f0)

## 2. 搭建过程中遇到的问题:
1. [解决用Hexo和GitHub搭建博客时hexo d命令报错问题](https://blog.csdn.net/Greenovia/article/details/60576985) 
2. [将本地 Hexo 仓库部署到 GitHub 上](https://blog.csdn.net/m0_38064214/article/details/84504904)
3. [V.GitHub + Hexo (2)：部署博客及更新博文](https://zhuanlan.zhihu.com/p/22632478)

## 3. 博客模板推荐:
1. [使用hexo+github搭建免费个人博客详细教程](http://blog.haoji.me/build-blog-website-by-hexo-github.html?from=xa)
2. [博客搭建详细教程](https://github.com/qiubaiying/qiubaiying.github.io/wiki/%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E6%95%99%E7%A8%8B)
3. [Github搭建个人博客（2019最新版,亲测）](https://blog.csdn.net/xudailong_blog/article/details/78762262)
4. [jekyll框架](https://github.com/jekyll/jekyll)
5. [hexo框架](https://github.com/hexojs/hexo)
6. [hexo-theme-next——Elegant theme for Hexo.](https://github.com/iissnan/hexo-theme-next)
7. [hexo-theme-yilia——一个简洁优雅的hexo主题](https://github.com/litten/hexo-theme-yilia)
8. [hexo-theme-matery——一个Hexo主题](https://github.com/blinkfox/hexo-theme-matery)
9. [模板博客](https://zhousiwei.gitee.io/)

## 4. 大神博客推荐:
1. [韦阳的博客](https://godweiyang.com/) 
2. [超详细Hexo+Github博客搭建小白教程——韦阳博客](https://godweiyang.com/2018/04/13/hexo-blog/)
3. [超详细Hexo+Github博客搭建小白教程——知乎](https://zhuanlan.zhihu.com/p/35668237)

# 二、Gitment：使用 GitHub Issues 搭建评论系统
1. [Gitment：使用 GitHub Issues 搭建评论系统](https://imsun.net/posts/gitment-introduction/)
2. [使用hexo搭建github博客](https://www.xncoding.com/2016/03/06/hexo.html)
3. [hexo - Next 主题添加评论功能](https://yashuning.github.io/2018/06/29/hexo-Next-%E4%B8%BB%E9%A2%98%E6%B7%BB%E5%8A%A0%E8%AF%84%E8%AE%BA%E5%8A%9F%E8%83%BD/)
4. [gitment——Github官网](https://github.com/imsun/gitment)

# 三、搭建评论系统时遇到的问题汇总
## 1. 添加评论时出现"[object ProgressEvent] "问题:
**object ProgressEvent问题解决:
找到next主题中的gitment评论文件 next/layout/_third-party/comments/gitment.swig，更改以下代码:**

```js
<!-- 原代码 -->
// gitment的英文版
<link rel="stylesheet" href="https://imsun.github.io/gitment/style/default.css">
<script src="https://imsun.github.io/gitment/dist/gitment.browser.js"></script>

// gitment的汉化版
// 只需到模板里将原来定义CSS和JS的那两行改成：
<!-- 请使用下面的替换  2019-06-30更新-->
<link rel="stylesheet" href="https://billts.site/extra_css/gitment.css">
<script src="https://billts.site/js/gitment.js"></script>
```
完整代码如下：

```js
<!-- LOCAL: You can save these files to your site and update links -->
    {% if theme.gitment.mint %}
        {% set CommentsClass = "Gitmint" %}
        <link rel="stylesheet" href="https://aimingoo.github.io/gitmint/style/default.css">
        <script src="https://aimingoo.github.io/gitmint/dist/gitmint.browser.js"></script>
    {% else %}
        {% set CommentsClass = "Gitment" %}
        <link rel="stylesheet" href="https://billts.site/extra_css/gitment.css">
        <script src="https://billts.site/js/gitment.js"></script>
    {% endif %}
<!-- END LOCAL -->
```

重新清理缓存，部署博客即可留言。
1. [Next主题增加Gitment评论系统](https://aoenian.github.io/2019/04/14/next-theme-gitment/)
2. [[object ProgressEvent] #170](https://github.com/imsun/gitment/issues/170)
3. [gitment评论模块接入hexo | 我的博客 #8](https://github.com/jjeejj/jjeejj.github.io/issues/8)
4. [hexo博客配置-添加评论系统-gitment和valine-需注册](https://xiaotiandi.github.io/publicBlog/2018-09-19-d196c9ad.html)
5. [gitment评论模块接入hexo](https://www.wenjunjiang.win/2017/07/02/gitment%E8%AF%84%E8%AE%BA%E6%A8%A1%E5%9D%97%E6%8E%A5%E5%85%A5hexo/)
6. [hexo博客的gitment评论开启一直失败 #178](https://github.com/imsun/gitment/issues/178)
7. [GitHub Pages个人博客搭建流程](https://adamhu.github.io/2019/06/GitHub-Pages%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2%E6%90%AD%E5%BB%BA%E6%B5%81%E7%A8%8B/)
## 2. 使用Gitment遇到的问题: Error：validation failed
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190814094325187.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3p5eF9seQ==,size_16,color_FFFFFF,t_70)

```js
// 原配置
id: '<%= page.title %>'
// 修改后的配置
id: '<%= page.date %>'
```

1. [Gitment评论功能接入踩坑教程](https://www.jianshu.com/p/57afa4844aaa)
2. [添加Gitment评论系统踩过的坑](http://xichen.pub/2018/01/31/2018-01-31-gitment/)
3. [使用Gitment遇到的问题: Error：validation failed](https://www.jianshu.com/p/32f115811254)
4. [Hexo+gitment的Error：validation failed](https://www.jianshu.com/p/d873394f12ce)
5. [gitalk Error: Validation Failed](https://blog.csdn.net/death05/article/details/83618887)
6. [Hexo添加gitalk评论插件及 Error: Validation Failed 报错解决](https://blog.csdn.net/lzw2016/article/details/83244906)
7. [处理Gitalk中由于文章URL过长导致的Validation Failed(422)](https://priesttomb.github.io/%E6%97%A5%E5%B8%B8/2018/02/12/%E5%A4%84%E7%90%86Gitalk%E4%B8%AD%E7%94%B1%E4%BA%8E%E6%96%87%E7%AB%A0URL%E8%BF%87%E9%95%BF%E5%AF%BC%E8%87%B4%E7%9A%84Validation-Failed%28422%29/)
8. [所有文章一键初始化评论 #5](https://github.com/imsun/gitment/issues/5)
9. [JavaScript-MD5](https://github.com/blueimp/JavaScript-MD5)
10. [issue的Label有长度限制！把id留空可能导致 Error: Validation Failed #112](https://github.com/imsun/gitment/issues/112) 
11. [Error: Validation Failed #118](https://github.com/imsun/gitment/issues/118)
12. [报错出现 Error: Validation Failed. #102](https://github.com/gitalk/gitalk/issues/102)

# 四、Hexo的Next主题详细配置
## 1. 整体配置：
1. [hexo的next主题个性化教程:打造炫酷网站](http://shenzekun.cn/hexo%E7%9A%84next%E4%B8%BB%E9%A2%98%E4%B8%AA%E6%80%A7%E5%8C%96%E9%85%8D%E7%BD%AE%E6%95%99%E7%A8%8B.html)
2. [hexo的next主题个性化配置教程](https://segmentfault.com/a/1190000009544924)
3. [超详细Hexo+Github博客搭建小白教程](https://godweiyang.com/2018/04/13/hexo-blog/)
4. [Hexo的Next主题详细配置](https://www.jianshu.com/p/3a05351a37dc)
5. [开始使用](https://theme-next.iissnan.com/getting-started.html)
6. [主题配置](http://theme-next.iissnan.com/theme-settings.html)
7. [hexo+next 部署各种炫酷博客特效](https://jiyali.github.io/2019/04/15/hexo-next-%E9%83%A8%E7%BD%B2%E5%90%84%E7%A7%8D%E7%82%AB%E9%85%B7%E5%8D%9A%E5%AE%A2%E7%89%B9%E6%95%88/)
8. [2018 - Hexo - Next - Mist 风格主题的美化（二）](https://blog.csdn.net/hack_different/article/details/83904505)
9. [你见过的最棒的个人博客界面是什么样的？](https://www.zhihu.com/question/29755481)
10. [【12】2小时还你一个集打赏、评论、RSS功能于一身的个人博客](https://www.jianshu.com/p/5973c05d7100)
11. [Hexo+Next主题优化](https://zhuanlan.zhihu.com/p/30836436)
12. [HEXO+NEXT主题个性化配置](http://mashirosorata.vicp.io/HEXO-NEXT%E4%B8%BB%E9%A2%98%E4%B8%AA%E6%80%A7%E5%8C%96%E9%85%8D%E7%BD%AE.html)
13. [对NexT主题风格的修改](https://kabeor.cn/%E5%AF%B9NexT%E4%B8%BB%E9%A2%98%E9%A3%8E%E6%A0%BC%E7%9A%84%E4%BF%AE%E6%94%B9/index.html) 
14. [Hexo-NexT配置超炫网页效果](https://www.jianshu.com/p/9f0e90cc32c2)
15. [hexo指南](https://hexo-guide.readthedocs.io/zh_CN/latest/)
16. [使用next主题配置博客基本信息](https://juejin.im/post/5a9d0ceaf265da237b2193b7)
17. [NexT的主题设定与配置](https://blog.csdn.net/shengshengshiwo/article/details/79350413)
18. [Github+Hexo一站式部署个人博客 (原创)](https://zhuanlan.zhihu.com/p/71164003)
19. [使用Hexo+Github一步步搭建属于自己的博客（进阶）](https://www.cnblogs.com/fengxiongZz/p/7707568.html)
20. [hexo next主题优化，打造个人精致网站](http://eternalzttz.com/hexo-next.html)
21. [hexo的next主题个性化配置](https://zhuanlan.zhihu.com/p/60424755)
22. [Hexo+Next个人博客主题优化](https://www.jianshu.com/p/efbeddc5eb19)
23. [GitHub + Hexo搭建自己博客(二) Next主题配置](https://juejin.im/post/5c6d20b151882562934c9962)
## 2. 局部配置：
1. [Hexo博客NexT主题美化之顶部加载进度条](https://blog.pangao.vip/Hexo%E5%8D%9A%E5%AE%A2NexT%E4%B8%BB%E9%A2%98%E7%BE%8E%E5%8C%96%E4%B9%8B%E9%A1%B6%E9%83%A8%E5%8A%A0%E8%BD%BD%E8%BF%9B%E5%BA%A6%E6%9D%A1/)
2. [Hexo Next 添加萌萌的宠物live2d](https://vonsdite.cn/posts/fbd1f97f.html)
3. [Hexo博客添加在线联系功能](https://www.ezlippi.com/blog/2018/01/next-chat.html)
4. [hexo next 配置 DaoVoice 实现在线聊天功能](https://hoxis.github.io/hexo-next-daovoice.html)
5. [DaoVoice控制台](http://dashboard.daovoice.io/app/7d574495/users?segment=all-users)
6. [设置文章打赏](https://github.com/ahonn/hexo-theme-even/wiki/%E8%AE%BE%E7%BD%AE%E6%96%87%E7%AB%A0%E6%89%93%E8%B5%8F)
7. [Hexo NexT主题添加点击爱心效果](https://asdfv1929.github.io/2018/01/26/click-love/)
8. [Hexo之在右上角或者左上角实现fork me on github](https://www.simon96.online/2018/11/16/hexo-do-forkMe/)
9. [Hexo + Next 的优化](https://simguo.github.io/2017/08/01/Hexo-Next-%E7%9A%84%E4%BC%98%E5%8C%96/)

# 五、GitHub + Hexo搭建自己博客：备份博客源文件
1. [GitHub + Hexo搭建自己博客(三) 多设备管理](https://sandop.github.io/2019/02/21/GitHub-Hexo%E6%90%AD%E5%BB%BA%E8%87%AA%E5%B7%B1%E5%8D%9A%E5%AE%A2-%E4%B8%89-%E5%A4%9A%E8%AE%BE%E5%A4%87%E7%AE%A1%E7%90%86/)
2. [超详细Hexo+Github博客搭建小白教程](https://godweiyang.com/2018/04/13/hexo-blog/)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190817175408575.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3p5eF9seQ==,size_16,color_FFFFFF,t_70)
