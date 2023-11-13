# Jike-Web-Crawler
A web crawler to collect product name and description from Jike

# Description
首先，因为这个网页有反爬+动态加载，而且它本身就不能显示到底有几个产品，即使我在手机上看，都只能一页看十几个，然后手动点刷新才会出新产品（还有重复），所以解决方案如下：

每隔一段时间（比如一周、一个月）你可以手动跑一下这个程序：

你每次跑程序会出现的事情：爬取网页上出现的产品名和产品描述，自动循环100次后去重（本次循环100次后爬出了不重复的125个产品），生成两个表格：1. 你爬出过的所有产品的总表JikeProductList_Overall（会自动去重）；2. 本次运行程序爬出来的新程序JikeProductList_自动添加程序运行的日期

📌文件夹内容（在跑程序的时候永远让这些文件在同一个文件夹里）：
1. 爬虫本虫：Jike_Crawler.ipynb
2. 产品总表：JikeProductList_Overall.csv（用Excel打开）
3. 今天我爬出来的125个产品：JikeProductList_2023-08-30.csv（用Excel打开）


