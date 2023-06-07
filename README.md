<h1 align="center"> FHA-Kitchens: A Novel Dataset for Fine-Grained Hand Action Recognition in Kitchen Scenes </h1>
<p align="center">
<!-- <a href="https://arxiv.org/abs/2305.02034"><img src="https://img.shields.io/badge/arXiv-Paper-<color>"></a> -->
</p>
<h5 align="center"><em>Ting Zhe, Yongqian Li, Jing Zhang, Yong Luo, Han Hu, Bo Du, Yonggang Wen, Dacheng Tao</em></h5>
<p align="center">
  <a href="#news">News</a> |
  <a href="#introduction">Abstract</a> |
  <a href="#usage">Usage</a> |
  <a href="#results">Results</a> |
  <a href="#statement">Statement</a>
</p>



# News

# Introduction
This is the official repository of the paper FHA-Kitchens: A Novel Dataset for Fine-Grained Hand Action Recognition in Kitchen Scenes
<!-- <a href="https://arxiv.org/abs/2305.02034"> FHA-Kitchens: A Novel Dataset for Fine-Grained Hand Action Recognition in Kitchen Scenes </a> -->

<figure>
<img src="Figs/1.png">
<figcaption align = "center"><b>Figure 1: Overview of the FHA-Kitchens dataset. The top shows some frames extracted from 8 dish categories. The bottom illustrates the annotation process of fine-grained actions in “fry vegetable”. 
 </b></figcaption>
</figure>

<p>

<p align="left"> In this paper, we present a novel dataset, namely the \textbf{FHA-Kitchens} dataset, which focuses on fine-grained hand actions observed in kitchen scenes. The FHA-Kitchens dataset encompasses a total of 2,377 video clips and 30,047 images, all extracted from eight different dish types. Each frame within the dataset is accompanied by meticulously labeled hand interaction regions, featuring high-quality annotations of fine-grained action categories and bounding boxes. The dataset can be used for supervised learning for hand interaction region and object detection (SL-D), supervised learning for fine-grained hand action recognition (SL-AR), and intra- and inter-class domain generalization for hand interaction region detection (DG).


# Usage
The code and dataset will be released soon.


# Overview
  ## Annotation Details
  
 <figure>
<img src="Figs/2.png">
<figcaption align = "center"><b>Figure 2: Comparisons of different high-resolution RS segmentation datasets. 
 </b></figcaption>
</figure>
  
  
# Results
## The basic information of generated datasets

<figure>
<img src="Figs/compare.png">
<figcaption align = "center"><b>Figure 2: Comparisons of different high-resolution RS segmentation datasets. 
 </b></figcaption>
</figure>

<p>

We present the comparison of our SAMRS dataset with existing high-resolution RS segmentation datasets in table. Based on the available high-resolution RSI object detection datasets, we can efficiently annotate 10,5090 images, which is more than ten times the capacity of existing datasets. Additionally, SAMRS inherits the categories of the original detection datasets, which makes them more diverse than other high-resolution RS segmentation collections. It is worth noting that RS object datasets usually have more diverse categories than RS segmentation datasets due to the difficulty of tagging pixels in RSIs, and thus our SAMRS reduces this gap. 



## Visualization of Generated Masks



<figure>
<img src="Figs/vis.png">
<figcaption align = "center"><b>Figure 3: Some visual examples from the three subsets of our SAMRS dataset.  
 </b></figcaption>
</figure>

<p>

In figure, we visualize some segmentation annotations from the three subsets in our SAMRS dataset. As can be seen, SOTA exhibits a greater number of instances for tiny cars, whereas FAST provides a more fine-grained annotation of existing categories in SOTA such as car, ship, and plane. SIOR on the other hand, offers annotations for more diverse ground objects, such as *dam*. Hence, our SAMRS dataset encompasses a wide range of categories with varying sizes and distributions, thereby presenting a new challenge for RS semantic segmentation.



## Dataset Statistics and Analysis
### The class distribution.

<figure>
<img src="Figs/class.png">
<figcaption align = "center"><b>Figure 4: Statistics of the number of pixels and instances for each category in the SAMRS database. The histograms for the subsets SOTA, SIOR, and FAST are shown in the first, second, and third columns, respectively. The first row presents histograms on a per-pixel basis, while the second row presents histograms on a per-instance basis.</a>  
 </b></figcaption>
</figure>



### The mask size distribution.

<figure>
<img src="Figs/mask_size.png">
<figcaption align = "center"><b>Figure 5: Statistics of the mask sizes in different subsets of the SAMRS database. (a) SOTA. (b) SIOR. (c) FAST.</a>  
 </b></figcaption>
</figure>




# Statement

This project is for research purpose only. For any other questions please contact [d_wang@whu.edu.cn](mailto:d_wang@whu.edu.cn).



## Citation

If you find SAMRS helpful, please consider giving this repo a star:star: and citing:

```
@inproceedings{SAMRS,
  title={Scaling-up Remote Sensing Segmentation Dataset with Segment Anything Model},
  author={Di Wang, Jing Zhang, Bo Du, Dacheng Tao, Liangpei Zhang},
  booktitle={arxiv},
  year={arXiv preprint arXiv:2305.02034}
}
```

## Relevant Projects

[1] <strong>An Empirical Study of Remote Sensing Pretraining, IEEE TGRS, 2022</strong> | [Paper](https://ieeexplore.ieee.org/document/9782149) | [Github](https://github.com/ViTAE-Transformer/RSP)
<br><em>&ensp; &ensp; &ensp;Di Wang<sup>&#8727;</sup>, Jing Zhang<sup>&#8727;</sup>, Bo Du, Gui-Song Xia and Dacheng Tao</em>

[2] <strong>Advancing Plain Vision Transformer Towards Remote Sensing Foundation Model, IEEE TGRS, 2022</strong> | [Paper](https://ieeexplore.ieee.org/document/9956816/) | [Github](https://github.com/ViTAE-Transformer/Remote-Sensing-RVSA)
<br><em>&ensp; &ensp; &ensp;Di Wang<sup>&#8727;</sup>, Qiming Zhang<sup>&#8727;</sup>, Yufei Xu<sup>&#8727;</sup>, Jing Zhang, Bo Du, Dacheng Tao and Liangpei Zhang</em>

