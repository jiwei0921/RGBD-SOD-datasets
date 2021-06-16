# RGBD-SOD-datasets
All common **RGB-D Saliency Datasets** we collected are shared in ready-to-use manner.

---
## Ready-to-use Package
### We directly provide a ready-to-use download package, including all test sets, and two popular training sets in the RGB-D Saliency Detection.
+ All test datasets, [fetch code is **b2p2**](https://pan.baidu.com/s/1sx1En1ecNyDf12jNGFeYZQ).
+ Training dataset 1, including NJUD and NLPR, [fetch code is **76gu**](https://pan.baidu.com/s/1sNxe3Szu7O_Qci1OGmKIKQ).
+ Training dataset 2, including NJUD and NLPR, DUT, [fetch code is **201p**](https://pan.baidu.com/s/19aiosd_73VGMg7PB7HJzww).

---

## RGB-D Saliency Datasets
**Datasets** | NJUD | DUTLF-Depth | NLPR | SIP | STEREO | LFSD | RGBD135 | SSD | ReDWeb-S
:-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-:
**Size** | 1985 | 1200 | 1000 | 929 | 797/1000 | 100 | 135 | 80|  3179| 
**Publication** | [ICIP](http://dpfan.net/wp-content/uploads/NJU2K_dataset_ICIP14.pdf) | [ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Piao_Depth-Induced_Multi-Scale_Recurrent_Attention_Network_for_Saliency_Detection_ICCV_2019_paper.pdf) | [ECCV](http://dpfan.net/wp-content/uploads/NLPR_dataset_ECCV14.pdf) | [TNNLS](https://arxiv.org/pdf/1907.06781.pdf) | [CVPR](http://dpfan.net/wp-content/uploads/STERE_dataset_CVPR12.pdf) | [CVPR](http://dpfan.net/wp-content/uploads/LFSD_dataset_CVPR14.pdf) | [ICIMCS](http://dpfan.net/wp-content/uploads/DES_dataset_ICIMCS14.pdf) | [ICCVW](http://dpfan.net/wp-content/uploads/SSD_dataset_ICCVW17.pdf)| [ReDWeb-S](https://github.com/nnizhang/SMAC) | 
**Download link** | [here](https://pan.baidu.com/s/1o-kOaDVqjV_druBHjD3NAA) | [here](https://pan.baidu.com/s/1mhHAXLgoqqLQIb6r-k-hbA) | [here](https://pan.baidu.com/s/1pocKI_KEvqWgsB16pzO6Yw) | [here](https://pan.baidu.com/s/14VjtMBn0_bQDRB0gMPznoA) | [here](https://pan.baidu.com/s/1ISsDYT68LfQnhJPtgBFSyg)/[1000_ori](https://pan.baidu.com/s/1LQSxF7GsmRoSM_iz09Yl1A) | [here](https://pan.baidu.com/s/1EHCvEwAOBP9_wwAm29SctQ) | [here](https://pan.baidu.com/s/1qZTr3EgA7SJjJW1wA1doTQ) | [here](https://pan.baidu.com/s/1zNL9-KSQwGILdAAfStMXWQ)| [here](https://github.com/nnizhang/SMAC) |
+ Tips: All data is uniformly resized to 256×256 for training purposes.
  
## Citation
+ Please cite our paper if you use our dataset (**DUTLF-Depth**) in your research 
```
@inproceedings{piao2019depth,
  title={Depth-induced multi-scale recurrent attention network for saliency detection},
  author={Piao, Yongri and Ji, Wei and Li, Jingjing and Zhang, Miao and Lu, Huchuan},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={7254--7263},
  year={2019}
} 
```
## Evaluation Metrics
**[Metrics](https://github.com/jiwei0921/Saliency-Evaluation-Toolbox)** | * | * | * | *
:-: | :-: | :-: | :-: | :-:
**E-measure** | **S-measure** | **weighted F & F-measure** | **MAE** | **PR-curves**| 
Integration into a easy way. | *| * | * | The link is [here](https://github.com/jiwei0921/Saliency-Evaluation-Toolbox)|
+ This Toolbox contains near all evaluation metrics for salient object detection including E-measure, S-measure, weighted F & F-measure, MAE scores and PR curves or bar metrics.

### Contact Us
If you have any questions, please contact us ( weiji.dlut@gmail.com ).
