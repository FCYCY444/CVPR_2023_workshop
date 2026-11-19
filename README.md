# CVPR_2023_workshop

冠层图与叶面斑块研究方向相关 GitHub 参考代码汇总仓库。数据来自两份上传的 **开源代码清单(2).md** 与 **开源代码清单(3).md**。

**去重统计：** 两份清单共有 14 个仓库条目，其中 `SLDGroup/MobileViG` 跨方向重复 1 次，合并后有 **13 个唯一仓库**。

> 此处按原仓库名集中保存多个项目的代码快照，不是 GitHub 官方意义的 Fork；不包含上游原始 Git 提交历史。

## 项目索引

| 目录 | 研究方法 | 方向 | 原始 GitHub 仓库 | 许可证 | 保存方式 |
| --- | --- | --- | --- | --- | --- |
| [slim-neck-by-gsconv](./slim-neck-by-gsconv/) | GSConv 轻量 Neck | 冠层图 | [alanli1997/slim-neck-by-gsconv](https://github.com/alanli1997/slim-neck-by-gsconv) | GPL-3.0 | 公开源码快照（导入中） |
| [attention-module](./attention-module/) | CBAM 浅层注意力 | 冠层图 | [Jongchan/attention-module](https://github.com/Jongchan/attention-module) | MIT | 公开源码快照（导入中） |
| [DroneDetectron2](./DroneDetectron2/) | Cascaded Zoom-in | 冠层图 | [akhilpm/DroneDetectron2](https://github.com/akhilpm/DroneDetectron2) | MIT | 公开源码快照（导入中） |
| [ECANet](./ECANet/) | ECA 通道注意力 | 冠层图 | [BangguWu/ECANet](https://github.com/BangguWu/ECANet) | MIT | 公开源码快照（导入中） |
| [MobileViG](./MobileViG/) | MobileViG | 冠层图；叶面斑块 | [SLDGroup/MobileViG](https://github.com/SLDGroup/MobileViG) | Apache-2.0 | 公开源码快照（导入中） |
| [CFDP](./CFDP/) | CFDP 通道剪枝 | 冠层图 | [Skhaki18/CFDP](https://github.com/Skhaki18/CFDP) | MIT | 公开源码快照（导入中） |
| [ultralytics](./ultralytics/) | SBAD 的 YOLO 框架 | 冠层图 | [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) | AGPL-3.0 | 公开源码快照（导入中） |
| [AICITY_2023_Track5](./AICITY_2023_Track5/) | PRB-FPN | 冠层图 | [NYCU-AICVLab/AICITY_2023_Track5](https://github.com/NYCU-AICVLab/AICITY_2023_Track5) | 未发现仓库级许可证 | 仅原始链接 |
| [mmsegmentation](./mmsegmentation/) | MTLSegFormer 的 SegFormer 基础框架 | 叶面斑块 | [open-mmlab/mmsegmentation](https://github.com/open-mmlab/mmsegmentation) | Apache-2.0 | 公开源码快照（导入中） |
| [RegSeg](./RegSeg/) | RegSeg | 叶面斑块 | [RolandGao/RegSeg](https://github.com/RolandGao/RegSeg) | MIT | 公开源码快照（导入中） |
| [WS-DefSegNet](./WS-DefSegNet/) | WS-DefSegNet | 叶面斑块 | [ic-qialanqian/WS-DefSegNet](https://github.com/ic-qialanqian/WS-DefSegNet) | MIT | 公开源码快照（导入中） |
| [compensation_learning](./compensation_learning/) | Compensation Learning | 叶面斑块 | [tnt-LUH/compensation_learning](https://github.com/tnt-LUH/compensation_learning) | Apache-2.0 | 公开源码快照（导入中） |
| [cad](./cad/) | Content-Adaptive Downsampling | 叶面斑块 | [visinf/cad](https://github.com/visinf/cad) | Apache-2.0 | 公开源码快照（导入中） |

## 说明

- 每个项目只保存一份，`MobileViG` 同时服务于两个方向。
- 每个文件夹的 `SOURCE.md` 记录原始地址、方法、文件入口、许可证、处理状态。
- `AICITY_2023_Track5` 未发现仓库级许可证：此处仅保存原始链接，**不在公开仓库重新分发源码**。
- 其他项目源代码导入时保留各自原文件、版权声明和许可证，并遵守 GPL、AGPL、MIT、Apache 等相应的再分发条件。
- 导入为默认分支浅克隆快照，不包含原始提交历史。大于 GitHub 文件大小限制的文件可能被省略；Git LFS 指针不等于模型权重文件。
- 来源清单中的 Windows 本地路径属于计划保存路径；本仓库没有访问本机磁盘或代为回填本地论文。
- 导入记录见 [import-reports/latest-import.md](./import-reports/latest-import.md)（源码导入后生成），可机读目录见 [projects.csv](./projects.csv)。
