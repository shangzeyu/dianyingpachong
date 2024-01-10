# dianyingpachong
电影爬虫
这个项目是一个简单的网络爬虫，用于抓取豆瓣电影Top250的数据并保存为CSV文件。下面是这个项目的详细介绍、使用方法、依赖库以及代码运行效果。

项目介绍：
这个项目通过发送HTTP请求到豆瓣电影的Top250页面，然后使用BeautifulSoup库解析HTML文档，提取出电影的详细信息。最后，将这些电影信息保存到CSV文件中。

使用方法：

首先，将项目代码克隆到本地。
安装项目所需的依赖库。可以使用pip命令安装requests和beautifulsoup4库：pip install requests beautifulsoup4
打开命令行终端，进入项目代码所在的目录。
运行代码：python main.py
依赖库：
这个项目主要使用了以下几个Python库：

requests：用于发送HTTP请求。
beautifulsoup4：用于解析HTML文档，提取出需要的数据。
csv：用于将电影数据保存到CSV文件。
代码运行效果：
当运行代码时，程序将会输出运行时间，例如：

Time taken: 5.081579208374023 seconds
同时，程序会在当前目录下生成一个名为"Douban Top250 Movies.csv"的CSV文件，其中包含了豆瓣电影Top250的详细信息。
