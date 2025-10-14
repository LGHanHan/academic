---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# 👧 About Me

我目前在西安科技大学[通信与信息工程学院](https://txxy.xust.edu.cn/)攻读硕士学位，主要从事物体姿态估计、三维点云重建以及雷达图像处理等方面的研究。导师为[王静副教授](https://txxy.xust.edu.cn/1445131440.html)。

目前，我已经发表SCI论文4篇。此外还有1篇SCI一区论文和会议论文在投。参与横向项目两项，积极参加各类技术比赛并荣获多项荣誉。

<span class='anchor' id='educations'></span>

# 📖 Educations

- 2019-2023，西安科技大学，通信与信息工程学院，电子信息工程，学士

- 2023-now，西安科技大学，通信与信息工程学院，电子信息，硕士

<span class='anchor' id='skills'></span>

# 💡 Skills
**1. 工具与框架**
- 编程语言: 熟练使用Python、Matlab等编程语言。
- 深度学习框架: 精通Pytorch、tensorflow、OpenCV（图像处理）。
- 科研工具: 熟练掌握Latex（论文攥写）、Git（版本控制）、Visio（算法流程图设计）。

**2. 深度学习模型设计与优化**
- 擅长设计端到端的深度学习网络，具备多种注意力机制（ECA、CBAM、金字塔、transformer等）、多尺度特征融合以及解耦机制的应用经验。
- 擅长在线形状优化、仿射变换等多种数据增强方法，掌握跨域数据集成等前沿技术，解决类内形状差异导致的泛化性问题。
- 精通各种超参数调整方法并熟练掌握学习率调控策略。

**3. 数据处理与算法实现**.
- 数据预处理与特征工程：
  熟练进行数据清洗、滤波、时序特征提取（如发电厂脱硫系统项目中处理工业传感器数据）。
  掌握多模态数据（RGB-D、SAR图像、点云）的融合方法。
- 数学建模与优化：
  具备扎实的数学建模能力（数学建模国赛二等奖），擅长将实际问题转化为优化问题（如二氧化硫浓度预测模型）。
- 算法落地与性能调优：
  具备工业级算法部署经验，熟悉模型精度评估与迭代优化流程。
  熟练使用各种去噪算法提升模型稳定性。

**4. 科研与工程能力**
- 学术研究能力：
  具备独立研究课题的能力，能够系统性地梳理领域前沿问题并提出创新性解决方案，并设计合理的实验方案进行验证。
- 工程实践能力：
  参与工业级项目（发电厂脱硫系统），熟悉工业数据采集、模型部署与系统集成。
- 团队协作能力：
  多次担任团队核心成员（比赛和项目），具备项目分工协调与进度管理能力。

  <span class='anchor' id='papers'></span>
  
# 📝 Papers

<!-- Paper -->

- **SAR图像的检测与分类**

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2024.01 - 2024.08</div>
<img src='images/publications/SAR.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

- Automatic Aircraft Identification with High Precision from SAR Images Considering Multiscale Problems and Channel Information Enhancement, Remote Sensing, JCR1区（导师一作）

该系统具有全天、全天候成像的能力，在飞机识别应用中具有很高的价值。然而，由于散斑噪声干扰、多尺度问题和复杂的背景干扰，从SAR图像中识别飞机仍然面临着很大的挑战。

</div><div markdown="1">


**主要研究:**
1. 提出了一种高效的双向路径多尺度融合关注网络（EBMA-Net）。它采用双向连通性，融合不同尺度飞机的特征，即使在背景非常复杂的情况下也能对飞机进行准确的检测。

2. 在EBMA-Net中，提出了一个高效多尺度信道注意融合（EMCA）模块和三个并行挤压高效信道注意（SECA）模块。其中EMCA模块通过叠加上下融合模块创建双向路径，有效地融合了浅层细节特征和深层语义信息，从而提高了飞机在不同尺度下的检测性能。SECA模块，对特征通道之间的依赖关系进行了显式建模，可以自动学习不同通道的重要性，对关键特征进行优先级排序，从而提高飞机识别的精度和鲁棒性。

3. 实验使用高分辨率SAR系统的飞机识别公共数据集（即GF-3卫星生成的SAR- aircraft -1.0）。结果表明，EBMA-Net的平均飞机检测精度为91.31%，其识别飞机的准确率可以达到95.6%。因此，EBMA-Net在飞机探测和识别方面明显优于其他网络。所提出的EBMA-Net能够捕获细节信息，较好地抑制背景干扰，也可用于从SAR图像中检测和识别不同尺度和背景的密集目标。

</div>
</div>

<!-- Paper -->

- **基于深度学习的物体姿态估计综述**
<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2024.10 - now</div>
<img src='images/publications/Zongshu.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

- From Visual Understanding to 6D Pose Reconstruction: A Cutting-Edge Review of Deep Learning-Based Object Pose Estimation, Displays, JCR1区（导师一作）

物体姿态估计是计算机视觉中的核心问题，为了帮助研究人员更好地了解这一领域，本文详细地总结了实例级、类别级以及未见物体和铰接体的位姿估计方法。根据输入数据的不同模态，重点介绍了基于深度学习的物体位姿估计方法的实现方式、应用领域、训练范式、网络架构及其优缺点，并比较了这些方法在不同数据集上的性能表现。此外，针对当前的技术瓶颈，本文还从多视角融合、跨模态数据集成及新型神经网络的前沿探索出发，展望了未来的发展方向，为推动物体姿态估计领域的突破性进展提供了全新的思路与借鉴。

</div>
</div>

<!-- Paper -->

- **FusePose：一个基于多信息融合的单目相机位姿估计网络**

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2024.10 - now</div>
<img src='images/publications/FusePose.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

- FusePose: A Monocular Camera Pose Estimation Network Based on Multi-Modal Information Fusion, JCR1区在投（导师一作）

相机姿态估计是计算机视觉领域的核心挑战之一，旨在推断相机相对于场景的位置和方向。然而，相机位姿估计任务仍面临诸多挑战。一方面，运动模糊会使图像特征难以提取与匹配，干扰位姿计算。另一方面，视点变化问题同样对相机位姿估计造成阻碍。当相机视点发生变化时，场景中物体的可见部分、视角以及与相机的距离等都会改变。这导致不同视点下获取的图像差异较大，使得位姿估计模型难以学习到稳定的特征模式。

</div><div markdown="1">

**主要研究:**
1. 本文提出了一个基于多信息融合的单目相机位姿估计网络—FusePose。FusePose在PoseNet2的基础上，通过时态感知定位模块（LSVO）和语义信息感知模块（SEMA）提取视觉里程计信息和场景语义信息。

2. LSVO模块实现了视觉里程计信息的高效提取。与之前的方法相比，LSVO模块解决了双暹罗网络在训练过程中产生的神经元偏置偏移现象。

3. 7-Scenes数据集不含语义标签，因此本文在7-Scenes数据集的基础上自建了一个语义分割图数据集，用于语义信息的提取。

4. SEMA模块通过构建四分路语义特征提取网络提取场景间的高级语义信息，并且采用自适应的特征融合方法，对不同尺度的语义特征进行合并。

5. FusePose通过将多尺度语义信息与视觉里程计信息联合约束，可以在相机位姿估计中充分利用场景中的高层结构信息和低层几何信息。语义信息可以识别出静态背景区域，将这些区域作为主要的几何约束源，视觉里程计信息能够在静态背景区域中更好的确定动态物体前后位置变化。两者的联合约束提高了位姿估计的精度和鲁棒性。

</div>
</div>

<!-- Paper -->

- **SDCNet:对称性驱动的类别级物体姿态估计网络**
<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2024.10 - now</div>
<img src='images/publications/SDCNet.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

- SDCNet: A Symmetry-Driven Network for Category-Level Object Pose Estimation, Remote Sensing, Measurement and Big Data（会议论文，导师一作）

物体姿态估计通过确定物体在三维空间中的位置和朝向，为各类测量工作提供关键的物体姿态参数，从而有效提升测量的精度与可靠性。本文设计了一个对称性驱动的类别级物体姿态估计网络—SDCNet。

</div>
</div>

<!-- Paper -->

- **SymPose：基于几何约束和在线形状优化方法的类别级物体姿态估计网络**

<div class='paper-box'>
    <div class='paper-box-image' style="display: flex; gap: 10px;">
        <div>
            <div class="badge">2024.06 - now</div>
            <img src='images/publications/B.gif' alt="sym" style="width: 100%;">
        </div>
        <div>
            <img src='images/publications/XZ.gif' alt="sym" style="width: 100%;">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
      
- SymPose: A Category-Level Object Pose Estimation Network Based on Geometric Constraints and Online Shape Optimization, IEEE sensors journal, JCR1区在投（导师一作）

在类别级物体姿态估计中，同一物体类别（例如瓶子、椅子等）内不同实例之间的几何形状、大小、比例等存在较大差异。这种差异使得系统无法依赖于简单的形状模板或通用特征来估计姿态，因为不同实例的特征变化可能导致模型对其姿态的理解出现偏差。

</div><div markdown="1">
      
**主要研究:**

1. 本文提出了名为SymPose的类别级物体姿态估计网络，旨在解决类内形状变化导致的模型泛化性较差问题。

2. SymPose通过点云优化模块使得模型能够灵活地适应类内的形状差异，并在处理不同物体时仍具有较高的精度。

3. 该网络在点云重建的过程中引入了基于几何信息的物理约束，利用物体的本征属性使得模型能够更好地理解物体的几何特性，从而减少估计过程中的不确定性。

4. 最后，为了减少离群点对物体姿态估计性能的影响，本文还设计了一个基于点云密度的离群鲁棒优化器。

</div>
</div>

<!-- Paper -->

- **LA-Net：基于多尺度特征融合和注意机制的端到端类别级目标姿态估计网络**

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2024.01 - now</div>
<img src='images/publications/mug_360views.gif' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

- LA-Net: An End-to-End Category-Level Object Attitude Estimation Network Based on Multi-Scale Feature Fusion and an Attention Mechanism, Electronics, JCR2区（导师一作）

目前类别级物体姿态估计方法在处理复杂物体的三维结构与多样化外观时，难以准确提取关键特征，进而导致姿态估计精度受限。并且基于两阶段的传统方法，在特征提取与姿态预测的过程中，存在计算步骤繁琐、资源消耗大的弊端，无法满足实时性要求较高的应用场景。本文旨在设计一种高效的端到端的姿态估计网络，实现高效的物体六自由度恢复。并且基于端到端的架构避免了两阶段过程中计算资源的消耗，因此具有较高的推理速度。

</div><div markdown="1">

**主要研究:**
1. 本文提出了一种基于多尺度特征融合和注意力机制的端到端类别级物体姿态估计网络LA-Net，能够高效恢复物体的六自由度姿态。

2. LA-Net通过引入线性连接层（Linear Connection Layer），扩展了三维图卷积网络的架构，从而实现了不同层级特征的多尺度融合。

3. 其次，LA-Net结合金字塔注意力机制和Max-Pooling层，提取物体的局部和全局几何信息，显著增强了网络对物体姿态的感知能力。

4. 最后，为了避免姿态估计中平移和旋转信息的相互影响，网络采用解耦机制分别恢复物体的旋转和平移信息。试验结果表明，与基线方法相比，LA-Net在目标姿态估计方面具有更高的精度。特别是对于具有复杂形状的物体，在10°2 cm指标上提高了5%。

</div>
</div>


<span class='anchor' id='project'></span>

# 🔍 Project
- **发电厂智能烟气脱硫系统**

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2023.03 - 2024.07</div>
<img src='images/publications/SO2.png' alt="sym3" width="100%">
</div>
<div class='paper-box-text' markdown="1">

**项目简介：**
  
以火力发电厂机组石灰石-石膏湿法烟气脱硫系统为对象，主要研究脱硫浆液 pH 值控制过程中的自动控制系统及其优化控制，提高出口二氧化硫浓度预测精度，从而降低发电厂的脱硫成本。
</div><div markdown="1">


**完成工作：**
1. 对发电厂采集的原始信号进行数据清洗，滤波和时序数据处理。
  
2. 在 tensorflow 框架下搭建并训练了基于 GRU 循环神经网络架构的二氧化硫浓度预测模型。

3. 通过 MAE、MSE 等指标全面评估模型效果，并在实际场景下测试可视化预测效果。

4. 封装模型文件编写与系统的对接程序。

<span class='anchor' id='honors-and-awards'></span>

# 🏆 Honors and Awards

**🏅 Honors**
- 2024.5，研究生学业一等奖学金（8/19）
- 2024.11，优秀研究生 （1/23）
- 2024.12，国家奖学金（2/5）
- 2024.12，徐精彩奖学金（1/5）
- 2025.5，研究生学业一等奖学金（1/19）

**🎏 Competitions**
- 2023，研电赛三等奖
- 2023，全国大学生数据分析理论赛一等奖
- 2023，全国大学生数据分析实战赛三等奖
- 2024，研电赛三等奖
- 2024，数学建模校赛二等奖
- 2024，数学建模国赛二等奖
- 2024，第六届研究生人工智能创新大赛三等奖
- 2024，西安科技大学通信学院第二界学术会议论坛三等奖
- 2025, 数学建模校级一等奖
- 2025，华数杯全国大学生数学建模三等奖
- 2025，全国大学生数据分析竞赛二等奖
- 2025，国家奖学金

<span class='anchor' id='society'></span>
  
# 🏰 Society

2019.09 - 2023.06，西安科技大学通信学院科技创新实验室
