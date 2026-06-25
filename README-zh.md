# scReport

<p align="center">
  <strong> Making bioinformatics results interactive.</strong>
</p>

scReport 是一个主要面向单细胞生物信息学的交互式报告生态（Interactive Reporting Ecosystem），致力于将分析结果从零散的静态图片、表格和脚本中组织起来，构建统一、可探索、可分享、可复现的科学报告。

scReport 以单细胞分析为起点，将逐步覆盖单细胞分析工作流中的核心分析流程，并最终构建覆盖主要分析结果的交互式报告体系，为结果展示、科研协作、成果共享与可重复研究提供统一的解决方案。

项目起源于一次需要管理大量单细胞分析结果的研究实践，以及对上游自动化 QC 报告的思考。

## 生态
### scReportLite


**版本号**：0.4.0

**GitHub**：[项目地址](https://github.com/Karios-bioinformatics/scReportLite)

**Zenodo**：[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20828069.svg)](https://doi.org/10.5281/zenodo.20828069)


#### 简介
scReportLite 是一个面向单细胞 RNA 测序（scRNA-seq）基础分析结果的交互式 HTML 报告生成 R 包。

它不试图替代 Seurat 等单细胞分析工具，也不负责重新执行完整分析流程，而是专注于将上游分析已经产生的结果表、降维坐标、QC 指标、marker 结果和注释信息，整理为可交互浏览、可追溯逻辑、可分享讨论的报告。

详细内容请参照[scReportLite README](https://github.com/Karios-bioinformatics/scReportLite/blob/main/README.md)

---
### scReportComposition


**版本号**：计划中

**GitHub**：[项目地址](https://github.com/Karios-bioinformatics/scReportComposition)

**Zenodo**：计划中


#### 简介
scReportComposition 是 scReport 软件生态中面向单细胞细胞类型组成分析（cell-type composition analysis）的交互式 HTML 报告生成 R 包。

它主要关注不同样本、分组、条件或处理之间的细胞比例变化，并将细胞组成差异、cluster / cell type 占比、组间比例比较等结果整理为可交互浏览和讨论的报告。

---
### scReportDE


**版本号**：计划中

**GitHub**：[项目地址](https://github.com/Karios-bioinformatics/scReportDE)

**Zenodo**：计划中


#### 简介
scReportDE 是 scReport 软件生态中面向差异表达分析（differential expression analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注不同细胞类型、簇、样本分组或实验条件之间的基因表达差异，并将差异表达基因表、火山图、表达分布、top marker / top DEG 结果等内容整理为可交互浏览、可追溯逻辑、可分享讨论的报告。

---
### scReportEnrichment


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportEnrichment 是 scReport 软件生态中面向功能富集分析（functional enrichment analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注 GO、KEGG、Reactome、Hallmark gene sets 等功能富集结果，并将富集条目、基因集、显著性、富集方向和相关基因列表整理为可交互浏览和解释的报告。

---
### scReportSubcluster


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportSubcluster 是 scReport 软件生态中面向亚群分析（subcluster analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注某一类细胞或某一个 cluster 内部的再次聚类、亚群划分、亚群 marker、亚群比例变化以及亚群之间的功能差异。

---

### scReportTrajectory


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportTrajectory 是 scReport 软件生态中面向轨迹分析与拟时序分析（trajectory / pseudotime analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注细胞状态转换、发育轨迹、分化路径、pseudotime 排序、分支结构以及沿拟时序变化的基因表达模式。

---
### scReportVelocity


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportVelocity 是 scReport 软件生态中面向 RNA velocity 分析结果的交互式 HTML 报告生成 R 包。

它主要关注细胞状态变化方向、velocity vector、latent time、动态基因以及细胞命运趋势等结果。

---
### scReportCommunication


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportCommunication 是 scReport 软件生态中面向细胞通讯分析（cell-cell communication analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注不同细胞类型之间的配体-受体关系、通讯强度、信号通路、发送细胞与接收细胞关系，以及不同分组之间通讯模式的变化。

---
### scReportTF


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportTF 是 scReport 软件生态中面向转录因子分析（transcription factor analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注转录因子活性、调控靶基因、regulon、motif enrichment 以及不同细胞群中的转录调控差异。

---
### scReportRegulatoryNetwork


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportRegulatoryNetwork 是 scReport 软件生态中面向调控网络分析（regulatory network analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注基因调控网络、转录因子-靶基因关系、调控模块、网络节点、边权重以及细胞类型特异性的调控结构。

---
### scReportGeneSetScore


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportGeneSetScore 是 scReport 软件生态中面向基因集打分（gene set scoring）结果的交互式 HTML 报告生成 R 包。

它主要关注不同细胞、cluster、cell type 或样本组中的基因集活性得分，例如 pathway score、signature score、metabolic score、immune score 等。

---
### scReportModuleScore


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportModuleScore 是 scReport 软件生态中面向模块打分（module score analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注由一组基因定义的功能模块、细胞状态模块或疾病相关模块在不同细胞群中的表达活性。

---
### scReportCellCycle


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportCellCycle 是 scReport 软件生态中面向细胞周期分析（cell cycle analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注 G1、S、G2/M 等细胞周期阶段分布，细胞周期评分，以及细胞周期状态对 PCA、cluster、UMAP 和 marker 结果的影响。

---
### scReportCNV


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportCNV 是 scReport 软件生态中面向拷贝数变异分析（copy number variation analysis, CNV）结果的交互式 HTML 报告生成 R 包。

它主要关注单细胞层面的染色体片段拷贝数变化、肿瘤细胞与正常细胞区分、CNV heatmap、CNV score、亚克隆结构和样本间 CNV 差异。

---
### scReportClonotype


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportClonotype 是 scReport 软件生态中面向克隆型分析（clonotype analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注 TCR / BCR 克隆型、克隆扩增、克隆共享、克隆多样性以及克隆型与细胞状态之间的关系。

---
### scReportMultiomics


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportMultiomics 是 scReport 软件生态中面向多组学整合分析（multi-omics integration）结果的交互式 HTML 报告生成 R 包。

它主要关注 scRNA-seq、scATAC-seq、CITE-seq、空间组学、甲基化组、蛋白组等多种数据类型之间的整合关系。

---
### scReportSpatial


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportSpatial 是 scReport 软件生态中面向空间映射与空间转录组分析（spatial mapping / spatial transcriptomics analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注细胞类型在空间位置中的分布、空间区域注释、空间邻域关系、空间 marker、空间共定位以及单细胞数据与空间数据之间的映射关系。

---
### scReportPseudobulk


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportPseudobulk 是 scReport 软件生态中面向拟 bulk / pseudobulk 分析结果的交互式 HTML 报告生成 R 包。

它主要关注将单细胞数据按照样本、细胞类型、cluster 或实验条件聚合后的表达矩阵，并在此基础上进行组间比较、差异表达、样本层面可视化和统计分析结果展示。

---
### scReportCoexpression


**版本号**：计划中

**GitHub**：计划中

**Zenodo**：计划中


#### 简介
scReportCoexpression 是 scReport 软件生态中面向共表达网络分析（co-expression network analysis）结果的交互式 HTML 报告生成 R 包。

它主要关注基因之间的共表达关系、共表达模块、模块特征基因、模块与细胞类型 / 表型 / 样本分组之间的关联。

