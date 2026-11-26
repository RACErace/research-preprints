# Mathematical research preprints

A single archive for research preprints and their reproducibility materials. The manuscripts are publicly available working papers, not peer-reviewed publications.

| Preprint | What it establishes | Editable source, code, and certificates |
| --- | --- | --- |
| [Certified lower bounds for eight, nine and ten cylinders touching a unit sphere](cylinders-lower-bounds.pdf) | Gives exact configurations with strictly larger lower bounds for the three common radii. The eight-ring insertion question remains open. | [Cylinder packing supplement](cylinders-lower-bounds-supplement.zip) |
| [The unique spectrally closest competitor to a balanced complete tripartite graph](closest-tripartite-graph.pdf) | Solves Conjecture 20 in both spectral distances for all n ≥ 3, including disconnected competitors. | [Closest-tripartite supplement](closest-tripartite-supplement.zip) |
| [A certified A7 minimizer for two-site Lennard–Jones crystals](A7-Lennard-Jones.pdf) | At volume 269/250 per particle, A7 is uniquely optimal in the full two-site periodic class; a three-site structure has lower energy. | [A7 supplement](a7-supplement.zip) |
| [Sharp adjacency spectral-tail bounds at rank six](spectral-rank-six.pdf) | Answers Problem 21 of Jovanović–Sedlar–Škrekovski and derives sharp trimmed-spectrum bounds. All closest competitors to the balanced tripartite graph have adjacency rank at most five. This is the rank reduction used in the Conjecture 20 paper above. | [Spectral rank supplement](spectral-rank-supplement.zip) |
| [Sharp replacements for three Graffiti.pc inequalities](three-graffiti-inequalities.pdf) | Refutes *Written on the Wall II* #138, #255 and #256 and supplies sharp universal replacements. | [Graffiti supplement](graffiti-supplement.zip) |
| [A weighted Bernoulli inequality for at most ten positive weights](weighted-bernoulli-ten.pdf) | Proves the Milojević–Sudakov inequality for the full real interval 0 ≤ p ≤ 1/3 when there are at most ten positive weights. Arbitrary support is not settled. | [Bernoulli supplement](bernoulli-supplement.zip) |

Each supplement contains a README with replay commands. To check the published downloads, run `sha256sum -c SHA256SUMS` from the repository root. See the [literature and priority checks](NOVELTY.md) for exact source statements and the scope of each result.

## 中文索引

1. **A7 晶格**：在指定密度下证明 A7 是所有双点周期结构中唯一最优的；并给出能量更低的三点周期结构。
2. **谱图秩**：完整回答原论文第 21 题，并给出两个最优的截尾谱界，是第 20 条证明所用的秩归约。
3. **Graffiti.pc**：三个猜想各有明确反例，并给出了不能再提高的通用系数。
4. **Bernoulli 不等式**：覆盖同一概率区间内的所有实数参数，但只证明最多十个正权重的情况。

5. **谱图最近邻**：完整解决第 20 条猜想。对每个 n ≥ 3，两种距离下都是同一张图唯一最接近。

6. **圆柱密堆积**：给出 8、9、10 根等半径圆柱围住单位球的精确构型，分别证明最大半径大于 0.70215、0.61196 和 0.54515。

各篇 PDF、可编辑原稿、证明代码和复现说明均可从上表下载。
