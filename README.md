## 个人基本信息

* 个人学号：2025303110009
* 个人姓名：王迪月
* Github账号：@Andy-95277259
* 项目名称：《Effective treatment of Cu2+-containing acid mine drainage with acidic-cupric resistant electroactive biofilms》 论文复现

## 项目内容
该论文发表于2025年的《Journal of Environmental Management》
论文DOI：https://doi.org/10.1016/j.jenvman.2025.125875
测序数据已提交至NCBI，BioProject编号为PRJNA1091201

## 可重复性评估
1.方法完整透明：MFC反应器构型、运行参数、pH梯度、铜离子、浓度、电化学/表征/测序方法均明确标注，无模糊步骤。
2.数据配套齐全：正文 + 附件提供SEM-EDS、元素定量、菌群多样性等全部支撑数据，无关键信息缺失。
3.无私有依赖：无未公开代码、私有数据集，实验参数与分析逻辑可直接复现。
4.结论可验证：核心结果（酸性抑制产电、吸附+沉淀除铜、关键菌群富集）可重复验证。

## 运行方式
1.安装依赖：pip install pandas matplotlib
2.运行代码：python code/analysis.py
3.查看结果：图表生成在figures/,报告在report/
