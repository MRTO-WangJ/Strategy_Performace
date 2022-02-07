# Strategy_Performace
基础量化投资类库

适用于量化投资初学者、代码新手、以及希望构建自己投资框架并寻求参考的同学。

类库包括三个部分：0、数据接口层；1、数据计算层；2、投资策略和回测计算部分（Strategy）；3、图片列表展示部分（Performance）

第一部分设定总投资域和样本时间，包括特殊剔除样本，如上市不满一年、ST股票等。

第二部分主要是投资策略编写以及收益序列的计算，包括因子投资、交叉线策略或着机器学习等。

第三部分主要根据投资策略收益时间序列计算组合收益评价指标，并且用图表方式展现。

类支持月度调仓
类库基于日度or月度数据
类库测试数据均来自国泰安
