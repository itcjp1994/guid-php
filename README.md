# guid
1:执行microtime(),获取当前的微秒数
2:把获取的微秒数转换为double类型
3:再用转换后的数字去乘以1000000
4:给随机数发生器播种,播种数为第三步得出的结果
rand为生成0到RAND_MAX 之间的伪随机整数,RAND_MAX的值因平台不同而不同
mt_srand() 函数作用是播下随机数发生器种子
