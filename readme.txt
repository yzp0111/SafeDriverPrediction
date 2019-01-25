kaggle安全驾驶预测（保险索赔几率）
Porto Seguro’s Safe Driver Prediction

data文件夹中为数据文件

code文件夹中为执行代码
SDP_xgb.ipynb文件为Jupyter notebook的执行文件

工具：python+numpy+sklearn+pandas+xgboost

分析数据特征间相关性，用heatmap可视化呈现，删除无用特征；
cat特征的缺失值看做一个新类别；
顺序/连续性特征的缺失值用中位数补全，并进行归一化；
定义基尼函数，作为损失函数的度量方法；
用XGBClassifier分类器；

测试得分 0.284