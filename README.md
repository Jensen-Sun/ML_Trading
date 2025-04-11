# ML_Trading
算法交易-机器学习在交易中的应用
从yfinance中导入’AAPL’2010-2024年数据，计算特征’X’的相关系数，完成对特征的筛选，并做标准化处理；采用逻辑回归、朴素贝叶斯、决策树、随机森林和神经网络对股价的涨跌进行预测，运用Confusion Matirx、f1-score 对预测结果进行评价；依据模型预测结果构建交易策略进行回测，比较每种算法的Cumulative returns、Maximum Drawdown和Sharpe ratio，实验结果显示决策树和随机森林的Sharpe Ratio较高，分别为3.17和3.77，但是模型的最大回撤均超过20%，需注重风险控制。
