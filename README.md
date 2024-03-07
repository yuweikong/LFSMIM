# LFSMIM

This is the official pytorch implementation of [LFSMIM: A Low-Frequency Spectral Masked Image Modeling Method for Hyperspectral Image Classification](https://ieeexplore.ieee.org/abstract/document/10416647) (IEEE GRSL).

The current version supports Python>=3.8.10, CUDA>=11.3.0 and PyTorch>=1.11.0, but it should work fine with lower versions of CUDA and PyTorch. 

<img src="img/LFSMIM.png" width="900px"/>
  
<img src="img/VIT.png" width="900px"/>

## Introduction
Masked image modeling (MIM) has made significant advancements across various fields in recent years. Previous research in the hyperspectral (HS) domain often utilizes conventional Transformers to model spectral sequences, overlooking the impact of local details on HS image classification. Furthermore, training models using raw image features as reconstruction targets entail significant challenges. In this study, we specifically focus on the reconstruction targets and feature modeling capabilities of the Vision Transformer (ViT) to address the limitations of MIM methods in the HS domain. As a proposed solution, we introduce a novel and effective method called LFSMIM, which incorporates two key strategies: 1) filtering out high-frequency components from the reconstruction target to mitigate the network’s sensitivity to noise and 2) enhancing the local and global modeling capabilities of the ViT to effectively capture weakened texture details and exploit global spectral features.
 
## Citation

If you use LFSMIM in an academic work, please cite:

```
@article{chen2024lfsmim,
  title={LFSMIM: A Low-Frequency Spectral Masked Image Modeling Method for Hyperspectral Image Classification},
  author={Chen, Yuhan and Yan, Qingyun},
  journal={IEEE Geoscience and Remote Sensing Letters},
  year={2024},
  publisher={IEEE}
}
```

## Contact

201983350015@nuist.edu.cn

