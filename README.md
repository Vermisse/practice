# 项目介绍 #

人工智能练习，目前实现了华容道

* 没有图形界面，以自定义数组保存结果，表现不够直观，使用Web项目是为了扩展界面
* 使用数据库保存缓存结果，因为可以监测计算过程，不过大幅拖慢了性能，也不敢开多线程，可以用Redis替换
* 使用Scala因为抽象层次更高，缺点是代码比较难读