# 九点巡回的完整证明森林

六份文件是同一个 xz 流的连续分段，不是各自可解压的文件。下载该目录后按文件名顺序拼接：
```sh
sha256sum -c SHA256SUMS
cat n9.boxes.xz.part-* > n9.boxes.xz
```
把拼接后的文件放进 [验证器压缩包](../cubic-tsp-cube-multiscale-supplement.zip) 的解压目录，运行 `bash reproduce.sh`。证明稿见 [中文预印本](../../paper.pdf)。
