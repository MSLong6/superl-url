# 运行截图

![image](https://github.com/super-l/search-url/blob/master/screenshots1.png)
![image](https://github.com/super-l/search-url/blob/master/screenshots2.png)

Author:superl
--------
Blog:www.superl.org
--------

# 使用说明
* 测试环境为 Python 2.7.x 如果需要python3版本的，可以自行修改，或者[我的博客](http://www.superl.org)留言

* 目前只可以采集百度搜索引擎的结果。并且每页默认显示50条记录。可自定义输入要采集的页数。

* 如果要采集关键词为“hacker”的相关网站，采集百度结果的前3页，则输入如下：

  * please input keyword:hacker

  * Search Number of pages:3



# 特点
* 获取到的是百度搜索结果的真实URL地址
* 可以忽略不需要的常见网站，如忽略百度翻译，等等所有百度相关结果，给数组添加baidu.com即可。程序已经默认忽略了很多条啦，如

  filter_array1 = ['baidu.com','sina.com.cn','sohu.com','taobao.com','douban.com','163.com','tianya.cn','qq.com','1688.com']

  filter_array2 = ['ganji.com','58.com','baixing.com']

  filter_array3 = ['zhihu.com','weibo.com','iqiyi.com','kugou.com','51.com','youku.com','soku.com','acfun.cn','verycd.com']

  filter_array4 = ['google.cn','youdao.com','iciba.com','cdict.net']

  filter_array5 = ['pconline.com.cn','zcool.com.cn','csdn.net','lofter.com']
  
* 实时显示采集到的网页的【真实URL】以及【标题】。前面的【ID】对应的是当前页百度结果的第X条数据
* 自动保存结果到当前目录的txt文件，文件名为搜索的 关键词.txt
* 自动去除重复记录
* 统计总采集条数（143 found），有效的条数（91 checked），被过滤的条数（52 filter），以及被过滤的重复的URL条数（9 delete）


# 关于更新
由于时间仓促，没有做优化。很多自定义参数也采用了默认值，下一个版本加上自定义参数
如果百度更新导致采集不到内容，可以[我的博客](http://www.superl.org)留言联系我进行修改

