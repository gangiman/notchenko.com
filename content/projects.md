---
title: "Projects"
author: "Alexandr Notchenko"
date: 2023-10-15
---

## Graph-Convolutional systems for Inverse Graphics

This architecture is able to learn topological and other latent features of spatial objects and condition distribution of graphical parametres on them, thus enabling reconstruction.

[code is not available publicly at the moment], [preprint in preparation]

### Selected References
1. Wu, Jiajun, Joshua B. Tenenbaum, and Pushmeet Kohli. "Neural scene de-rendering." _In Proc. CVPR, vol. 2. 2017._
2. Ganin, Yaroslav, Tejas Kulkarni, Igor Babuschkin, S. M. Eslami, and Oriol Vinyals. "Synthesizing Programs for Images using Reinforced Adversarial Learning." _ICML 2018 NAMPI Workshop. 2018._
3. Hua, Binh-Son, Minh-Khoi Tran, and Sai-Kit Yeung. "Pointwise convolutional neural networks." _In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pp. 984-993. 2018._
4. Kool, W. W. M., and M. Welling. "Attention Solves Your TSP." _arXiv preprint arXiv:1803.08475. 2018._
5. Vaswani, Ashish, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. "Attention is all you need." _In Advances in Neural Information Processing Systems, pp. 5998-6008. 2017._


**Status**: Work in progress


<img style="width:inherit;" src="/images/ig_pipeline_for_2d.png"></img>
&nbsp;&nbsp;&nbsp;
<img style="width:inherit;" src="/images/ig_results.png"></img>

----------------

## Sparse 3D Convolutional Neural Networks for Large-Scale Shape Retrieval

The goal of the research was to combining two ideas:

1. 3D Sparse Convolutional Neural Networks
2. metric learning (particulary triplet learning)

to solve shape retieval problem.


[[code](https://github.com/gangiman/PySparseConvNet/)] [[arxiv](https://arxiv.org/abs/1611.09159)] [[publication](https://link.springer.com/chapter/10.1007/978-3-319-73013-4_23)]

### Selected References
1. A. M. Bronstein, M. M. Bronstein, L. J. Guibas, and M. Ovsjanikov. Shape google: Geometric words and expressions for invariant shape retrieval. _ACM Transactions on Graphics (TOG), 30(1):1, 2011._
2. B. Graham. Spatially-sparse convolutional neural networks. _arXiv preprint arXiv:1409.6070, 2014._
3. V. Hegde and R. Zadeh. Fusionnet: 3d object classification using multiple data representations. _arXiv preprint arXiv:1607.05695, 2016._
4. E. Hoffer and N. Ailon. Deep metric learning using triplet network. _In International Workshop on Similarity-Based Pattern Recognition, pages 84–92. Springer, 2015._
5. E. Johns, S. Leutenegger, and A. J. Davison. Pairwise decomposition of image sequences for active multi-view recognition. _arXiv preprint arXiv:1605.08359, 2016._
6. D. Maturana and S. Scherer. Voxnet: A 3d convolutional neural network for realtime object recognition. _In Intelligent Robots and Systems (IROS), 2015 IEEE/RSJ International Conference on, pages 922–928. IEEE, 2015._
7. N. Sedaghat, M. Zolfaghari, and T. Brox. Orientation-boosted voxel nets for 3d object recognition. _arXiv preprint arXiv:1604.03351, 2016._
8. H. Su, S. Maji, E. Kalogerakis, and E. G. Learned-Miller. Multi-view convolutional neural networks for 3d shape recognition. _In Proc. ICCV, 2015._
9. J. Wang, Y. Song, T. Leung, C. Rosenberg, J. Wang, J. Philbin, B. Chen, and Y. Wu. Learning fine-grained image similarity with deep ranking. _In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 1386–1393, 2014._
10. Z. Wu, S. Song, A. Khosla, F. Yu, L. Zhang, X. Tang, and J. Xiao. 3d shapenets: A deep representation for volumetric shapes. _In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 1912–1920, 2015._

**Status**: Finished


<img style="width:inherit;" src="/images/scn_activations.png"></img>
&nbsp;&nbsp;&nbsp;
<img style="width:inherit;" src="/images/scn_conv.png"></img>
&nbsp;&nbsp;&nbsp;
<img style="width:inherit;" src="/images/scn_conv_pool.png"></img>