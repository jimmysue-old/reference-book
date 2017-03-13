- [Markuš N, Gogić I, Pandžić I S, et al. Memory-Efficient Global Refinement of Decision-Tree Ensembles and its Application to Face Alignment[J]. arXiv preprint arXiv:1702.08481, 2017.](https://arxiv.org/pdf/1702.08481.pdf)
> However, we
> argue that their basic method is not applicable in many practical
> scenarios due to large memory requirements. This paper
> shows how this issue can be solved through the use of **quantization**
> and **architectural changes** of the predictor that maps
> decision tree-derived encodings to the desired output.

通过量化和加入回归中间层来减小模型内存。 

- [Dapogny A, Bailly K, Dubuisson S. Face Alignment with Cascaded Semi-Parametric Deep Greedy Neural Forests[J]. arXiv preprint arXiv:1703.01597, 2017.](https://arxiv.org/pdf/1703.01597.pdf)
> In this paper, we propose a semi-parametric cascade
> that first aligns a parametric shape, then captures more finegrained
> deformations of an explicit shape
 结合回归形状参数和坐标（显式形状）来进一步提高FA的精度。这么做我才是形状模型的参数能够表达的形状精度有限，毕竟形状模型在训练的时候是有方差截断的。实际经验表明对于闭眼（特别是一睁一闭）张嘴大表情等难以控制。
