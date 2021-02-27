# hexo-moments-js
通过js加载的轻量化朋友圈网页模板

# 爬虫配置教程
https://zfe.space/post/friend-link-circle.html

# 页面部署方式
修改api地址，
在需要加载的页面添加moments.js，
在需要加载的页面添加id为moments_container的div即可。

# js中的配置项
```
let requests_url = 'https://hexo-circle-of-friends-api.vercel.app/api'; //api地址
let maxnumber = 20; //页面展示文章数量
let addnumber = 10; //每次加载增加的篇数
let opentype = '_blank';  //'_blank'打开新标签,'_self'本窗口打开
```
