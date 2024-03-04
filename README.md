# Xman
Xman is a fresh looking and responsive theme for [Hexo](http://hexo.io) with more features and some build-in Chinese service based on [Jacman](https://github.com/wuchong/jacman).  


## Xman Changes compared to Jacman
**Xman support Hexo 4.0+**
[Use Case](http://xinghua.space)

**Visual elements simplified**
* Abandoned some early material design design elements, such as excessive shadows
* Streamline the underline decoration of each module and use more white space for visual division

**Adjustments to some technical solutions based on the development of W3C and browsers in recent years**
* Replace float layout with Grid and Flex layout (doing)
* Gradually remove jQuery dependencies (todo)
* Remove terminated third-party services
  * Google+
  * duoshuo comment
  * netease gentie
  * jiathis share


## Installation
### Install
```bash
git clone https://github.com/starding/hexo-theme-xman.git themes/xman
```
**Xman requires Hexo 2.7 and above.** 
### Enable
Modify `theme` setting in blog folder` _config.yml` to `xman`.
### Update
```bash
cd themes/xman
git pull origin master
```
**please backup your `_config.yml` file before update.** 

## Configuration

Modify settings in  `/themes/xman/_config.yml`.

## Features
- **menu**  
 Main navigation menu.
- **widget**  
 Widgets displaying in sidebar.The category,tag,rss,archive,tagcloud,links,weibo are supported.
- **Image**  
 Images about favicon, site logo, author image. 
 Support different image styles like `img-logo`,`img-topic`,`img-center` etc.
- **author**  
 Author imformation, used to show your social network links on the bottom right. 
 Including github, stackoverflow, twitter, facebook, linkedin, weibo, douban, zhihu, email.
- **toc**  
 Show Table Of Contents in article & aside.
- **comments**  
 [giscus](https://giscus.app/) & [disqus](https://disqus.com/) & [畅言](http://changyan.kuaizhan.com/) are supported.
- **share**  
 Build-in share tool at the bottom of articles.
- **Analytiscs**  
 [Google analytics](http://www.google.com/analytics/) & [Baidu tongji](http://tongji.baidu.com/) & [CNZZ tongji](http://www.cnzz.com/) are all supported.
- **Search**  
 [Googlle Custom Search](https://www.google.com/cse/ ) & [Baidu Site Search](http://zn.baidu.com/) & [Tiny Search](http://tinysou.com/) are supported.
- **totop**  
 Scroll to top
- **rss**  
 RSS subscription link (change if using Feedburner).
- **fancybox**  
 Enable [Fancybox](http://fancyapps.com/fancybox/)
- **custom theme color**
 Mondify theme color in `_config.yaml` instead of finding unfamiliar stylus files.
- **others**
 You can configure sidebar not show in post pages.


## License
[MIT](/LICENSE)
