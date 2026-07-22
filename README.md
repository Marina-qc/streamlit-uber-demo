# Uber Pickups in NYC

一个用 Streamlit 做的小型数据可视化应用：加载纽约市 2014 年 9 月的 Uber 接客记录，展示原始数据表、按小时统计的接客次数柱状图，以及一张可以用滑块按小时筛选的交互式地图。

## 技术栈

- Python
- [Streamlit](https://streamlit.io/) — 构建交互式网页界面
- [Pandas](https://pandas.pydata.org/) — 数据加载与处理
- [NumPy](https://numpy.org/) — 数值计算（按小时统计直方图）

## 本地运行

1. 安装依赖：

   ```bash
   pip install -r requirements.txt
   ```

2. 启动应用：

   ```bash
   streamlit run uber_pickups.py
   ```

3. 浏览器会自动打开 `http://localhost:8501`，即可看到应用效果。

## 数据来源

数据集为纽约市 2014 年 9 月的 Uber 接客记录，来自 [Streamlit 官方教程](https://docs.streamlit.io/get-started/tutorials/create-an-app) 提供的公开示例数据（`uber-raw-data-sep14.csv.gz`）。

## 关于这个项目

这是我跟着 Streamlit 官方教程 [Create an app](https://docs.streamlit.io/get-started/tutorials/create-an-app) 一步步做的学习项目，目的是练习如何使用 AI 编程工具（Claude Code）辅助开发。
