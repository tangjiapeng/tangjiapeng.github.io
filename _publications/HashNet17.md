---
title: "HashNet: Deep Learning to Hash by Continuation"
collection: publications
permalink: /publications/HashNet17
venue: "International Conference on Computer Vision (ICCV) 2017"
date: 2017-10-21
citation: '<b>Zhangjie Cao</b>, Mingsheng Long, Jianmin Wang, Philip S. Yu. <i>International Conference on Computer Vision.</i> <b>ICCV 2017</b>.'
---

[[Conference Version]](http://caozhangjie.github.io/files/hashnet17.pdf)
[[Arxiv]](https://arxiv.org/abs/1702.00758)
[[Code]](https://github.com/thuml/HashNet)
[[Poster]](http://caozhangjie.github.io/files/HashNet17_poster.pdf)

## Abstract
Learning to hash has been widely applied to approximate nearest neighbor search for large-scale multimedia retrieval, due to its computation efficiency and retrieval quality. Deep learning to hash, which improves retrieval quality by end-to-end representation learning and hash encoding, has received increasing attention recently. Subject to the ill-posed gradient difficulty in the optimization with sign activations, existing deep learning to hash methods need to first learn continuous representations and then generate binary hash codes in a separated binarization step, which suffer from substantial loss of retrieval quality. This work presents HashNet, a novel deep architecture for deep learning to hash by continuation method with convergence guarantees, which learns exactly binary hash codes from imbalanced similarity data. The key idea is to attack the ill-posed gradient problem in optimizing deep networks with non-smooth binary activations by continuation method, in which we begin from learning an easier network with smoothed activation function and let it evolve during the training, until it eventually goes back to being the original, difficult to optimize, deep network with the sign activation function. Comprehensive empirical evidence shows that HashNet can generate exactly binary hash codes and yield state-of-the-art multimedia retrieval performance on standard benchmarks.
