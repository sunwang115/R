R语言数据处理与科研绘图使用视频教程：




使用教程：https://baozl.com/2026/10/31/r-%e8%af%ad%e8%a8%80%e9%a1%b6%e5%88%8a%e7%a7%91%e7%a0%94%e7%bb%98%e5%9b%be-skill-%c2%b7-%e6%96%b0%e6%89%8b%e4%bd%bf%e7%94%a8%e6%95%99%e7%a8%8b/




开源地址：https://github.com/sunwang115/R-skill/tree/main




R 语言顶刊科研绘图模板图鉴（全 21 期汇总）

本合集来自公众号「宝藏郎」的 R 语言顶刊科研绘图（R 语言绘图图鉴） 系列，共 21 期、覆盖 411 个 SCI/Nature 风格绘图模板，配套 R 代码 + 示例数据，可直接套用自己的数据出图。

配合 R 语言顶刊绘图 Skill 使用，无需自己写 R 代码，给出数据位置 + 要画的图，Skill 会自动安装环境并绘图。

一、本合集包含哪些种类的图（图鉴总览）

下面按科研场景把 411 个模板归为 17 大类，方便你按需求快速定位。

1. 柱状 / 条形类

基础柱状图、分组柱状图、堆叠 / 百分比堆叠柱状图、双向柱状图、正负分布条形图、分裂 / 分面条形图、圆点柱状图、径向条形图、环形 / 极坐标柱状图、南丁格尔玫瑰图、显著性柱状图、堆积百分比柱状图、绝对量柱状堆积图、柱状误差点线图、柱状图 + 蜂群散点、柱状图结合富集分析（通路加到柱上）、复现 Cell/Nature 风格柱状图、扩增子带进化树物种柱状图等。

2. 箱线 / 小提琴 / 云雨 / 分布类

基础箱线图、分组箱线图、配对箱线图、多组配对箱线图、箱线图分面、排序箱线图、差异箱线图、多基因 / 多组差异箱线图、小提琴图、小提琴图分面、多基因小提琴图、配对连线小提琴图、split 小提琴图、显著性标记小提琴图、云雨图、连线云雨图、配对云雨图、分组散点 + 箱线 + 小提琴 + 条形组合图、分组直方图、箱线累积分布曲线图、循环箱线图等。

3. 散点 / 气泡 / 相关性类

基础散点图、多组合散点图、分组散点图、时间趋势散点图、个性化散点图、拟合曲线散点图、带误差棒点图、误差线点图、气泡图、变化趋势气泡图、显著性气泡图、相关性散点图、线性相关性分析、多层注释散点图、不同组散点 + 回归 / 多项式拟合、相互作用 dot、偏差图等。

4. 热图 / 矩阵 / 聚类类

基础热图、CNS 级热图、离散型 / 环状 / 环形热图、组合版热图、相关性热图、回归模型热图、方差分解热图、行列注释热图、个性化注释热图、单列热图 + 文字 / 显著性 / 箭头注释、多层分组热图、聚类热图、新版 / 简单整洁 / 临床相关性热图、热图与折线图 / 柱状图组合、ChIP·ATAC·CUT&Tag heatmap、IMATE / 组合 / 区域 / 华夫 / 砖块热图、WGCNA heatmap、组合进化树与热图等。

5. 火山图 / 差异表达类

火山图、多组火山图、EnhancedVolcano 火山图、瀑布图、棒棒糖图（Lollipop）、卡通版棒棒糖图、哑铃图、突变频谱（mutationSignature）、突变热点等。

6. 降维 / 排序类（PCA·PCoA·tSNE·UMAP·NMDS）

PCA 散点图、三维 PCA 图、PCA 叠加密度曲线、PCA 比较不同样本、PCA 分析、PCoA 分析、envfit_pcoa_pca_nmds_rda_cca、降维 PCA/PCOA/NMDS、tSNE、细胞类群 UMAP、复现 Nature 单细胞 UMAP、单细胞 Seurat 替换 UMAP 坐标、pcoa_boxplot（patchwork 拼图）等。

7. 富集分析 / 通路 / 功能类

