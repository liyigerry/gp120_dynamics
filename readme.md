# gp120动态性研究

## gp120多构象比较性研究
[代码](./dynamics)
Insight into dynamics, molecular motions, and free energy landscape of HIV-1 gp120 in different conformational states: A comparative molecular dynamics study 

比较研究三种状态全长gp120结构（unliganded，CD4-free liganded, liganded gp120 complexed with CD4）的动力学行为，查明三者间在全局和局部构象柔性、结构（几何）性质、
分子运动以及自由能图谱上的差异。重点讨论局部构象柔性差异、局部结构区域运动（包括尺度和方向）与构象转化、CD4结合、辅助受体结合的关联性。最终通过构建的FEL明确
三种状态gp120的热力学和能力学性质差异，以此来解释三者在动力学行为上的差异。该方面的研究对理解HIV-1 gp120的侵染机制和免疫逃避机理会有所帮助。

## CD4结合对gp120构象动态性的影响
[代码](./CD4_binding)
Effect of CD4 binding on dynamics, molecular motions, and FEL of HIV-1 gp120
这部分研究以liganded状态gp120为研究对象，主要是通过组合本质动力学手段分析CD4结合前后liganded状态gp120在分子运动、CD4结合腔和FEL上的变化。需要指出的是，CD4结合之前，
对于单体gp120分子（gp120 free in solution, 并非trimer上的gp120），其应该采取类似于CD4结合后liganded状态（参见桑鹏和一篇PNAS的文章）。对于同样的liganded gp120初始态，
CD4存在与CD4不存在会对它的动力学行为造成影响，具体包含结构性质、分子运动以及FEL图谱上的变化，明确这些变化（或差异）有助于理解gp120结构-动力学-功能三者间的关系。


## gp120构象转换倾向性
[代码](./transition_preference)
Preference for conformation transition between unliganded, CD4-free, and CD4-complexed gp120. 通过计算不同状态间的本质子空间重叠，推测三种状态间构象转换倾向性的大小。
具体请参照科学通报的文章。


## gp120高温解折叠模拟
[代码](./high_temperature_unfolding)
通过高温分子动力学模拟手段，研究CD4-dependent gp120和CD4-independent gp120在稳定性和构象柔性上的差异，并找到造成这种差异的结构因素；通过构建二者在常温条件下的FEL，
解释构象柔性和热稳定性差异背后的理化机制，该方面的研究能够从物理化学原理的角度阐明gp120对CD4依赖的分子机制。

## gp120自由能图谱的构建
[代码](./pt_wte)

## 主要方法
1. 多副本分子动力学模拟
2. 平衡轨迹分析
3. 本质动力学/tICA
4. 自由能图谱构建
5. 马尔可夫状态模型
6. 复本交换和权重直方图分析
