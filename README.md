# Pandapower 入门指南
Pandapower 是一个基于 Python 的电力系统分析工具，它提供了简单易用的 API 来进行电力系统建模、潮流计算、优化等。

## 项目结构概览

现有的教程文件都在 `tutorials/` 目录下，涵盖了从入门到高级的多个主题。以下是推荐的学习路径：

### 第一阶段：基础入门（建议按顺序学习）

1. **`minimal_example.ipynb`** - 最小示例，快速了解 pandapower 的基本用法
2. **`create_simple.ipynb`** - 创建简单电网模型
3. **`create_advanced.ipynb`** - 创建高级电网模型
4. **`powerflow.ipynb`** - 潮流计算基础
5. **`plotting_basic.ipynb`** - 基本可视化
6. **`internal_datastructure.ipynb`** - 内部数据结构

### 第二阶段：进阶主题

- **`time_series.ipynb`** 和 **`time_series_advanced_output.ipynb`** - 时序仿真
- **`opf_basic.ipynb`** - 最优潮流 (OPF)
- **`diagnostic.ipynb`** - 电网诊断
- **`contingency_analysis.ipynb`** - 故障分析

### 第三阶段：专业应用

- **`shortcircuit/`** - 短路计算
- **`protection/`** - 继电保护
- **`FACTS.ipynb`** - FACTS 设备
- **`state_estimation.ipynb`** - 状态估计
- **`cim2pp.ipynb`** - CIM 数据导入（你当前打开的）


## 环境准备

你需要：
1. **安装 pandapower**: `pip install pandapower`
2. **额外依赖**: `pip install matplotlib networkx pandas numpy`
3. **运行 Jupyter Notebook**: 在 VSCode 中可以直接打开 `.ipynb` 文件运行

