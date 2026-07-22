# 数据分析 & 机器学习项目集

西安财经大学应用统计硕士 — 课程与个人项目代码合集。

---

## 项目列表

### 1. 客户价值分层与流失预警模型

基于 RFM 模型对电商客户进行价值分层，使用逻辑回归与 XGBoost 构建流失预警模型。

- **数据**：Kaggle E-Commerce Customer Behavior（5000 条订单记录）
- **方法**：RFM 分层、PCA 降维、逻辑回归、XGBoost
- **成果**：AUC = 0.82，识别 12% 高价值核心客群

📓 [在线查看 Notebook](https://nbviewer.jupyter.org/github/ranwei-xxcj/ranwei-portfolio-projects/blob/main/%E5%AE%A2%E6%88%B7%E4%BB%B7%E5%80%BC%E5%88%86%E5%B1%82%E4%B8%8E%E6%B5%81%E5%A4%B1%E9%A2%84%E8%AD%A6%E6%A8%A1%E5%9E%8B.ipynb)

---

### 2. 保险索赔金额预测与风险因子分析

基于 XGBoost 预测保险索赔金额，通过特征工程与 WOE 编码识别关键风险因子。

- **数据**：保险索赔数据集（50 万条保单与索赔记录）
- **方法**：WOE 编码、对数变换、XGBoost、网格搜索、SHAP 分析
- **成果**：RMSE = 0.38（相比均值基线提升 24%），识别车辆品牌与历史违章为关键因子

📓 [在线查看 Notebook](https://nbviewer.jupyter.org/github/ranwei-xxcj/ranwei-portfolio-projects/blob/main/%E4%BF%9D%E9%99%A9%E7%B4%A2%E8%B5%94%E9%87%91%E9%A2%9D%E9%A2%84%E6%B5%8B%E4%B8%8E%E9%A3%8E%E9%99%A9%E5%9B%A0%E5%AD%90%E5%88%86%E6%9E%90.ipynb)

📄 [最终报告 (docx)](./保险索赔预测报告.docx)

---

### 3. 期货交易绩效归因分析系统

基于 Python 构建交易数据分析与风控系统，计算收益率、波动率、最大回撤、VaR 等核心指标，精准定位收益贡献与风险来源。

- **数据**：AKShare 螺纹钢期货日线（1500+ 条）
- **方法**：LSTM、双向 LSTM、自注意力池化、技术指标特征工程
- **成果**：系统性消融实验证明纯技术指标无法有效预测短期涨跌，提出 7 条改进方向

📓 [在线查看 Notebook](https://nbviewer.jupyter.org/github/ranwei-xxcj/ranwei-portfolio-projects/blob/main/%E6%9C%9F%E8%B4%A7%E4%BA%A4%E6%98%93%E7%BB%A9%E6%95%88%E5%BD%92%E5%9B%A0%E5%88%86%E6%9E%90%E7%B3%BB%E7%BB%9F.ipynb)

---

## 技术栈

`Python` `Pandas` `NumPy` `Scikit-learn` `XGBoost` `PyTorch` `LSTM` `Matplotlib` `Seaborn` `SHAP` `Imbalanced-learn`

## 如何查看

点击上方 📓 链接，通过 **nbviewer** 在线查看完整的 Notebook（含代码、输出、图表），无需安装任何环境。

## 作者

**冉威** — 西安财经大学应用统计硕士

- 求职意向：AI 应用开发工程师 / 数据分析师
- 作品集：[在线作品集](https://ranwei-xxcj.github.io)
