# dame

由 [mame](https://github.com/chadluo/hexo-theme-mame) 修改而来的一款 hexo 主题。  
demo 的话请看[我的博客](http://gaoryrt.github.io)效果。

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

## 关于主题颜色 theme color  

全部放在 `source/css/style.css` 的最后，自己改就方便多了  

You can change the theme color easily by modifing the code at the end of `source/css/style.min.css`.  

## 暂时存在的问题 
  
首页还是丑  

## log
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