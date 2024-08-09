<h1 align="center"> Multi-Granularity Hand Action Detection </h1>

<p align="center">
  <a href="#news">News</a> |
  <a href="#introduction">Abstract</a> |
  <a href="#usage">Usage</a> |
  <a href="#results">Results</a> |
  <a href="#statement">Statement</a>
</p>



# News

**2024.07.16**

- The paper "Multi-Granularity Hand Action Detection" has been accepted by the 32nd ACM International Conference on Multimedia (MM ’24). We will release the dataset and related code soon.


# Introduction
This is the official repository of the paper Multi-Granularity Hand Action Detection.


# Abstract
Detecting hand actions in videos is crucial for understanding video content and has diverse real-world applications. Existing approaches often focus on whole-body actions or coarse-grained action categories, lacking fine-grained hand-action localization information. To fill this gap, we introduce the FHA-Kitchens (Fine-Grained Hand Actions in Kitchen Scenes) dataset, providing both coarse- and fine-grained hand action categories along with localization annotations. This dataset comprises 2,377 video clips and 30,047 frames, annotated with approximately 200k bounding boxes and 880 action categories. Evaluation of existing action detection methods on FHA-Kitchens reveals varying generalization capabilities across different granularities. To handle multi-granularity in hand actions, we propose MG-HAD, an End-to-End Multi-Granularity Hand Action Detection method. It incorporates two new designs: Multi-dimensional Action Queries and Coarse-Fine Contrastive Denoising. Extensive experiments demonstrate MG-HAD's effectiveness for multi-granularity hand action detection, highlighting the significance of FHA-Kitchens for future research and real-world applications.


## Demo of bounding box annotations for different interaction regions

https://github.com/superZ678/FHA-Kitchens/assets/35674945/16f7d614-3738-494b-baf9-4a394b628d28


# Statement

This project is for research purposes only. For further questions, please contact Ting Zhe at zheting@whu.edu.cn.



## Citation