GO 富集分析网络图、GO 柱状图（分组色彩）、GO 圈图、KEGG 圈图、GOplot、DAVIDkappa、pathway_sup、基因功能富集分析泡泡图、富集分析柱状图（通路加到柱上）、GSEA、GSEA_Java、GSEA_clusterProfiler、多 GSEA 富集图、GSEA 多组富集、GSVA、ssGSEA、ROAST 检验、enrichment 转录因子 coupling 等。

8. 网络 / 互作 / 系统类

PPI 蛋白互作网络、PPImodule、pyscenic 转录因子 TF-target 网络、免疫细胞相关性网络图、相关性网络图、ggraph 网络图、cytoscape 视频网络、网络图 + 微生物丰度与基因相关性、corrgram 等。

9. 生存 / 临床 / 预测模型类

生存曲线（Kaplan-Meier）、连续 / 离散 / 双基因 / 联系变量（最优 cutoff）生存曲线、最佳分组生存分析、森林图、临床亚组分析、列线图（Nomogram）、ROC 曲线、多指标 ROC 曲线、生存 ROC 曲线、多时间点 / 多指标生存 ROC 曲线、timeROC、DCA 决策曲线、单因素 Cox、HRtable、smoothHR 非线性关联、免疫治疗预测等。

10. 基因组 / 突变 / 进化类

Circos、circos_R、OmicCircos、circlize 基因组图、复杂基因组图、染色体分布图、Manhattan 曼哈顿图、oncoplot、oncoprint、CNV、TMB、突变频谱、MutSigCV 泳道图、fishplot 肿瘤亚克隆、高端 / 半圆 / 系统发育树、基因家族进化树 + 表达谱聚类 + 多序列比对、多序列比对可视化、3D 基因组、IGV / phastCons / ChIP 与转录组叠加信号图、SNP Motif 等。

11. 微生物 / 群落 / 生态类

菌群分布图、病原真菌分布图、OTU/ASV 抽平柱状图、多样性指数箱型图-条形图-小提琴图-点图、稀释曲线（Rarefaction）、STAMP 图、Adonis（PERMANOVA）、MetaREM、WGCNA 寻找共表达与表型相关性等。

12. 环形 / 极坐标 / 组合 / 占比类

旭日图、饼图、3D 饼图、Krona 嵌套饼图、组合版环饼图、环状华夫图、南丁格尔玫瑰图、雷达图、花瓣雷达图、议会图、圆圈图、圈图、相关性圈图、车轱辘图、月亮图、凹凸图（Bump chart）、环形水平条形 + 柱状堆积、环状正负堆砌条形、离散型环状热图、组合版环状热图等。

13. 地图 / 地理空间类

ASIR 地图、流动的世界地图、组合地图与条形图、中国地图（ChinaMap）、个性化地图绘制、树状地图等。

14. 流向 / 集合 / 层级类

桑基图（sankey）、韦恩图（venn）、成比例 Venn 图、注释韦恩点图、UpSet 图、树形图（Treemap）、花瓣图、流向 / 状态转移可视化、树状地图等。

15. 单细胞类

单细胞 UMAP（Cell/Nature 复现）、Seurat 替换 UMAP 坐标、plot1cell 炫酷单细胞聚类图、单细胞差异基因对角线点图、单细胞差异基因 muscat、单细胞基因显著性检验及批量作图、markerGene、panCancer 小提琴图、免疫浸润（immune_infiltrationV2/V3）、使用 R2 展示高低免疫浸润等。

16. 机器学习 / 统计模型类

LASSO、SVM、随机森林、iCluster、cancerSubtype、WGCNA / WGCNA_fitting、广义线性混合模型、标准回归系数自动化计算、PLS-PM / 偏最小二乘结构方程、batch 批次效应评估与矫正、ROC/多指标 ROC、DCA、GEO2lncRNA、lncRNA 重注释、TCGA2table、count2TPM/FPKM 转换、GEO 数据库使用、pubmed/text 文本挖掘等。

17. 其他 / 综合 / 教学类

瀑布图、解剖图、曼哈顿图、面积图、词云图、流程图、棋局 / 棋盘矩阵、箭头图、轨道图、阴影图、黑白色块图、双轴图（twoAxis）、趋势分析 STEMbox、认识数据（数据画像）、高端个性化合图、ggplot2 系列定制图等。

二、每期图名清单（按 21 期展开，含文章链接）
第 1 期（20 个模板）

