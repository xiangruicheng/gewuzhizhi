
《证券分析》
《经营分析与估值》
《彼得林奇的成功投资》
《财富报表分析与股票估值》-郭永清
《投资最重要的事》
《周期》
《市场是怎么失败的》一书中，约翰·卡西迪


select * from ( select date,sum(amount)/100000000 as money from kline where code in('1A0001','399001') and date>20230101 group by date ) as t order by t.money desc;