# 鸢尾花数据集分类实验
机器学习入门项目，基于 sklearn 实现三种基础分类算法的对比实验。

## 技术栈
Python 3.x / scikit-learn / Pandas / Matplotlib

## 项目内容
1. 数据加载与探索：使用 sklearn 内置鸢尾花数据集，查看特征与类别分布
2. 数据集划分：按 7:3 比例拆分训练集与测试集
3. 模型实现：分别训练逻辑回归、K近邻、决策树三种分类模型
4. 效果对比：通过准确率指标对比不同算法的分类表现
5. 可视化分析：绘制特征散点图，直观展示数据分布规律

## 运行方式
1. 安装依赖
```bash
pip install scikit-learn pandas matplotlib
运行主程序
python iris_classification.py
学习总结
 
- 掌握了监督学习分类任务的完整流程：数据加载 → 数据划分 → 模型训练 → 效果评估

- 理解了逻辑回归、KNN、决策树三种基础算法的调用方式与适用场景

- 熟悉了 sklearn 常用API的使用方法
