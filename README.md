- 👋 Hi, I’m @ys00huan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ys00huan/ys00huan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
开始
│
├── 阶段1: 数据预处理与特征工程
│   │
│   ├── 数据清洗: 处理缺失值和异常值
│   ├── 特征构建: 
│   │   ├── 基础时序特征 (滞后值、滑动窗口统计)
│   │   ├── 周期性特征 (星期几、季度等)
│   │   └── 事件特征 (节假日、促销)
│   └── 特征选择: 相关性分析和重要性排名
│   │
│   └── 输出: 预处理数据集
│
├── 阶段2: 模型构建
│   │
│   ├── 实现基线模型: ARIMA, Prophet, LSTM, LightGBM
│   ├── 开发核心模型: 
│   │   ├── 选择backbone (LSTM或Transformer)
│   │   ├── 集成注意力机制 (时间注意力、特征注意力)
│   │   └── 模型优化 (Dropout, Adam优化器)
│   └── 模型训练: 使用训练集，早期停止
│   │
│   └── 输出: 训练好的模型文件
│
├── 阶段3: 实验验证与评估
│   │
│   ├── 验证设置: 时间序列交叉验证
│   ├── 评估指标: WRMSSE, MAE, MSE
│   ├── 对比分析: 与基线模型和现有方法比较
│   ├── 可解释性分析: 可视化注意力权重
│   └── 统计分析: 显著性检验
│   │
│   └── 输出: 实验报告和图表
│
├── 阶段4: 迭代优化与部署准备
│   │
│   ├── 超参数调优: 网格搜索或贝叶斯优化
│   ├── 模型简化: 剪枝或量化
│   ├── 部署准备: 封装为API或工具
│   └── 文档生成: 用户指南和API文档
│   │
│   └── 输出: 最终模型和部署包
│
└── 结束









