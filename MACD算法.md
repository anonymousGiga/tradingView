MACD主要由以下几个指标组成，分别是DIFF、DEA和MACD柱。

# 1 DIFF
DIFF是快速移动平均线(即EMA1)和慢速移动平均线(即EMA2)之差，在有些地方DIFF也直接叫作MACD。例如tradingview的示例pinescript中就叫作macd。

# 2 DEA
DIFF的均值叫作DEA，此值也叫作DEM

# 3 MACD柱
此值的计算方式为：MACD = (DIFF-DEA) * 2，主要用来表示强度。

# 4 要点
macd是一个价格强度指标，而不是趋势指标。MACD是的滞后的趋势强度指标，而不是一个具有前瞻性的先行指标。

常用的方式是：金叉买入，死叉卖出。不过值得注意的是：**MACD指标不是用来判断「趋势」，而是用来判断「强度」**

macd背离：价格创新高（新低），但是强度变弱（变强），说明趋势正在减弱。
