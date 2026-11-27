# 三维单位立方体的立方巡回 · 复现材料

论文只在[同一份 PDF](../paper.pdf)中阅读；下面按章节列出源文件和证书。ZIP 内文件及校验值保留原样。

| 章节 | 页码 | 源码和证书 |
| --- | ---: | --- |
| 1. 基础界、封闭巡回构造与四至六点 | 2 | [下载](cubic-tsp-cube-supplement.zip) |
| 2. 联合换边与七、八点定理 | 9 | [下载](cubic-tsp-cube-joint-supplement.zip) |
| 3. 多尺度换边与九点定理 | 20 | [下载](cubic-tsp-cube-multiscale-supplement.zip) |
| 4. 全局 16.10 上界、局部重排与删点 | 32 | [下载](cubic-tsp-cube-reordering-supplement.zip) |
| 5. 十点定理与刚性 | 46 | [下载](cubic-tsp-cube-ten-points-source.zip) |
| 6. 任意点数下的投影、角簇与覆盖球 | 59 | [下载](cubic-tsp-cube-regions-source.zip) |
| 7. 十一点定理、加权直径球与稠密性 | 71 | [下载](cubic-tsp-cube-eleven-points-source.zip) |

旧版说明中提到的独立 PDF 或旧仓库路径，可从[原始快照](https://github.com/RACErace/research-preprints/tree/c581f547663df38a0e01e4edf5f1d9304e2f44ec)查看。

## 大型证书

- 第三章九点森林：[分卷和校验](cubic-tsp-cube-multiscale-data/)。
- 第四章带余量森林：[分卷和校验](cubic-tsp-cube-reordering-data/)。第五章的旧脚本以分卷目录的上一级为参数：先解压源码包，再运行 `bash reconstruct.sh /绝对路径/research-preprints/research/cubic-tour/materials`。脚本、分卷及摘要均未改动。
- 第七章十一点森林可由源码包从头生成，再用其中的独立检查器核验；无需下载上述分卷。
