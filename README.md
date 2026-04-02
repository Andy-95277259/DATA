## 个人基本信息

* 个人学号：2025303110009
* 个人姓名：王迪月
* Github账号：@Andy-95277259
* 项目名称：《Effective treatment of Cu2+-containing acid mine drainage with acidic-cupric resistant electroactive biofilms》 论文复现

## 项目内容
1. 该论文发表于2025年的《Journal of Environmental Management》
2. 论文DOI：https://doi.org/10.1016/j.jenvman.2025.125875
3. 测序数据已提交至NCBI，BioProject编号为PRJNA1091201

## 可重复性评估
1. 方法完整性：MFC反应器构型、运行参数、pH梯度、铜离子浓度、电化学/表征/测序方法均明确标注，步骤无模糊点；
2. 数据完备性：正文+附件包含SEM-EDS、元素定量、菌群多样性等全部支撑数据，无关键信息缺失；
3. 依赖透明性：无未公开代码、私有数据集，实验参数与分析逻辑可直接复现；
4. 结论可验证性：核心结论（酸性条件抑制产电、吸附+沉淀协同除铜、关键功能菌群富集）可重复验证。

## 运行方式
1. 环境准备：Python 3.10
   安装依赖：pip install pandas==1.5.3 matplotlib==3.6.0
2. 运行代码：
   cd 项目根目录
   python code/full_reproduce.py
3. 结果查看：
   数据在reproduce-project/data下
   生成的七张图片在reproduce-project/output下（PNG格式）
