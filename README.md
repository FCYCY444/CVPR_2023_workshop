# CVPR_2023_workshop

冠层图与叶面斑块研究相关 GitHub 参考代码合集，来源于四份清单：`开源代码清单(2).md`、`(3).md`、`(6).md` 和 `(7).md`。所有项目按原始 `owner/repo` 去重，严格按照原作者仓库名称建立单独文件夹。

**项目总计 27 个**：先前 13 个继续保留；本次两份新清单共 34 条、去重后 25 个项目，其中 11 个已在原仓库中，所以新增 **14 个**。新增项目中 **9 个**安排复制源码，**5 个**仅收录链接。当前预计合计为 **21 个源码项目、6 个仅链接项目**，实际导入结果以 [导入报告](./import-reports/workshop-additions-20261125.md) 为准。

> 这是单仓库源码快照及来源索引，**不是 GitHub 原生 Fork**。代码快照不包含上游提交历史、Git LFS 对象或外部权重下载。项目许可证彼此独立，须以各自目录中的原始声明为准。

## 去重后的项目目录

| 目录 | 对应方法或研究 | 研究方向 | 原始 GitHub 仓库 | 许可证 | 保存状态 |
| --- | --- | --- | --- | --- | --- |
| [slim-neck-by-gsconv](./slim-neck-by-gsconv/) | GSConv 轻量 Neck | 冠层图 | [alanli1997/slim-neck-by-gsconv](https://github.com/alanli1997/slim-neck-by-gsconv) | GPL-3.0 | 已复制源码 |
| [attention-module](./attention-module/) | CBAM 浅层注意力 | 冠层图 | [Jongchan/attention-module](https://github.com/Jongchan/attention-module) | MIT | 已复制源码 |
| [DroneDetectron2](./DroneDetectron2/) | Cascaded Zoom-in | 冠层图 | [akhilpm/DroneDetectron2](https://github.com/akhilpm/DroneDetectron2) | MIT | 已复制源码 |
| [ECANet](./ECANet/) | ECA 通道注意力 | 冠层图；叶面斑块 | [BangguWu/ECANet](https://github.com/BangguWu/ECANet) | MIT | 已复制源码 |
| [MobileViG](./MobileViG/) | MobileViG | 冠层图；叶面斑块 | [SLDGroup/MobileViG](https://github.com/SLDGroup/MobileViG) | Apache-2.0 | 已复制源码 |
| [CFDP](./CFDP/) | CFDP 通道剪枝 | 冠层图；叶面斑块 | [Skhaki18/CFDP](https://github.com/Skhaki18/CFDP) | MIT | 已复制源码 |
| [ultralytics](./ultralytics/) | SBAD 的 YOLO 框架 | 冠层图 | [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) | AGPL-3.0 | 已复制源码 |
| [AICITY_2023_Track5](./AICITY_2023_Track5/) | PRB-FPN | 冠层图 | [NYCU-AICVLab/AICITY_2023_Track5](https://github.com/NYCU-AICVLab/AICITY_2023_Track5) | 未发现仓库级许可证 | 仅原始链接 |
| [mmsegmentation](./mmsegmentation/) | MTLSegFormer 的 SegFormer 基础框架 | 叶面斑块 | [open-mmlab/mmsegmentation](https://github.com/open-mmlab/mmsegmentation) | Apache-2.0 | 已复制源码 |
| [RegSeg](./RegSeg/) | RegSeg | 叶面斑块 | [RolandGao/RegSeg](https://github.com/RolandGao/RegSeg) | MIT | 已复制源码 |
| [WS-DefSegNet](./WS-DefSegNet/) | WS-DefSegNet | 叶面斑块 | [ic-qialanqian/WS-DefSegNet](https://github.com/ic-qialanqian/WS-DefSegNet) | MIT | 已复制源码 |
| [compensation_learning](./compensation_learning/) | Compensation Learning | 叶面斑块 | [tnt-LUH/compensation_learning](https://github.com/tnt-LUH/compensation_learning) | Apache-2.0 | 已复制源码 |
| [cad](./cad/) | Content-Adaptive Downsampling | 冠层图；叶面斑块 | [visinf/cad](https://github.com/visinf/cad) | Apache-2.0 | 已复制源码 |
| [LocalizationLabelNoise](./LocalizationLabelNoise/) | A Novel Benchmark for Refinement of Noisy Localization Labels in Autolabeled Datasets for Object Detection | 冠层图 | [ifnspaml/LocalizationLabelNoise](https://github.com/ifnspaml/LocalizationLabelNoise) | MIT | 待复制源码 |
| [Synthetic-Mushroom-Dataset](./Synthetic-Mushroom-Dataset/) | A Realistic Synthetic Mushroom Scenes Dataset | 冠层图；叶面斑块 | [dafniana/Synthetic-Mushroom-Dataset](https://github.com/dafniana/Synthetic-Mushroom-Dataset) | 仓库级许可未核实 | 仅保存链接 |
| [L-CRP](./L-CRP/) | Revealing Hidden Context Bias in Segmentation and Object Detection through Concept-specific Explanations | 冠层图；叶面斑块 | [maxdreyer/L-CRP](https://github.com/maxdreyer/L-CRP) | 仓库级许可未核实 | 仅保存链接 |
| [EVFR](./EVFR/) | Exploring Video Frame Redundancies for Efficient Data Sampling and Annotation in Instance Segmentation | 冠层图；叶面斑块 | [jihun-yoon/EVFR](https://github.com/jihun-yoon/EVFR) | MIT（上游 LICENSE 文件内容不完整） | 待复制源码 |
| [WEDGE](./WEDGE/) | WEDGE: A multi-weather autonomous driving dataset built from generative vision-language models | 冠层图 | [infernolia/WEDGE](https://github.com/infernolia/WEDGE) | 代码 GPL-3.0；数据 CC BY-NC-SA 4.0 | 待复制源码 |
| [RepRFN](./RepRFN/) | Reparameterized Residual Feature Network For Lightweight Image Super-Resolution | 冠层图；叶面斑块 | [laonafahaodange/RepRFN](https://github.com/laonafahaodange/RepRFN) | MIT | 待复制源码 |
| [flight-net](./flight-net/) | FLIGHT Mode On: A Feather-Light Network for Low-Light Image Enhancement | 冠层图；叶面斑块 | [aselsan-research-imaging-team/flight-net](https://github.com/aselsan-research-imaging-team/flight-net) | CC BY-NC-SA 4.0（非商业限制） | 待复制源码 |
| [zutis](./zutis/) | Zero-shot Unsupervised Transfer Instance Segmentation | 叶面斑块 | [NoelShin/zutis](https://github.com/NoelShin/zutis) | MIT | 待复制源码 |
| [Oneshot-Part-CellSegmentation](./Oneshot-Part-CellSegmentation/) | One-shot and Partially-Supervised Cell Image Segmentation Using Small Visual Prompt | 叶面斑块 | [usagisukisuki/Oneshot-Part-CellSegmentation](https://github.com/usagisukisuki/Oneshot-Part-CellSegmentation) | 仓库级许可未核实 | 仅保存链接 |
| [rip_currents](./rip_currents/) | Rip Current Segmentation: A Novel Benchmark and YOLOv8 Baseline Results | 叶面斑块 | [Irikos/rip_currents](https://github.com/Irikos/rip_currents) | 仓库级许可未核实 | 仅保存链接 |
| [namedmask](./namedmask/) | NamedMask: Distilling Segmenters from Complementary Foundation Models | 叶面斑块 | [NoelShin/namedmask](https://github.com/NoelShin/namedmask) | MIT | 待复制源码 |
| [CONFETI](./CONFETI/) | Contrast, Stylize and Adapt: Unsupervised Contrastive Learning Framework for Domain Adaptive Semantic Segmentation | 叶面斑块 | [cxa9264/CONFETI](https://github.com/cxa9264/CONFETI) | 仓库级许可未核实 | 仅保存链接 |
| [Open-set-M2F](./Open-set-M2F/) | On Advantages of Mask-level Recognition for Outlier-aware Segmentation | 叶面斑块 | [matejgrcic/Open-set-M2F](https://github.com/matejgrcic/Open-set-M2F) | MIT（部分依赖采用独立许可证） | 待复制源码 |
| [PerfPredRecV2](./PerfPredRecV2/) | Improvements to Image Reconstruction-Based Performance Prediction for Semantic Segmentation in Highly Automated Driving | 叶面斑块 | [ifnspaml/PerfPredRecV2](https://github.com/ifnspaml/PerfPredRecV2) | GPL-3.0（上游 README 明确声明；仓库无独立 LICENSE） | 待复制源码 |

## 许可及内容边界

- `Synthetic-Mushroom-Dataset`、`L-CRP`、`Oneshot-Part-CellSegmentation`、`rip_currents`、`CONFETI` 的再分发许可暂未核实，**仅保存来源链接**，不复制源码。
- `AICITY_2023_Track5` 此前也是仅链接项目，保持原状。
- `WEDGE` 项目代码采用 GPL-3.0；原始数据集另标明 CC BY-NC-SA 4.0，本次**只复制 Code/ 和仓库原始说明、许可证**，不镜像 Dataset/ 和网站素材。
- `flight-net` 适用 **CC BY-NC-SA 4.0**，存在署名、非商业及相同方式共享条件。
- `EVFR` 原仓库 README 明确标注 MIT，但 LICENSE 文本不完整；保留原文件及来源信息，后续使用前建议确认完整许可文本。
- `PerfPredRecV2` README 明确声明 **GPL-3.0**，但上游缺少独立 LICENSE 文件。分发副本将添加标准 GPL-3.0 许可证文本并标注来源。
- 各项目第三方依赖、预训练权重及数据集可能适用不同许可，不应仅凭顶层许可证判断使用权限。
- 两份清单中的 Windows 路径为计划下载位置；本次只写入 GitHub，不会修改本地计算机文件。

机器可读的去重索引见 [projects.csv](./projects.csv)；本次新增源码的目标清单见 [workshop-additions-import.tsv](./.github/workshop-additions-import.tsv)。

## 待核实的补充来源（不算在 27 个项目内）

- [few-shot-Video-Data-Sampling](https://github.com/aboah1994/few-shot-Video-Data-Sampling) — 清单标记源仓库 404，未自动复制
- [score_sde_pytorch](https://github.com/yang-song/score_sde_pytorch) — SANO 论文引用的基础实现，非该论文已核实完整源码
- [NVD 数据入口](https://nvd.ltu-ai.dev) — 数据集项目页，未核实完整检测实现