瀑布图、解剖图、曼哈顿图、哑铃图、离散型环状热图、多元回归方差分解热图、多层注释散点图、环状正负堆砌条形图、饼状热图、批量蜂窝图、环状相关性热图、CNS 级柱状图、箱线图分面、PCoA 分析、STAMP 图、分面条形图、生存分析、ASIR 地图、GO 富集分析网络图、组合版环状热图

 图片查看文章链接：https://mp.weixin.qq.com/s/iUXdkc-Eu8Taj4lFKahI1w

第 2 期（20 个模板）

堆砌金字塔图、旭日图、稀释曲线、小提琴图、OTU 抽平柱状图、多样性指数箱型图-条形图-小提琴图-点图、降维 PCA/PCOA/NMDS、OPLS-DA 与 PLS-DA、pcoa_boxplot（patchwork 拼图）、envfit_pcoa_pca_nmds_rda_cca、回归模型热图、多基因小提琴图、CNS 级热图、多重注释柱状图、多组合散点图、基因作用元件图、卡通版棒棒糖图、流动的世界地图、面积图、月亮图

 图片查看文章链接：https://mp.weixin.qq.com/s/ceA_SkdsLqMYjKrFnR9nNw

第 3 期（20 个模板）

棋局、趋势变化堆砌条形图、小提琴图分面、相关性热图、箭头图、正负分布条形图、拆分堆砌条形图、车轱辘图、堆砌金字塔图、多组配对箱线图、分组条形图、轨道图、3D 热图、成对差异分析、径向条形图、流程图、连线云雨图、配对箱线图、全能型箱线图、森林图

 图片查看文章链接：https://mp.weixin.qq.com/s/bgHpe3aqQ8MnKjytFqsbiQ

第 4 期（20 个模板）

旭日图、圆点柱状图、哑铃图、组合版热图、气泡图、配对三线表、散点图、环状华夫图、结构域与基因结构图、时间趋势变化散点图、注释韦恩点图、组合地图与条形图、饼图、词云图、点+误差棒、偏差图、蝶形条形图 & 蝶形柱状堆积图、豆荚图+显著性+误差棒、花瓣图、环形热图

 图片查看文章链接：https://mp.weixin.qq.com/s/8wZ_X5v_h2rUIzsY9wWTZQ

第 5 期（20 个模板）

环形水平条形图+柱状堆积图、环形柱状图+误差棒+显著性+分组标签、环状柱形图 & 南丁格尔玫瑰图、绝对量柱状堆积图+环形图、环状柱状堆积图、雷达图、生病率之比、热图+显著性+间隔+注释+柱状图、热图+重要值计算及标记+解释度条形图、热图+柱状堆积图、热图绘制并添加注释、网络图+微生物丰度与基因相关性、线性相关性分析、箱线图+点线图+显著性+分组、箱线图+组内显著性+组内线性回归、议会图、凹凸图 Bump chart、系统发育树循环、半圆进化树、棒棒糖图 & 哑铃图

 图片查看文章链接：https://mp.weixin.qq.com/s/tW2Q7w2EX0yC1t2AI7cEng

第 6 期（20 个模板）

并列柱状堆积图+误差线+显著性、不同组散点+回归曲线+多项式拟合、不一样的点线图、成比例 Venn 图、带误差线的柱状堆积图、单列热图+文字注释+显著性+箭头注释、多序列比对及可视化、多组火山图、多层分组热图、变化趋势气泡图、分类水平聚类分析+注释、分组分面条形图、分组散点&箱线图&小提琴图&条形图、分组散点图、分组箱线图、分组直方图、火山图、3D 饼图、bulk 数据处理、EnhancedVolcano 火山图

 图片查看文章链接：https://mp.weixin.qq.com/s/nndShux4NclKgb3YgRW-tg

第 7 期（20 个模板）

好看阴影图、ggheatmap 热图、ggplot2 双侧柱状图、ggplot2 扇形图、ggplot 黑白色块图、ggplot 点线图、ggplot 结合 pheatmap、ggplot split 小提琴图、ggplot 分组柱状图-箱线图-小提琴图+趋势线、Krona 嵌套饼图、plot1cell 单细胞聚类图、病原真菌分布图、pyscenic TF-target 网络、棒棒糖图、标注感兴趣基因热图、单细胞差异基因对角线点图、单细胞差异基因 muscat、单细胞基因显著性检验及批量作图、分组不同色彩 GO 柱状图、复现 Cell 柱状图加注释

 图片查看文章链接：https://mp.weixin.qq.com/s/eXInqdk3_lGVFMncnCtd2g

