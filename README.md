# TKL
TKL is a responsive design theme for Hexo.
[Demo| Kieran's Blog](http://go.kieran.top/post/14/)
### Install
Execute the following command and modify theme in <code>_config.yml</code> to <code>TKL</code>.
```
git clone https://github.com/SuperKieran/TKL.git
```
<!--more-->
### Update
Execute the following command to update TKL.
``` 
cd themes/TKL
git pull
```
### Config
#### Theme_config.yml
```
cover: /img/bg_img.jpg
logo: /img/logo.png
top_saying:
- title: YOU'VE MADE A <span>BRAVE</span> DECISION, WELCOME.
- content: 每一个不曾起舞的日子都是对生命的辜负。
bottom_saying: 虽然还没想好写点什么，但是总觉得这里放句话比较和谐。
  
excerpt_link: Read More
  
rss: /atom.xml
  
highlightjs: vs

works:
- works_name: XXX1
  works_url: /
- works_name: XXX2
  works_url: /
  
duoshuo: duoshuo_name
  
github: https://github.com/
twitter: https://twitter.com/
facebook: https://www.facebook.com/
google:  https://google.com/
weibo: http://weibo.com/
  
timeline:
- num: 1
  word: 2014/06/12-Start xxx
- num: 2
  word: 2014/11/29-Start bbb
- num: 3
  word: 2015/02/18-Start ddd
- num: 4
  word: ...
  
links:
- name: Kieran
  link: http://go.kieran.top/
- name: Name
  link: http://domain.com/

# Local search
# Dependencies: https://github.com/flashlab/hexo-generator-search
local_search:
  enable: true
# if auto, trigger search by changing input
# if manual, trigger search by pressing enter key or search button
  trigger: auto
# show top n results per article, show all results by setting to -1
  top_n_per_article: 2
```
#### Hexo_config.yml
change some code to enable archives page
```
# Archives
## 2: Enable pagination
## 1: Disable pagination
## 0: Fully Disable
archive: 1
category: 1
tag: 1
```
Enable Seach
Install hexo plugin at first: [hexo-generator-search-zip](https://github.com/SuperKieran/hexo-generator-search-zip)
```
search:
  path: search.json
  zipPath: search.zip
  versionPath: searchVersion.txt
  field: post
```
### Icon
Seclet icon which you like in<code>\TKL\source\css\iconList.css</code>  
![](http://cdn.kieran.top/hexo_14_1.png)  
![](http://cdn.kieran.top/hexo_14_2.png)
### Screen
Show
![](http://cdn.kieran.top/hexo_14_3.png)
  
Content
![](http://cdn.kieran.top/hexo_14_4.png)
### Others
If you like this theme, [Fork](https://github.com/SuperKieran/TKL/fork) && Star.
Come on.

### Share Your Blog
Write your blog here -> https://github.com/SuperKieran/TKL/issues/54

### Wechat Group
<img src="http://cdn.kieran.top/wechat.jpeg" width="300px" />
如何加入 TKL 微信交流群？ 先加上面机器人为好友，然后发送 “TKL” 关键字，自动邀请进群

### Bug
2018年12月13日： 最新版 hexo 会自动补上闭合标签，如果出现顶部导航栏没有显示的情况，可以安装旧版本解决，安装命令 `npm i hexo@3.7.1 --save`
