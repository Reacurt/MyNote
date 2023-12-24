## 一、WEB

### 1、信息收集

#### (1)dirsearch 目录扫描

##### robots.txt

robots.txt是网站管理者写给爬虫的一封信，里面描述了网站管理者不希望爬虫做的事，比如：

不要访问某个文件、文件夹
禁止某些爬虫的访问
限制爬虫访问网站的频率

一个自觉且善意的爬虫，应该在抓取网页之前，先阅读robots.txt，了解并执行网站管理者制定的爬虫规则。

##### .phps (index.phps)

phps文件就是php的源代码文件，通常用于提供给用户（访问者）查看php代码，因为用户无法直接通过Web浏览器看到php文件的内容，所以需要用phps文件代替。其实，只要不用php等已经在服务器中注册过的MIME类型为文件即可，但为了国际通用，所以才用了phps文件类型。

它的MIME类型为：text/html, application/x-httpd-php-source, application/x-httpd-php3-source。

##### 网站备份

常见的网站源码备份文件后缀:

tar.gz，zip，rar，tar

常见的网站源码备份文件名：

web，website，backup，back，www，wwwroot，temp