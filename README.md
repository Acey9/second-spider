second-spider
=============

Another spider powered by gevent,requests,pyquery 

1. The concurrency foundation on [gevent](http://www.gevent.org/)
2. The spider strategy highly configurable:

> 
* max depth 
* the count of urls you want fetch 
* the max concurrency of http request,avoid dos
* the http request headers and cookie can be set
* just crawl same host url
* just crawl same domain url


### Usage

        spider = Spider()
        spider.setRootUrl("http://www.sina.com.cn")
        spider.run()

### Read more

Please read the code for more details.
If you are chinese reader, refer to http://blog.kenshinx.me for more details
