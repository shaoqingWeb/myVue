
* A Vue2.0.js project

* Miss==>>各站点数据整合；图片，视频，文章；在线云音乐播放器；

# 介绍
* 自己做的vue项目，组件化应用、数据交互等。（PS:欢迎Star）
# 实现功能
### 阅读
1.  读1区
2.  读2区
3.  读3区

### 音乐
1.  私人FM
2.  热歌榜
3.  每日推荐
4.  排行榜
5.  推荐歌单
6.  搜索
7.  播放,歌词
8.  单曲循环
9.  随机播放
10.  列表循环
11. 上一首,下一首,快进
12. 加入，删除播放列表
13. 下载 None
14. 登录 None
15. 我喜欢的音乐 None
16. MV None 
### 视频 None
### 图片 None

# Demo
* <a target="_blank" href="http://139.196.32.78:8088/#/home/music">在线Demo</a>

* <a target="_blank" href="https://github.com/shaoqingWeb/myVue">https://github.com/shaoqingWeb/myVue</a>




# 技术栈
* Vue+Vuex+webpack+vueRouter+axios

# Server
* missAdmin==>>负责Api服务. ### 技术栈:mongodb,mongoose,koa2
* missRept==>>负责各网站的数据采集. ### 技术栈:mongodb,mongoose,koa1
* missCloudMusic==>>负责提供音乐数组Api(网易云) ### 技术栈:express

# 部署
* Pm2 , Nginx

# 心得
* 通过Miss更加熟练了Vue,Vuex；这让我感到欣慰。当然，在次过程中也遇到了很多诸多问题,比如说数据采集时会有反盗链机制；还有Vue的一些坑，Vue当时全局注册了一个第三方的内库，但是由于后来没有用，所以就删除了导入代码，而忘了删除注册代码；下面的事情就很尴尬了，用浏览器访问的时候完全没问题，可用手机访问就出不来了(页面)；好像是页面没有加载到似的（关键问题在于没有任何的error），后来尝试了各种，包括了重新建项目再来试；这个坑爬了很久（浪费时间）。所以童鞋们写代码的时候一定要细心啊！！！啊啊啊

# 致谢
* 感谢<a target="_blank" href="https://github.com/Binaryify">Binaryify</a>提供网易云Api;Github==>><a target="_blank" href="https://github.com/Binaryify/NeteaseCloudMusicApi">NeteaseCloudMusicApi</a>




## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8088
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