第 8 期（20 个模板）

复现 Cell 双向柱状图加注释、复现 Nature 单细胞 UMAP、柱状误差点线图、富集分析柱状图（通路加到柱子上）、离散型热图、配对连线小提琴图、配对箱线图、配对云雨图、相互作用 dot、行列注释热图、学习 NC 代码 IPA 富集旗袍图、柱状图结合蜂群散点图、3D 基因组、广义线性混合模型图、生存曲线、基因家族成员进化树+表达谱聚类+多序列比对、最佳分组生存分析、Ternary 三元图、花瓣雷达图、临床亚组分析

 图片查看文章链接：https://mp.weixin.qq.com/s/3ox9flYagAtcExafEi2pTw

第 9 期（20 个模板）

热图（相关性/基因表达变化聚类）、DAVIDkappa、桑基图+气泡图展示富集、基因功能富集分析泡泡图、正负分布条形图、circos、基因表达量箱线图、GSEA、GSEA_Java、WGCNA、WGCNA_fitting、WGCNA_heatmap、MetaREM、oncoplot、Lollipop、树状地图、mortalityV2、TCGA2table、count2TPM、ROC

 图片查看文章链接：https://mp.weixin.qq.com/s/zS36fj2ceht5YEZOZH04Iw

第 10 期（20 个模板）

sankey、circos_R、tSNE、color、map、nomogram、特殊主题热图、lasso、ID_table、DCA、count2FPKM、count2FPKMv2、batch 批次效应评估与矫正、nSurv、correlationV2、PCA、bar、组合版环饼图、lineage、GEO2lncRNA

 图片查看文章链接：https://mp.weixin.qq.com/s/2Pb7ZtbrEitum_y1IBVYCA

第 11 期（20 个模板）

oncoprint、Manhattan、profile、iCluster、pathway_sup、HRtable、Adonis、AS_3rd、热图、ChinaMap、TMB、GOplot、PPImodule、cytoscape_video、panCancer_violin、immune_infiltrationV2、immune_infiltrationV3、profile_1bw、lncRNAreannotation、分裂条形图

 图片查看文章链接：https://mp.weixin.qq.com/s/ZjB07s4KVk9g-jTo1Wy18g

第 12 期（20 个模板）

柱状图、GSEA_clusterProfiler、GSVA、twoAxis、pubmedMiningV2、textMining、triangle、SVM、单因素 Cox、phastCons、friends、PCA 分析、cancerSubtype、mutationEvents、ssGSEA、groupMethylation、batchCorrelation、OmicCircos、bubble_volcano、corrgram

 图片查看文章链接：https://mp.weixin.qq.com/s/48JyA1bizBMYDJxIi3tSVA

第 13 期（20 个模板）

baseZoom、gganatogram、热图绘制、CNV、GOclustering、ggraph 网络图、单细胞 Seurat 替换 UMAP、配对云雨图、PLS-PM、偏最小二乘结构方程、标准回归系数自动化计算、随机森林模型分析、免疫细胞之间相关性网络图、箱线累积分布曲线图、IGVzoom 信号分布图、enrichment 转录因子间的 coupling、roast 检验、拟合模型 timeROC、转录结合位点 SNP Motif、fishplot 肿瘤亚克隆

 图片查看文章链接：https://mp.weixin.qq.com/s/bvowvKp4IxOHqO363XvJ9w

第 14 期（20 个模板）

染色体分布图 chromosome、圆圈图、临床亚组分析、cluster 热图、显著性标记小提琴图、免疫浸润与基因的相关性、细胞类群 UMAP、趋势分析 STEMbox、成对图计算免疫浸润得分、使用 R2 展示高低免疫浸润、多个基因和免疫浸润的相关性、双向柱状图、STEMheatmap、smoothHR 非线性关联、PCA 比较不同样本间基因表达模式、环状热图、GEO 数据库使用、WGCNA 寻找共表达与表型相关性、ROC 预测肿瘤、免疫治疗预测

 图片查看文章链接：https://mp.weixin.qq.com/s/jH5-2SlvvogHcy-nphDcPw

