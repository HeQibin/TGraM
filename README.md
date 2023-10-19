# TGraM

> [**Multi-Object Tracking in Satellite Videos with Graph-Based Multi-Task Modeling**](https://ieeexplore.ieee.org/document/9715124),            
> Qibin He, Xian Sun, Zhiyuan Yan, Beibei Li, Kun Fu       

<p align='center'>
  <img src='assets/tgram_fig.bmp' width="800px">
</p>


## Abstract

Recently, satellite video has become an emerging means of earth observation, providing the possibility of tracking moving objects. However, the existing multi-object trackers are commonly designed for natural scenes without considering the characteristics of remotely sensed data. In addition, most trackers are composed of two independent stages of detection and re-identification (ReID), which means that they cannot be mutually promoted. To this end, we propose an end-to-end online framework, which is called TGraM, for multi-object tracking in satellite videos. It models multi-object tracking as a graph information reasoning procedure from the multi-task learning perspective. Specifically, a graph-based spatiotemporal reasoning module is presented to mine the potential high-order correlations between video frames. Furthermore, considering the inconsistency of optimization objectives between detection and ReID, a multi-task gradient adversarial learning strategy is designed to regularize each task-specific network. Additionally, aiming at the data scarcity in this field, a large-scale and high-resolution Jilin1 satellite video dataset for multi-object tracking (AIR-MOT) is built for the experiments. Compared with state-of-the-art multi-object trackers, TGraM achieves efficient collaborative learning between detection and ReID, improving the tracking accuracy by 1.2 MOTA. 

## Dataset

* **AIR-MOT**

  The self-built AIR-MOT dataset can be downloaded from https://drive.google.com/drive/folders/1zfvhKOGmvZVWUgbE8l3LL9uude0bBg-O?usp=sharing. We have released 70 videos, and the rest will be available soon.
  
  
## Paper

Please cite our paper if you find the code or dataset useful for your research.

```
@ARTICLE{He-TGRS-TGraM-2022,
  author={Q. {He} and X. {Sun} and Z. {Yan} and B. {Li} and K. {Fu}},
  journal={IEEE Transactions on Geoscience and Remote Sensing}, 
  title={Multi-Object Tracking in Satellite Videos with Graph-Based Multi-Task Modeling}, 
  year={2022},
  volume={},
  number={},
  pages={1-14},
  doi={10.1109/TGRS.2022.3152250}}
```
