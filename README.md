# *非特殊情况不再更新*
***
考虑到css写得乱糟糟，可维护性不高，暂时就把这个主题放一放了  
清明节了，跟这个主题说拜拜吧  
很多人也说过展示方式的问题了   
下一次就重新开始写  
在此之前非特殊情况不会更新  

# dame

一款hexo主题，plain是白红配色，主分支是红色主题  
其实颜色都可以自己改的，我在css里放一起了  
使用Materialize框架，移动端看上去要比桌面端看上去好得多    
demo 的话请看[我的博客](http://gaoryrt.github.io)  

## Install

Execute the following command and modify `theme` in `_config.yml` to `dame`.

```
git clone https://github.com/gaoryrt/dame.git themes/dame
```

## Update

Execute the following command to update Dame.

```
cd themes/dame
git pull
```

## costumize

Remember to change the data in `hexo/themes/dame/_config.yml`

### 关于主题颜色 theme color  

全部放在 `source/css/style.css` 的最后，自己改就方便多了  

You can change the theme color easily by modifing the code at the end of `source/css/style.min.css`.  


### _config.yml的配置说明

```
menu:
  主页: 主页的相对位置，一般是 /
  归档: 归档的相对位置，一般是 /archives

more:    这里的内容和连接会出现在「更多」nav 菜单中
  Github: 
  微博: 
  知乎: 
  rss: /rss2.xml 请不要改
  关于我:  

parallax_pic_1: 这个只有主分支主题可用，视差效果的图片
parallax_pic_2: 同上，这一副是下面的图片

google-site-verification: 谷歌站长分析的token
logo: 左上角logo的文字，建议不超过五个字母
```

## changeLog
**2016-01-30 18:20:18**  
把 js 文件放在`</body>`之前了，听说这样规范一点  

**2016-02-19 12:37:12**  
添加了多说评论，很丑，研究了一下他这个貌似是用js加载出来的各种`ds-xxx`标签  
我还不好改，本来想尝试吧`embed.js`拉到本地，发现更坑，css还是多说内部的  
以后还是直接添加`ds-xxx`的本地css算了  

**2016-02-21 13:48:15**  
现在多说样式也和这个主题符合了！

**2016-02-23 20:48:49**  
改了一下手机端的多说样式，宽了不少，好多了。

**2016-03-22 19:59:21**  
把能用的js都换到了cdn处，所有图片也大幅缩小了，放在了cdn处  
就是为了访问速度优化

**2016-03-29 22:16:54**  
字体改的容易识别了，<code>左右过窄解决了   
去掉了一些不必要的js、css加载项  
加上点点细节优化

**2016-03-31 01:49:13**   
基本上都集中到了theme的config文件中设置了  
layout文件夹里仍有一些东西需要提炼出来   
