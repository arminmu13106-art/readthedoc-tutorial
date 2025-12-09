Template for the Read the Docs tutorial
=======================================
示例：
linkedin-cv-classifier/          # GitHub仓库根目录
│
├── 📄 FINAL_REPORT.pdf          # 必须提交的最终PDF报告
├── 📄 README.md                 # 项目介绍和快速开始指南
├── 📄 requirements.txt          # Python依赖包列表
│
├── 📂 notebooks/                # Jupyter笔记本（主要工作区）
│   ├── 📘 1_data_exploration.ipynb
│   ├── 📘 2_data_preprocessing.ipynb
│   ├── 📘 3_feature_engineering.ipynb
│   ├── 📘 4_rule_based_baseline.ipynb
│   ├── 📘 5_embedding_approach.ipynb
│   ├── 📘 6_model_training.ipynb
│   └── 📘 7_final_evaluation.ipynb
│
├── 📂 src/                      # Python源代码（可重用的函数）
│   ├── 📄 __init__.py
│   ├── 📄 data_loader.py       # 加载数据的功能
│   ├── 📄 text_cleaner.py      # 清洗文本的功能
│   ├── 📄 feature_extractor.py # 提取特征的功能
│   └── 📄 model_utils.py       # 模型训练和评估工具
│
├── 📂 config/                   # 配置文件
│   └── 📄 labels.yaml          # 职业领域和资历的标签定义
│
├── 📂 data/                     # 数据文件夹（可能需要.gitignore）
│   ├── 📂 raw/                 # 原始数据
│   ├── 📂 processed/           # 处理后的数据
│   └── 📂 external/            # 外部数据（如SNAPADDY测试数据）
│
├── 📂 models/                   # 保存训练好的模型
│   ├── 📄 domain_classifier.pkl
│   └── 📄 seniority_predictor.pkl
│
└── 📂 reports/                  # 生成的报告和图表
    ├── 📄 confusion_matrix.png
    └── 📄 feature_importance.png
This GitHub template includes fictional Python library
with some basic Sphinx docs.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/
