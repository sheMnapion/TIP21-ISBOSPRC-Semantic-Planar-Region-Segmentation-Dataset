# TIP21-ISBOSPRC-Semantic-Planar-Region-Segmentation-Dataset
This is the repository containing the dataset for the task of Semantic Planar Region
Segmentation proposed in the paper Image Stitching Based On Semantic Planar Region
Consensus (abbreviated as ISBOSPRC). 
- The dataset images (1005 in total) are from 
  [ADE20k](https://groups.csail.mit.edu/vision/datasets/ADE20K/)
  and can be accessed similarly as in this 
  [repository](https://www.github.com/CSAILVision/semantic-segmentation-pytorch) by using training_sprs.odgt 
  and validation_sprs.odgt.
  We manually relabel the images to contain the semantic planar region segmentation information.
- Download the repository to obtain the whole dataset.
- A slightly larger dataset with an additional 150+ images will be updated soon.
## Reference

If you find the dataset useful, please cite the following paper:

A. Li, J. Guo and Y. Guo, "Image Stitching Based on Semantic Planar Region Consensus," 
in IEEE Transactions on Image Processing, vol. 30, pp. 5545-5558, 2021, 
doi: 10.1109/TIP.2021.3086079.

  @ARTICLE{9448359,
    author={Li, Aocheng and Guo, Jie and Guo, Yanwen},
    journal={IEEE Transactions on Image Processing}, 
    title={Image Stitching Based on Semantic Planar Region Consensus}, 
    year={2021},
    volume={30},
    number={},
    pages={5545-5558},
    doi={10.1109/TIP.2021.3086079}
  }