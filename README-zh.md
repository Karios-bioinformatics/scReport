# scReport

<p align="center">
  <strong>Making bioinformatics results interactive.</strong>
</p>

scReport 是一个主要面向单细胞生物信息学的交互式报告生态（Interactive Reporting Ecosystem），致力于将分析结果从零散的静态图片、表格和脚本中组织起来，构建统一、可探索、可分享、可复现的科学报告。

scReport 以单细胞分析为起点，将逐步覆盖单细胞分析工作流中的核心分析流程，并最终构建覆盖主要分析结果的交互式报告体系，为结果展示、科研协作、成果共享与可重复研究提供统一的解决方案。

项目起源于一次需要管理大量单细胞分析结果的研究实践，以及对上游自动化 QC 报告的思考。

English version: [README.md](https://github.com/Karios-bioinformatics/scReport/blob/main/README.md)

## 生态

| 模块 | 状态 | 仓库 | DOI / 归档 | 关注内容 |
|---|---:|---|---|---|
| **scReportLite** | `0.4.0` | [Repository](https://github.com/Karios-bioinformatics/scReportLite) | [Zenodo](https://doi.org/10.5281/zenodo.20828069) | 单细胞基础报告：QC、降维、marker、注释信息和交互式浏览。 |
| **scReportComposition** | 计划中 | [Repository](https://github.com/Karios-bioinformatics/scReportComposition) | [Zenodo](https://doi.org/10.5281/zenodo.20955461) | 细胞类型组成、样本比例、分组比例和 composition overview 报告。 |
| **scReportDE** | 计划中 | [Repository](https://github.com/Karios-bioinformatics/scReportDE) | 计划中 | 差异表达报告：DEG 表、火山图、表达分布、top marker 和比较摘要。 |
| **scReportEnrichment** | 计划中 | [Repository](https://github.com/Karios-bioinformatics/scReportEnrichment) | 计划中 | GO、KEGG、Reactome、Hallmark gene sets 等功能富集结果报告，包括富集条目、基因集、显著性和关联基因。 |
| **scReportSubcluster** | 计划中 | 计划中 | 计划中 | 选定细胞群内部的二次聚类、亚群 marker、比例变化和功能差异。 |
| **scReportTrajectory** | 计划中 | 计划中 | 计划中 | 轨迹和拟时序报告，包括细胞状态转换、分支结构和动态基因表达。 |
| **scReportVelocity** | 计划中 | 计划中 | 计划中 | RNA velocity 报告，包括状态变化方向、velocity vector、latent time、动态基因和命运趋势。 |
| **scReportCommunication** | 计划中 | 计划中 | 计划中 | 细胞通讯报告，包括配体-受体关系、信号通路、发送/接收细胞关系和分组差异。 |
| **scReportTF** | 计划中 | 计划中 | 计划中 | 转录因子活性、靶基因、regulon、motif enrichment 和细胞类型特异性调控。 |
| **scReportRegulatoryNetwork** | 计划中 | 计划中 | 计划中 | 基因调控网络、转录因子-靶基因关系、调控模块、拓扑结构和细胞类型特异性网络。 |
| **scReportGeneSetScore** | 计划中 | 计划中 | 计划中 | 基因集活性得分，例如 pathway score、signature score、metabolic score、immune score 等。 |
| **scReportModuleScore** | 计划中 | 计划中 | 计划中 | 用户定义模块、疾病模块或细胞状态模块在不同细胞群中的表达活性。 |
| **scReportCellCycle** | 计划中 | 计划中 | 计划中 | 细胞周期阶段分布、细胞周期评分，以及对 PCA、cluster、UMAP 和 marker 分析的影响。 |
| **scReportCNV** | 计划中 | 计划中 | 计划中 | 拷贝数变异报告，包括 CNV heatmap、CNV score、肿瘤/正常细胞区分和亚克隆结构。 |
| **scReportClonotype** | 计划中 | 计划中 | 计划中 | TCR/BCR 克隆型、克隆扩增、克隆共享、克隆多样性，以及克隆型与细胞状态关系。 |
| **scReportMultiomics** | 计划中 | 计划中 | 计划中 | scRNA-seq、scATAC-seq、CITE-seq、空间组学、甲基化组、蛋白组等多组学整合报告。 |
| **scReportSpatial** | 计划中 | 计划中 | 计划中 | 空间映射和空间转录组报告，包括细胞类型空间分布、组织区域、空间邻域、空间 marker 和映射关系。 |
| **scReportPseudobulk** | 计划中 | 计划中 | 计划中 | 拟 bulk 表达矩阵、样本层面比较、差异表达、可视化和统计结果。 |
| **scReportCoexpression** | 计划中 | 计划中 | 计划中 | 共表达关系、共表达模块、hub genes，以及模块与细胞类型、表型或样本分组之间的关联。 |

## 模块页面

- [scReportLite README](https://github.com/Karios-bioinformatics/scReportLite/blob/main/README.md)
- [scReportComposition README](https://github.com/Karios-bioinformatics/scReportComposition/blob/main/README.md)
- [scReportDE README](https://github.com/Karios-bioinformatics/scReportDE/blob/main/README.md)
- [scReportEnrichment README](https://github.com/Karios-bioinformatics/scReportEnrichment/blob/main/README.md)
