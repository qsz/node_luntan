利用react + redux + react-router + webpack，制作的移动端网站(cnode社区)，
====  

##版本号1.0
####效果查看
[网址](https://qsz.github.io/node-luntan) <br>
![扫描二维码](https://github.com/qsz/node-luntan/blob/gh-pages/photo/QQ%E5%9B%BE%E7%89%8720161030223340.png) <br>
####部分效果图
![首页 ](https://github.com/qsz/node-luntan/blob/gh-pages/photo/home.PNG) <br>
![发表主题 ](https://github.com/qsz/node-luntan/blob/gh-pages/photo/createreply.PNG)<br>  
![查看帖子 ](https://github.com/qsz/node-luntan/blob/gh-pages/photo/topic.PNG) <br> 
![查看评论 ](https://github.com/qsz/node-luntan/blob/gh-pages/photo/replylist.PNG) <br> 
![个人资料 ](https://github.com/qsz/node-luntan/blob/gh-pages/photo/user.PNG)<br>  

###下载
git clone https://github.com/qsz/node-luntan<br>
cd node-luntan<br>
npm install <br>

###主要功能
1.主题分类，列表、帖子查看<br>
2.点赞<br>
3.登入退出<br>
4.查看他人、自己的个人资料<br>
###总结
1.项目架构初步形成，发现state树的设计需要优化，最好把每个文章信息都存入state中，这样可以减少网络加载<br>
2.代码写得很不优美，需要在接下来的版本大力优化<br>
3.action、reducer的设计以及对应关系需要进行优化<br>
4.下一个版本增加功能:发表评论、接受消息<br>


#期待2.0
