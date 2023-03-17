# SharpContour: A Contour-based Boundary Refinement Approach for Efficient and Accurate Instance Segmentation (CVPR2022)

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) 
<a href="https://pytorch.org/get-started/locally/"><img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white"></a>

## [Project Page](https://xyzhang17.github.io/SharpContour/) | [Paper](https://arxiv.org/abs/2203.13312) 

This is the official PyTorch implementation of [SharpContour]().


we will release the code in April.



## A Gentle Introduction

![](/figs/teaser.png)

Excellent performance has been achieved on instance segmentation but the quality on the boundary area remains unsatisfactory, which leads to a rising attention on boundary refinement. For practical use, an ideal post-processing refinement scheme are required to be accurate, generic and efficient. However, most of existing approaches propose pixel-wise refinement, which either introduce a massive computation cost or design specifically for different backbone models. Contour-based models are efficient and generic to be incorporated with any existing segmentation methods, but they often generate over-smoothed contour and tend to fail on corner areas. In this paper, we propose an efficient contour-based boundary refinement approach, named SharpContour, to tackle the segmentation of boundary area. We design a novel contour evolution process together with an Instance-aware Point Classifier. Our method deforms the contour iteratively by updating offsets in a discrete manner. Differing from existing contour evolution methods, SharpContour estimates each offset more independently so that it predicts much sharper and accurate contours. Notably, our method is generic to seamlessly work with diverse existing models with a small computational cost. Experiments show that SharpContour achieves competitive gains whilst preserving high efficiency. 


## Citation

If you use SharpContour in your research, please consider the following BibTeX entry and giving us a star🌟!

```BibTeX
@inproceedings{zhu2022sharpcontour,
  title={SharpContour: a contour-based boundary refinement approach for efficient and accurate instance segmentation},
  author={Zhu, Chenming and Zhang, Xuanye and Li, Yanran and Qiu, Liangdong and Han, Kai and Han, Xiaoguang},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={4392--4401},
  year={2022}
}
```