第 15 期（20 个模板）

GDSC 基因药物敏感性、扩增子绘制带进化树的物种柱状图、ChIP·ATAC·CUT&Tag heatmap、Chip 与转录组结果叠加图、GSEA 多组的富集分析、突变频谱探究、菌群分布图、markerGene、误差线点图、添加 p 值、组合进化树与热图、个性化注释热图、韦恩图 venn、PCA 图叠加密度曲线、聚类条形图、个性化绘制散点图、热图、循环箱线图、拟合曲线散点图、PCOA 分析

 图片查看文章链接：https://mp.weixin.qq.com/s/AMZjVPexVkztdmACi7yCtA

第 16 期（20 个模板）

高端系统发育树、离散型环状热图、IMATE 分析组合热图、堆积百分比柱状图、多组组合箱线图、泳道图 MutSigCV、基因表达时间序列聚类 ternaryCluster、相关性组合热图、高端个性化合图、个性化地图绘制、新版热图绘制、基因丰度图、区域热图绘制、circlize 基因组图绘制、显著性柱状图、华夫热图、复杂基因组图绘制、砖块热图与富集分析图、聚类热图绘制、热图注释叠加

 图片查看文章链接：https://mp.weixin.qq.com/s/IiFiOBRtDdeEh4Huau_owg

第 17 期（20 个模板）

简单整洁的热图、方差分析误差线图、热图与折线图组合、双轴柱状和折线图组合、个性化热图组合、临床相关性热图、排序箱线图、火山图、venn 图、UpSet 图、相关性散点图、相关性热图、相关性圈图、相关性网络图、雷达图、桑基图、饼图、差异箱线图、显著性气泡图、棒棒糖图

 图片查看文章链接：https://mp.weixin.qq.com/s/2C8UOYULrkhBVhiWyzIqPQ

第 18 期（20 个模板）

GO 圈图、KEGG 圈图、多 GSEA 富集图、连续变量生存曲线、联系变量生存曲线（最优 cutoff）、双基因生存曲线、森林图、列线图、多基因差异箱线图、ROC 曲线、多指标 ROC 曲线、生存 ROC 曲线、多时间点生存 ROC 曲线、多指标生存 ROC 曲线、PCA 图、三维 PCA 图、圈图、基因组可视化、树形图、多组差异箱线图

 图片查看文章链接：https://mp.weixin.qq.com/s/RkUd3qCofpaSWrl57ZEO_g

第 19 期（20 个模板）

认识数据、柱状图、显著性柱状图、堆积百分比柱状图、分类柱状图、排序箱线图、差异箱线图、多基因差异箱线图、多组差异箱线图、箱线图分面、小提琴图、多基因小提琴图、小提琴图分面、成对差异分析、气泡图、偏差图、热图、临床相关性热图、火山图、venn 图

 图片查看文章链接：https://mp.weixin.qq.com/s/U7NkYI_njcIKfYgXI6klzA

第 20 期（20 个模板）

UpSet 图、相关性散点图、相关性热图、相关性圈图、相关性网络图、雷达图、桑基图、饼图、显著性气泡图、棒棒糖图、GO 圈图、KEGG 圈图、多 GSEA 富集图、离散变量生存曲线、连续变量生存曲线、联系变量生存曲线（最优 cutoff）、双基因生存曲线、森林图、列线图、ROC 曲线

 图片查看文章链接：https://mp.weixin.qq.com/s/dOckTxFgMtLpVaEDeuAWRQ

第 21 期（11 个模板）

多指标 ROC 曲线、生存 ROC 曲线、多时间点生存 ROC 曲线、多指标生存 ROC 曲线、PCA 图、三维 PCA 图、圈图、基因组可视化、树形图、瀑布图、解剖图

 图片查看文章链接：https://mp.weixin.qq.com/s/5TooPWiN_kt9k4B-vV804Q

提示：公众号内回复【R语言】可获取配套 R 代码；《R 语言顶刊绘图 Skill》可让你"只说要画哪个图 + 数据在哪"就自动出图，详细教程见官方页：https://baozl.com/2026/10/30/r-%e8%af%ad%e8%a8%80%e7%bb%98%e5%9b%be%e4%bb%a3%e7%a0%81skill/
