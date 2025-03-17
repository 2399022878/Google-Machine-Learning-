# 基本概念

- 从基本层面来说，机器学习是指训练一款名为[模型](https://developers.google.cn/machine-learning/glossary?hl=zh-cn#model)的软件，以便做出有用的[预测](https://developers.google.cn/machine-learning/glossary?hl=zh-cn#prediction)或根据数据生成内容。
- 模型是从数据中派生出来的数学关系，机器学习系统会使用这些关系进行预测。
- 特征是监督式模型用于预测标签的值。标签是“答案”，即我们希望模型预测的值。
- 非监督学习使用无标签样本
- 模型会学习特征与标签之间的数学关系，以便对未见过的数据做出最准确的预测。
  - 通过将 prediction 和 labeled example（即实际值）进行比较
  - 通过loss
- 评估模型时，使用带标签的数据集，但只为模型提供数据集的特征，最后比较prediction与label。

# Numpy as np

- np.array
- np.arrange
- np.zeros
- np.ones
- np.random.random
- np.random.randint

# Pandas as pd

- mydf = pd.DataFrame(data = ,columns = columns_names)
- mydf.head(a) 显示前a行数据
- mydf.iloc[[a]]，单独显示第a行
- a  = pd.read_csv("name")
-
