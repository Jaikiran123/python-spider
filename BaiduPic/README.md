#利用python爬取百度图片

由于百度图片网页是ajax动态加载的，所以不能直接在源码中获取全部图片的url。通过selenium模拟浏览器的行为，点击加载更多，就可以获取加载出的图片url。

* get_html.py获取源码

* picDownload.py负责下载