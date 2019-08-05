
### 一分钟学会爬虫: PyQuery

* 抓取目标网页
  from pyquery import PyQuery as pq
  d = pq(url='http://google.com/')
  
* 解析内容
  ul_items = d('ul').items()
  ul_items = d('li a').items()
  ul_items = d('.page-title').items()
  
* 解析属性
  item.attr('href')
  item.text()
  
