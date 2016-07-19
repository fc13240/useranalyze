# useranalyze
电商用户行为分析

此项目主要包含三个模块。
1、用户访问session分析：该模块主要是对用户访问session进行统计分析，包括session的聚合指标计算、按时间比例随机抽取session、获取每天点击、下单和购买排名前10的品类、并获取top10品类的点击量排名前10的session。主要使用Spark Core实现。

2、页面单跳转化率统计：该模块主要是计算关键页面之间的单步跳转转化率，涉及到页面切片算法以及页面流匹配算法。主要使用Spark Core实现。

3、热门商品离线统计：该模块主要实现每天统计出各个区域的top5热门商品。主要使用Spark SQL实现。

4、广告流量实时统计：该模块负责实时统计广告流量，包括广告展现流量和广告点击流量。实现动态黑名单机制，以及黑名单过滤，主要使用Spark Streaming实现。

