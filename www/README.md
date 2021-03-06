# Python Web开发相关组件

[Full Stack Python](http://www.fullstackpython.com/introduction.html)
[Learn X in Y minutes](https://learnxinyminutes.com/docs/python3/)
[Python Module of the Week](https://pymotw.com/2/contents.html)
[The Hitchhiker’s Guide to Python!](http://docs.python-guide.org/en/latest/)
[Python 基础教程](http://www.runoob.com/python/python-tutorial.html)

## Python Web框架

+ [wsgi](http://wsgi.readthedocs.org/en/latest/)
    * [Python Web Server Gateway Interface v1.0.1](https://www.python.org/dev/peps/pep-3333/)
    * [来了解一下WSGI这个概念](http://www.nowamagic.net/academy/detail/1330310)
    * [戏说WSGI（Python Web服务网关接口）](http://www.cnblogs.com/holbrook/archive/2012/02/25/2357337.html)

+ [django](https://www.djangoproject.com/)
    * [Django1.7开发博客](http://yidao620c.github.io/blog/20150420/simpleblog-01.html)
    * [Django Girls Tutorial](http://tutorial.djangogirls.org/en/index.html)
    * [The Django Book 2.0--中文版](http://docs.30c.org/djangobook2/)
    * [Django REST framework](http://www.django-rest-framework.org/)
    * [Django FileBrowser Documentation](http://django-filebrowser.readthedocs.org/en/latest/)
    * [Django MSSQL Database Backend](http://django-mssql.readthedocs.org/en/latest/)
    * [使用 Django 和 Python 开发 Web 站点](https://www.ibm.com/developerworks/cn/linux/l-django/)
    * [基于 Django 框架的敏捷 Web 开发](http://www.ibm.com/developerworks/cn/opensource/os-cn-django/)

+ [webpy](http://webpy.org/)
    * [web.py API](http://webpy.readthedocs.org/en/latest/api.html)
    * [web.py 0.3 新手指南](http://justjavac.iteye.com/blog/1490432)
    * [Web.py + Markdown 轻量级博客实践](https://github.com/dylanninin/blog)
    * [Web.py Cookbook 简体中文版](http://justjavac.com/python/2012/04/19/webpy-cookbook.html)

+ [flask](http://flask.pocoo.org/)
    * [欢迎来到 Flask 的世界](http://dormousehole.readthedocs.org/en/latest/)
    * [Python和Flask真是太强大了](http://python.jobbole.com/81065/)
    * [选择一个 Python Web 框架：Django vs Flask vs Pyramid](http://www.oschina.net/translate/django-flask-pyramid)
    * [回归简单，向Django说再见](http://www.tuicool.com/articles/fu22yev)
    * [flask的优点是什么？](http://python-china.org/t/93)
    * [Python China](http://python-china.org/)
    * [Flask+SAE快速打造微信公众帐号（有码）](http://blog.csdn.net/linhan8/article/details/8746110)
    * [Flask Web Development](https://segmentfault.com/blog/young_ipython?page=1)

+ [tornado](http://www.tornadoweb.org/en/stable/)
    * [Tornado Web Server](http://tornado.readthedocs.org/en/latest/index.html)
    * [Tornado Web 服务器框架](http://www.tornadoweb.cn/)
    * [Tornado概览](http://www.tornadoweb.cn/documentation)
    * [Introduction to Tornado](http://demo.pythoner.com/itt2zh/index.html)
    * [Tornado源码分析之http服务器篇](http://kenby.iteye.com/blog/1159621)
    * [Tornado 简单入门教程](http://segmentfault.com/a/1190000002703321)

+ [pylons/pyramid](http://www.pylonsproject.org/)
    * [The Pylons Project](http://docs.pylonsproject.org/en/latest/)
    * [The Pyramid Web Framework](http://docs.pylonsproject.org/projects/pyramid/en/latest/)
    * [repoze.bfg](http://docs.repoze.org/bfg/current/)

+ [quixote](http://quixote.ca/)
    * [Python应用：轻量级Web框架Quixote](http://www.douban.com/note/66842743/)
    * [Quixote入门指南](http://www.open-open.com/doc/view/7c2ed5e6a5f34d6d98e550a2387dd435)

+ [bottle](http://bottlepy.org/docs/dev/index.html)
    * [Python Web 开发框架 Bottle](http://simple-is-better.com/news/59)
    * [Bottle API 参考](http://article.yeeyan.org/view/35282/126927)

+ [TurboGears](http://turbogears.org/)
    * [TurboGears2 CookBook](http://turbogears.readthedocs.org/en/latest/cookbook/cookbook.html)
    * [使用 TurboGears 和 Python 开发 Web 站点](http://www.ibm.com/developerworks/cn/linux/l-turbogears/)
    * [SourceForge使用Python、TurboGears、MongoDB……来重构网站](http://haoluobo.com/tag/turbogears/)

### Python Web框架比较

+ [Python各种WEB框架简介](http://www.open-open.com/lib/view/open1413011357655.html)
+ [浅谈Python web框架](http://feilong.me/2011/01/talk-about-python-web-framework/)
+ [Python web 框架 django, web.py, Tornado, Flask, Quixote比较,区别和优缺点](http://www.360doc.com/content/14/1231/23/13232598_437241318.shtml)
+ [15个最受欢迎的Python开源框架](http://blog.jobbole.com/72306/)
+ [选择一个 Python Web 框架：Django vs Flask vs Pyramid](http://www.oschina.net/translate/django-flask-pyramid)

### Python Web框架讨论

Flask代表micro（此类还有bottle和web.py）。Django代表full-stack。Tornado代表asynchronous 。可以这样认为吗？
是否可以这样说：这3个框架基本可以代表Python Web开发的主要模式？

我觉得这些框架只有功能多寡的不同，没有模式的不同 binux@v2ex
>从0考虑一个web框架可能有什么：
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

#### app framework

- app factory
- blueprint
- api/template error handling
- development/testing/staging/production server configurations
- db logic
- db logic error handing
- controller
- delayed jobs
- json serialization/template rendering

#### management

- database miggration
- app manage commands

#### testing

- moking/testing
- profiling(performance testing)
- security testing

#### deployment/operation/monitor

- deployment automation
- manage automation
- app exception monitor
- app/db performance monitor

## Python Web前端模板引擎

+ [jinja2](http://jinja.pocoo.org/docs/dev/api/)
    * [欢迎来到 Jinja2](http://docs.jinkan.org/docs/jinja2/)
    * [另一个中文版](http://www.pythonfan.org/docs/python/jinja2/zh/index.html)

+ [mako](http://www.makotemplates.org/)
    * [Python模板库Mako的语法（译自官方文档）](http://www.yeolar.com/note/2012/08/28/mako-syntax/)
    * [对于mako模板的一些使用心得](http://java114.iteye.com/blog/756942)

+ [Cheetah](http://www.cheetahtemplate.org/)
    * [使用 Python 和 Cheetah 构建和扩充模板](http://www.ibm.com/developerworks/cn/opensource/os-pythcheetah/)

### Python Web前端模板引擎 比较


## Python Web ORM组件

+ Django
    * [django orm总结](http://www.cnblogs.com/linjiqin/p/3817954.html)

+ [sqlalchemy](http://www.sqlalchemy.org/)
    * [SQLAlchemy 1.0 Documentation](http://docs.sqlalchemy.org/en/rel_1_0/)
    * [SQLAlchemy0.3.4指南(tutorial)](http://gashero.yeax.com/?p=6#id9)
    * [SQLAlchemy 使用经验](http://www.keakon.net/2012/12/03/SQLAlchemy%E4%BD%BF%E7%94%A8%E7%BB%8F%E9%AA%8C)
    * [使用 SQLAlchemy](http://www.ibm.com/developerworks/cn/aix/library/au-sqlalchemy/)

### Python Web ORM组件比较

+ [SQLAlchemy 和其他的 ORM 框架](http://www.oschina.net/translate/sqlalchemy-vs-orms)

## Python 数据库

+ [mongodb](https://www.mongodb.org/)
    * [The MongoDB 3.0 Manual](https://docs.mongodb.org/manual/)
    * [MongoDB教程](http://www.yiibai.com/mongodb/)
    * [MongoDB基本使用](http://www.cnblogs.com/TankMa/archive/2011/06/08/2074947.html)
    * [API Documentation for MongoDB Drivers](http://api.mongodb.org/)

+ [mysql](http://www.mysql.com)
    * [MySQL Documentation](http://dev.mysql.com/doc/)
    * [MySQL教程](http://www.yiibai.com/mysql/)
    * [Basic MySQL Tutorial](http://www.mysqltutorial.org/basic-mysql-tutorial.aspx)

### Python 数据库比较

+ [勿盲从！请理性选择SQL和NoSQL解决方案](http://tech.it168.com/a2015/0111/1697/000001697648.shtml)
+ [NoSQL开篇——为什么要使用NoSQL](http://www.infoq.com/cn/news/2011/01/nosql-why/)

#  Web开发基础知识

## [W3School](http://www.w3school.com.cn/sql/sql_update.asp)
>W3School是网页编程的学习网站，涉及HTML, CSS, JavaScript, SQL, XML等 内容

## [廖雪峰的官方网站](http://www.liaoxuefeng.com/)
>学习Web编程的好去处, GitHub地址为: <https://github.com/michaelliao>

##  [Python官网](https://docs.python.org/3.4/library/asyncio.html?highlight=asyncio#module-asyncio)
   + [Full Stack Python](http://www.fullstackpython.com/introduction.html?from=itblog)
   + [The Vital Guide to Python Interviewing](http://www.toptal.com/python#hiring-guide)
   + [一篇文章入门Python生态系统](http://codingpy.com/article/python-ecosystem-introduction/)
   + [Python进阶必读汇总](http://www.kuqin.com/shuoit/20151116/348975.html)
   + [Python之科普篇](http://www.douban.com/group/topic/13347288/)
   + [你是如何自学 Python 的？](http://www.zhihu.com/question/20702054)
   + [python模块之HTMLParser](http://www.tuicool.com/articles/jiqYr2)
   + [python:利用asyncio进行快速抓取](http://blog.jobbole.com/63897/)
   + [使用Python下载邮件(pop/imap)](http://www.pythoner.com/414.html)
   + [Python Club](http://www.pythonclub.org/)
   + [Python in JOBBOLE](http://blog.jobbole.com/category/python/)
   + [写给已有编程经验的 Python 初学者的总结](http://blog.jobbole.com/79197/)
   + [如何入门 Python 爬虫？](http://www.zhihu.com/question/20899988/answer/24923424)
   + [Python爬虫框架Scrapy实战定向批量获取职位招聘信息](http://blog.csdn.net/HanTangSongMing/article/details/24454453)
   + [零基础自学用Python 3开发网络爬虫](http://jecvay.com/category/smtech/python3-webbug)
   + [Python初学者资料](https://github.com/Yixiaohan/codeparkshare/blob/master/README.md)
   + [你是如何开始能写python爬虫？](http://www.zhihu.com/question/21358581)
   + [开源一个 python 脚本驱动的定向爬虫](http://v2ex.com/t/103525)
   + [标准爬虫初探，来自Python之父的大餐！](http://developer.51cto.com/art/201411/456836.htm)
   + [500lines](https://github.com/aosabook/500lines)
   + [Python爬虫学习记录](http://blog.csdn.net/cwyalpha/article/details/48111173)
   + [python3爬虫之入门和正则表达式](http://rlovep.com/2015/09/23/python3%E7%88%AC%E8%99%AB%E4%B9%8B%E5%85%A5%E9%97%A8%E5%92%8C%E6%AD%A3%E5%88%99%E8%A1%A8%E8%BE%BE%E5%BC%8F/)
   + [基于scrapy的上市公司信息抓取工具](https://github.com/zihaolucky/Crawl_Stocks_Info)
   + [What is a metaclass in Python?](http://blog.jobbole.com/21351/)
   + [Python高级特性（1）：Iterators、Generators和itertools](http://blog.jobbole.com/66097/)
   + [Python高级特性（2）：Closures、Decorators和functools](http://blog.jobbole.com/66895/)
   + [Python高级特性（3）: Classes和Metaclasses](http://blog.jobbole.com/67748/)
   + [Welcome to aiomysql’s documentation!](http://aiomysql.readthedocs.org/en/latest/)
   + [Python程序员必知必会的开发者工具](http://blog.jobbole.com/58226/)
   + [Python yield 使用浅析](http://blog.jobbole.com/32876/)
   + [Python关键字yield详解](http://blog.jobbole.com/28506/)
   + [Python程序员的常见错误](http://blog.jobbole.com/69834/)
   + [Python高级编程技巧](http://blog.jobbole.com/61171/)
   + [给Python初学者的一些技巧](http://blog.jobbole.com/32748/)
   + [Python程序员的10个常见错误](http://blog.jobbole.com/68256/)
   + [Python编程中常用的12种基础知识总结](http://blog.jobbole.com/48541/)
   + [30个有关Python的小技巧](http://blog.jobbole.com/63320/)
   + [高级正则表达式技术（Python版）](http://blog.jobbole.com/65605/)
   + [写给Python初学者的设计模式入门](http://blog.jobbole.com/62023/)
   + [爱的 Python : Python中函数式编程](http://blog.jobbole.com/35028/)
   + [Python编程中的反模式](http://blog.jobbole.com/74252/)
   + [Python 代码性能优化技巧](http://blog.jobbole.com/77042/)
   + [Python 3 Readiness](http://py3readiness.org/)
   + [Special Method Names](http://www.diveintopython3.net/special-method-names.html)
   + [与 Python 无缝集成——基本特殊方法 4](http://segmentfault.com/a/1190000004008393?utm_source=Weibo&utm_medium=shareLink&utm_campaign=socialShare)
   + [提高你的Python: 解释‘yield’和‘Generators（生成器）’](http://www.oschina.net/translate/improve-your-python-yield-and-generators-explained)
   + [从底层理解Python的执行](http://www.csdn.net/article/2015-05-28/2824795)
   + [Python 高级特性](http://segmentfault.com/a/1190000000498466?utm_source=tuicool&utm_medium=referral)
   + [Python函数式编程指南](http://www.cnblogs.com/huxi/archive/2011/06/18/2084316.html)
   + [Python 开源异步并发框架的未来](http://segmentfault.com/a/1190000000471602)
   + [Asynchronous IO Support Rebooted: the "asyncio" Module](http://legacy.python.org/dev/peps/pep-3156/)
   + [Understanding Asynchronous IO With Python 3.4's Asyncio And Node.js](http://sahandsaba.com/understanding-asyncio-node-js-python-3-4.html)
   + [python:利用asyncio进行快速抓取](http://developer.51cto.com/art/201403/434352.htm)
   + [初探 Python 3 的异步 IO 编程](http://www.keakon.net/2015/09/07/%E5%88%9D%E6%8E%A2Python3%E7%9A%84%E5%BC%82%E6%AD%A5IO%E7%BC%96%E7%A8%8B)
   + [Python 3.4 中新的 asyncio ： Servers、Protocols 和 Transports](http://www.oschina.net/translate/the-new-asyncio-in-python-34-servers-pro)
   + [Python程序的执行原理](http://tech.uc.cn/?p=1932)


## HTTP协议
+ [HTTP必知必会](http://www.cnblogs.com/starstone/p/4890409.html)
+ [图解HTTP（上）](http://www.cnblogs.com/xing901022/p/4309840.html)
+ [图解HTTP（下）](http://www.cnblogs.com/xing901022/p/4311987.html)
+ [HTTP响应头和请求头信息对照表](http://tools.jb51.net/table/http_header)
+ [HTTP 状态消息](http://www.w3school.com.cn/tags/html_ref_httpmessages.asp)
+ [关于URL编码](http://www.ruanyifeng.com/blog/2010/02/url_encoding.html)


## [被误解的 MVC 和被神化的 MVVM](http://blog.devtang.com/blog/2015/11/02/mvc-and-mvvm/)
