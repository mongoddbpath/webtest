# webtest
### 学校成绩管理系统项目测试
### 这是一个从开发到测试都完整进行的项目，也是毕业论文设计所设计的项目，老师评语:开发和测试能力不错
### 这次展示的是系统的登陆模块测试
### 系统的登陆页面
![](http://or30iz1wj.bkt.clouddn.com/%E7%99%BB%E9%99%86%E9%A6%96%E9%A1%B5OK.jpg)
### 这是测试用例的编写(正常的话应该是在QC中编写的)
![](http://or30iz1wj.bkt.clouddn.com/%E6%B5%8B%E8%AF%951OK.jpg)
![](http://or30iz1wj.bkt.clouddn.com/%E6%B5%8B%E8%AF%952OKOK.jpg)
### 测试环境的搭建；是Wamp环境；各版本号:apache是2.4.9,php是5.5.12， mysql是5.6.17
### 测试用例的执行
![](http://or30iz1wj.bkt.clouddn.com/%E6%B5%8B%E8%AF%95%E7%94%A8%E4%BE%8B%E7%9A%84%E6%89%A7%E8%A1%8COK.jpg)
### 之后的压力性能测试(用的是apache自带的AB工具)
![](http://or30iz1wj.bkt.clouddn.com/%E5%8E%8B%E5%8A%9B%E6%B5%8B%E8%AF%95%E4%B8%8E%E6%80%A7%E8%83%BD%E6%B5%8B%E8%AF%95OK.jpg)
从中我们可知，在系统完成1000请求量和10并发量测试之后的结果分析，该系统登陆页面的吞吐量为60.23，每个请求耗时约为17ms;有很多可以优化的空间
