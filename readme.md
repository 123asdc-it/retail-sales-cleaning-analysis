# 零售销售数据清洗与可视化项目
## 项目简介
针对零售门店销售数据集，完成**缺失值/异常值/格式/重复值清洗**，输出规范数据集+数据校验报告，为后续运营分析提供干净数据支撑。

## 技术栈
- 数据处理：Python 3.8+、Pandas
- 开发工具：Jupyter Notebook
- 数据格式：CSV

## 文件结构
```
retail-sales-cleaning-analysis/
├── data/          # 数据集目录
│   ├── raw_data.csv     # 原始销售数据（1万条记录）
│   └── cleaned_data.csv # 清洗后规范数据
├── notebooks/     # 代码目录
│   └── Project1_零售销售数据清洗与可视化.ipynb  # 核心代码（含清洗+校验）
├── .gitignore     # 忽略无关文件
└── README.md      # 项目说明
```

## 核心功能
1. 数据清洗：处理缺失值（无）、异常值（负销量/单价）、日期格式、重复交易ID；
2. 数据校验：全方位验证清洗后数据的完整性、有效性；
3. 数据保存：输出规范CSV文件，可直接用于后续可视化/分析。

## 快速使用
1. 克隆仓库：\`git clone https://github.com/123asdc-it/retail-sales-cleaning-analysis.git\`
2. 安装依赖：\`pip install pandas -i https://pypi.tuna.tsinghua.edu.cn/simple\`
3. 打开Notebook：运行\`notebooks/Project1_零售销售数据清洗与可视化.ipynb\`即可复现结果
