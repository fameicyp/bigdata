# bigdata
kafka的offset偏移量维护在mysql中 \t
VipIncrementAnalysis类需求是:按地区分组统计每日新增VIP数量 \t
UnPaymentAyalysis 类的需求是:订单行为异常用户及时运营 \t
通过BI数据分析，发现某段时间有部分用户短时间内多次进入付费定单页，却没有成为VIP用户。 \t
我们要做的是通过实时计算，把这部分潜在VIP用户抓取出来，提供给客服或运营人员及时处理，增加这部分用户的VIP转化率。 \t
