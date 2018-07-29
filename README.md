## python-crawl


一个爬取今日头条新闻的Python案例，使用Scrapy框架


## scrapy vs requests+beautifulsoup

beautiful soup可以离线解释html文件，但是获取html文件是由用户的其他行为的定义的，比如urllib或者request<br/>
而scrapy是一个完整的获取程序，只需要把网址贴上去，就会自动去爬，省去很多用户需要关注的细节


## 两种爬虫模式比较：
1、requests和beautifulsoup都是库，scrapy是框架。<br/>
2、scrapy框架中可以加入requests和beautifulsoup。<br/>
3、scrapy基于twisted，性能是最大的优势。<br/>
4、scrapy方便扩展，提供了很多内置的功能。<br/>
5、scrapy内置的css和xpath selector非常方便，beautifulsoup最大的缺点就是慢。

<br/>

## 爬虫能做什么？<br/>
1、搜索引擎---百度、谷歌、垂直搜索引擎。<br/>
2、推荐引擎---今日头条<br/>
3、机器学习数据样本<br/>
4、数据分析（如金融数据分析）、舆情分析等。

<br/>

## 网页分类：<br/>
常见类型的服务：<br/>
1、静态网页<br/>
2、动态网页<br/>
3、webservice（restapi）
