# 完善这个WebApp需要学习

## Python Web框架
+ django
+ webpy
+ flask
+ tornado
+ pylons
+ quixote
+ bottle
+ repoze.bfg
+ pyramid
+ wsgi

## Python Web前端框架 
+ jinja2
+ mako

## Python 数据库中间件
+ sqlalchemy   

## Python 数据库
+ mongodb
+ mysql


## [Jinja](http://jinja.pocoo.org/docs/dev/api/)
    Jinja2是个Web页面模板框架, powered by Pocc(Flask, Jinja 2, Pygments, Sphinx, and Werkzeug): http://www.pocoo.org/

## [aiohttp]()

## [Flask](http://flask.pocoo.org/)
    Flask是基于Werkzeug, Jinja2的 Python微框架 

   + [欢迎来到 Flask 的世界](http://dormousehole.readthedocs.org/en/latest/)
   + [Python和Flask真是太强大了](http://python.jobbole.com/81065/)
   + [选择一个 Python Web 框架：Django vs Flask vs Pyramid](http://www.oschina.net/translate/django-flask-pyramid)
   + [回归简单，向Django说再见](http://www.vimer.cn/2011/11/%E5%9B%9E%E5%BD%92%E7%AE%80%E5%8D%95%EF%BC%8C%E5%90%91django%E8%AF%B4%E5%86%8D%E8%A7%81.html)
   + [拿Python搞web的, 有不用Django的吗?](http://www.douban.com/group/topic/9727762/)
   + [flask的优点是什么？](http://python-china.org/t/93)
   + [Python China](http://python-china.org/)
   + [Flask+SAE快速打造微信公众帐号（有码）](http://blog.csdn.net/linhan8/article/details/8746110)

## [W3School](http://www.w3school.com.cn/sql/sql_update.asp)
    W3School是网页编程的学习网站，涉及HTML, CSS, JavaScript, SQL, XML等 内容

## [廖雪峰的官方网站](http://www.liaoxuefeng.com/)
    学习网站编程的好去处, GitHub地址为: https://github.com/michaelliao  

##  [Python官网](https://docs.python.org/3.4/library/asyncio.html?highlight=asyncio#module-asyncio)
   + [python模块之HTMLParser](http://www.tuicool.com/articles/jiqYr2)
   + [python:利用asyncio进行快速抓取](http://blog.jobbole.com/63897/)
   + [使用Python下载邮件(pop/imap)](http://www.pythoner.com/414.html)
   + [Python Club](http://www.pythonclub.org/)
   + [Python in JOBBOLE](http://blog.jobbole.com/category/python/)
   + [写给已有编程经验的 Python 初学者的总结](http://blog.jobbole.com/79197/)
   + [如何入门 Python 爬虫？](http://www.zhihu.com/question/20899988/answer/24923424)
   + [Python爬虫框架Scrapy实战之定向批量获取职位招聘信息](http://blog.csdn.net/HanTangSongMing/article/details/24454453)
   + [零基础自学用Python 3开发网络爬虫](http://jecvay.com/category/smtech/python3-webbug)
   + [Python初学者资料](https://github.com/Yixiaohan/codeparkshare/blob/master/README.md)
   + [你是如何开始能写python爬虫？](http://www.zhihu.com/question/21358581)
   + [开源一个 python 脚本驱动的定向爬虫](http://v2ex.com/t/103525)
   + [标准爬虫初探，来自Python之父的大餐！](http://developer.51cto.com/art/201411/456836.htm):[500lines](https://github.com/aosabook/500lines)
   + [15个最受欢迎的Python开源框架](http://blog.jobbole.com/72306/)
   + [Python web 框架 django, web.py, Tornado, Flask, Quixote比较,区别和优缺点](http://www.360doc.com/content/14/1231/23/13232598_437241318.shtml)
   + [选择一个 Python Web 框架：Django vs Flask vs Pyramid](http://www.oschina.net/translate/django-flask-pyramid)
   + [浅谈Python web框架](http://feilong.me/2011/01/talk-about-python-web-framework)


## [What is a metaclass in Python?](http://stackoverflow.com/questions/100003/what-is-a-metaclass-in-python)
    ATT

## [Welcome to aiomysql’s documentation!](http://aiomysql.readthedocs.org/en/latest/)
    ATT

## 讨论
Flask代表micro（此类还有bottle和web.py）。Django代表full-stack。Tornado代表asynchronous 。可以这样认为吗？
是否可以这样说：这3个框架基本可以代表Python Web开发的主要模式？

我觉得这些框架只有功能多寡的不同，没有模式的不同 binux@v2ex
+ 从0考虑一个web框架可能有什么： 
    - TCPServer 
    - request，response封装 
    - 路由 
    - 接口转换 
    - 模板 
    - 工具集 
    - 数据库接口 
    - 各种转换 
    - 各种生成器 


Django 就像 IDE 给你的插件（admin,orm,route 等）没法换，但是 Flask 像 Editor 有很多供选择的 batteries。 
以及，Flask 这货在 app 大之后，需要开发者自己有一定的经验和构架的能力才可以很好的控制各种模式：(humiaozu@v2ex)

### app framework 

- app factory 
- blueprint 
- api/template error handling 
- development/testing/staging/production server configurations 
- db logic 
- db logic error handing 
- controller 
- delayed jobs 
- json serialization/template rendering 

### management 

- database miggration 
- app manage commands 

### testing 

- moking/testing 
- profiling(performance testing) 
- security testing 

### deployment/operation/monitor 

- deployment automation 
- manage automation 
- app exception monitor 
- app/db performance monitor
