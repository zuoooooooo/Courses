# Optimization Experiment

This repository contains files and scripts for an optimization experiment. The project includes various input data, methods, results, and charts related to the tested optimization algorithms.

## Directory Structure
- `Optimization Experiment Report.pdf`: PDF document of the optimization experiment report
- `environment.yml`: Environment configuration file for setting up dependencies
- `lab.ipynb`: Jupyter Notebook containing the experiment code and analysis
- `README.md`: This README file

### Input Files
- `a9a.txt`: Input data file
- `FISTA1`: First FISTA method file
- `FISTA2`: Second FISTA method file
- `Prox1`: First proximal method file
- `Prox2`: Second proximal method file
- `result.txt`: Optimization experiment results
- `solution.txt`: Solution file

### Figures
- `AGD-1.png`: Accelerated Gradient Descent 1 chart
- `AGD-2.png`: Accelerated Gradient Descent 2 chart
- `C1.png`: C1 chart
- `C2.png`: C2 chart
- `FISTA-1.png`: FISTA 1 chart
- `FISTA-2.png`: FISTA 2 chart

## How to Use

1. **Set Up Environment**:
    - This experiment relies on the following libraries:
      * numpy
      * pandas
      * matplotlib.pyplot
    - Ensure you have Anaconda or Miniconda installed.
    - Create the environment using the provided `environment.yml` file:
      ```sh
      conda env create -f environment.yml
      ```
    - Activate the environment:
      ```sh
      conda activate <environment-name>
      ```

2. **Run the Experiment**:
    - Open `lab.ipynb` with Jupyter Notebook:
      ```sh
      jupyter notebook lab.ipynb
      ```
    - Make sure the input files are in the same directory as `lab.ipynb`.
    - Execute the cells in the notebook to run the optimization experiment and generate results.

3. **View Results**:
    - Check the charts in the `figures` directory for visual representations of the optimization process.
    - Read the `Optimization Experiment Report.pdf` for a detailed report on the experiment.

## Project Description

This project aims to compare different optimization algorithms, including FISTA (Fast Iterative Shrinkage-Thresholding Algorithm) and proximal gradient methods. The generated results and charts provide insights into the performance and convergence characteristics of these algorithms.

## Contact

For any questions or inquiries, please contact zuoyihong@mail.ustc.edu.cn.


# 优化实验

这个仓库包含了一个优化实验的文件和脚本。该项目包括了与测试的优化算法相关的各种输入数据、方法、结果和图表。

## 目录结构
- `优化实验报告.pdf`：优化实验报告的PDF文档
- `environment.yml`：用于设置依赖项的环境配置文件
- `lab.ipynb`：包含实验代码和分析的Jupyter Notebook
- `README.md`：这个README文件
### 输入文件
- `a9a.txt`：输入数据文件
- `FISTA1`：第一个FISTA方法文件
- `FISTA2`：第二个FISTA方法文件
- `Prox1`：第一个近端方法文件
- `Prox2`：第二个近端方法文件
- `result.txt`：优化实验结果
- `solution.txt`：解决方案文件

### figures
- `AGD-1.png`：加速梯度下降1的图表
- `AGD-2.png`：加速梯度下降2的图表
- `C1.png`：C1图表
- `C2.png`：C2图表
- `FISTA-1.png`：FISTA 1的图表
- `FISTA-2.png`：FISTA 2的图表



## 如何使用

1. **设置环境**:
    - 本实验主要依赖以下库：
      * import numpy as np
      * import pandas as pd
      * import matplotlib.pyplot as plt
    - 若需要完整环境，请确保已安装Anaconda或Miniconda。
    - 使用提供的`environment.yml`文件创建环境：
      ```sh
      conda env create -f environment.yml
      ```
    - 激活环境：
      ```sh
      conda activate <环境名称>
      ```

2. **运行实验**:
    - 使用Jupyter Notebook打开`lab.ipynb`：
      ```sh
      jupyter notebook lab.ipynb
      ```
    - 在运行时可能需要将输入文件中的文件与`lab.ipynb`放在一个目录下
    - 执行笔记本中的单元格，执行优化实验并生成结果。

3. **查看结果**:
    - 参考`figures`目录中的图表，了解优化过程的可视化表示。
    - 阅读`优化实验报告.pdf`，了解实验的全面报告。

## 项目描述

该项目旨在比较不同的优化算法，包括FISTA（快速迭代收缩阈值算法）和近似点梯度方法。生成的结果和图表有助于理解这些算法的性能和收敛特性。

## 联系方式

如有任何问题或疑问，请联系zuoyihong@mail.ustc.edu.cn。



