---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<!--{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
## Table of Contents

1. [Extreme Weather Prediction](#extreme)
2. [High Spatio-Temporal CyGNSS Soil Moisture Using Machine Learning](#cygnss)
3. [Interpretable Machine Learning for Satellite Based Remote Sensing](#explainable)
4. [YouTop200: A Most-Watched Video Object Segmentation Dataset](#youtop)
5. [Self Supervised Learning Based 3D Instance Segmentation of Scutoid](#scutoid)

------------------------------------------------------------------------------
## Extreme Weather Prediction <a name="extreme"></a>

<!-- ![](/files/figures/MIT/PCCA_res.png) -->
<!-- ![](/files/figures/MIT/cnn_arch_fig.png) -->
<!-- <img src="/files/figures/MIT/cnn_arch_fig.png" width = '960' height = '500'> -->
<!-- <img src="/files/figures/MIT/PCCA_res.png" width = '800' height = 'auto'> -->
<img style="float:left;margin:10px 10px 0px 0px" src="/files/figures/MIT/PCCA_res.png">

### Abstract

In this study, we use analogue method and Convolutional Neural Networks (CNNs) to assess the potential predictability of extreme precipitation occurrence based on Large-Scale Meteorological Patterns (LSMPs) for the winter (DJF) of Pacific Coast California (PCCA) and the summer (JJA) of Midwestern United States (MWST). We evaluate the LSMPs constructed with a large set of variables at multiple atmospheric levels and quantify the prediction skill with a variety of complementary performance measures. Our results suggest that LSMPs provide useful predictability of daily extreme precipitation occurrence and its interannual variability over both regions. The 14-year (2006-2019) independent forecast shows Gilbert Skill Scores (GSS) in PCCA range from 0.06 to 0.32 across 24 CNN schemes and from 0.16 to 0.26 across 4 analogue schemes, in contrast to those from 0.1 to 0.24 and from 0.1 to 0.14 in MWST. Overall, CNN is shown to be more powerful in extracting the relevant features associated with extreme precipitation from the LSMPs than analogue method, with several single-variate CNN schemes achieving more skillful prediction than the best multi-variate analogue scheme in PCCA and more than half of CNN schemes in MWST. Nevertheless, both methods highlight the Integrated Vapor Transport (IVT, or its zonal and meridional components) enables higher skills than other atmospheric variables over both regions. Warm-season extreme precipitation in MWST presents a forecast challenge with overall lower prediction skill than in PCCA, attributed to the weak synoptic-scale forcing in summer.

### Publication

Xiang Gao and Shray Mathur. "Predictability of U.S. Regional Extreme Precipitation Occurrence Based on Large-Scale Meteorological Patterns (LSMPs)." *Journal of Climate*, 2021 [[Paper](https://doi.org/10.1175/JCLI-D-21-0137.1)]

<!-- The field of ***connectomics*** aims to reconstruct the wiring diagram of the brain by mapping the neural connections at the level of individual synapses. Recent advances in electronic microscopy (EM) have enabled the collection of a large number of image stacks at nanometer resolution, but the annotation requires expertise and is super time-consuming. Here we provide a deep learning framework powered by [PyTorch](https://pytorch.org/) for automatic and semi-automatic image segmentation in connectomics. This repository is actively under development by Visual Computing Group ([VCG](https://vcg.seas.harvard.edu)) at Harvard University. -->

<!-- ### [[Documentation](https://zudi-lin.github.io/pytorch_connectomics/build/html/index.html)] [[GitHub](https://github.com/zudi-lin/pytorch_connectomics#pytorch-connectomics)] -->

<!-- Besides installation guidance and package references, we provide several tutorials covering both semantic and instance segmentation for [neurons](https://zudi-lin.github.io/pytorch_connectomics/build/html/tutorials/snemi.html), and other biological structures like [synapses](https://zudi-lin.github.io/pytorch_connectomics/build/html/tutorials/cremi.html) and [mitochondria](https://zudi-lin.github.io/pytorch_connectomics/build/html/tutorials/mito.html). -->

------------------------------------------------------------------------------
## High Spatio-Temporal CyGNSS Soil Moisture Using Machine Learning <a name="cygnss"></a>

![](/files/figures/UT/scatter_daily_36km_all_months.png)
<!-- <img style="float:left;margin:10px 10px 0px 0px" src="/files/figures/UT/spatial_corr_heatmaps.png" width = '500' height = '500'> -->

### Abstract

This dissertation presents a Machine Learning based soil moisture retrieval method for NASA’s Cyclone Global Navigation Satellite System (CYGNSS) mission. The CYGNSS observations are compared to the Soil Moisture Active Passive (SMAP), in-situ Texas Soil Observation Network (TxSON) and NASA's CyGNSS L3 soil moisture (SM) measurements for the entire 2019 year. An initial grid-wise sensitivity analysis of CYGNSS reflectivity (P<sub>r,eff</sub>) to Soil Moisture (SM) is conducted at a 9x9km<sup>2</sup> grid resolution over the 36x36 km<sup>2</sup> TxSON region to assess the spatio-temporal relationships between P<sub>r,eff</sub> and SM. Variability among grid cells and seasonal shifts in correlations motivated inclusion of land physical parameters and CYGNSS observation geometry in the analysis.  Specifically, we include the Specular Point (SP) incidence angle(θ),Elevation, Clay Fraction, Normalized Difference Vegetation Index (NDVI), Depth to Restrictive Layer (DepRes), and surface roughness. The individual effects of these variables on P<sub>r,eff </sub> are assessed through a correlation and regression analysis. Finally, an Artificial Neural Network (ANN) model is trained for different combinations of input features to attain SM estimates at 9x9km<sup>2</sup>and 3x3km<sup>2</sup> grid resolutions. The model structure is tuned to attain optimal results for different combinations and a 5-fold cross validation approach is employed to train the models. SM predictions with a root mean squared error of 0.0409 (0.0497) cm<sup>3</sup>/cm<sup>3</sup> and Pearson correlation coefficient of 0.7024 (0.6794) are reported at 9x9 (3x3) km<sup>2</sup> grid resolution

[[Thesis](/files/UT/Thesis.pdf)]

<!-- Zudi Lin, [Donglai Wei](https://donglaiw.github.io), [Won-Dong Jang](https://wdjang.github.io), Siyan Zhou, Xupeng Chen, [Xueying Wang](https://sites.google.com/view/snowxwang/home?authuser=0), Richard Schalek, Daniel Berger, [Brian Matejek](https://www.brianmatejek.com), Lee Kamentsky, Adi Suissa-Peleg, [Daniel Haehn](https://danielhaehn.com), [Thouis Jones](https://personal.broadinstitute.org/thouis/), Toufiq Parag, [Jeff Lichtman](https://lichtmanlab.fas.harvard.edu/people/jeff-lichtman) and [Hanspeter Pfister](https://en.wikipedia.org/wiki/Hanspeter_Pfister). "Two-Stream Active Query Suggestion for Active Learning in Connectomics." *European Conference on Computer Vision* (**ECCV**), 2020 [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630103.pdf)][[Supp.](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123630103-supp.pdf)]

### Code

* Mitocondria Segmentation on the Lucchi Dataset [[Link](https://zudi-lin.github.io/pytorch_connectomics/build/html/tutorials/mito.html#semantic-segmentation)]
* Synaptic Cleft Detection on the CREMI Dataset [[Link](https://zudi-lin.github.io/pytorch_connectomics/build/html/tutorials/synapse.html#synaptic-cleft-detection)]
* Synaptic Polarity Detection on the EM-R50 Dataset [[Link](https://zudi-lin.github.io/pytorch_connectomics/build/html/tutorials/synapse.html#synaptic-polarity-detection)]
* ***Two-Stream Query Suggestion*** Algorithm [[Link](https://github.com/zudi-lin/pytorch_connectomics/blob/master/scripts/tools/active_learning/two_stream.py)]

### Dataset

Todo

### Acknowledgements

This project has been partially supported by NSF award IIS-1835231 and NIH award 5U54CA225088-03. -->

------------------------------------------------------------------------------
## Interpretable Machine Learning for Satellite Based Remote Sensing<a name="explainable"></a>

<!-- ![Two-stream active](/files/figures/Aarhus/tSNE_all.png) -->
<!-- <img style="float:left;margin:10px 10px 0px 0px" src="/files/figures/Aarhus/tSNE_all.png" width="400" height="400"> -->
<img style="float:left;margin:10px 10px 0px 0px" src="/files/figures/Aarhus/tSNE_all.png" width = "550" height = "550">

### Abstract

The use of machine learning methods for data analytics in satellite based remote sensing has grown tremendously in recent years. However, the increase in performance due to the use of increasingly sophisticated machine learning models have negatively impacted the transparency of the data pipeline, as the machine learning models often acts as black-box predictors. In this paper, we employ methods from the field of interpretable machine learning and explainable AI to address this issue, and present a transparent data pipeline, where machine learning classifications are presented in union with explanations to the underlying reasons for the individual classifications. We demonstrate this on crop type classification over 4 seasons from 2017-2020, based on field-level zonal statistics from Sentinel-1 tiles. The data analytics pipeline has emphasis on visualizing and investigating the temporal evolution of the individual crop types, which is then used in conjunction with a variety of machine learning models to provide crop type classification strongly coupled to the temporal evolution and the underlying agronomical understanding. This couples the machine learning models directly to the temporal dynamics of the individual crop types. We focus on linear and non-linear models, from a logistic regression classifier to a neural network, and differentiate between inherently interpretable models, such as logistic regression classifiers, and black-box with no inherent interpretability, such as neural networks. Throughout the paper, we provide insights into potential pitfalls regarding interpretability, such as issues with correlated input features and subjective interpretations of the classification explanations. Finally, we investigate the current state-of-the-art in interpretable non-linear machine learning models, such as explainable boosting machines, and provide future perspectives with regard to increasingly complex machine learning models and significantly larger data repositories, combined with and increased use of machine learning models by regulatory agencies in the EU, and what needs for interpretability such uses require.

------------------------------------------------------------------------------
## YouTop200: A Most-Watched Video Object Segmentation Dataset <a name="youtop"></a>

![](/files/figures/Harvard/segs_upd.png)

### Abstract

We collected and annotated a new dataset—YouTop200-of 200 most-watched YouTube videos in their full length, spanning ten genres. Our effort exceeds previous attempts in dataset size, scene and object variability, and narrative structure complexity. YouTop200 has 431K annotated instance masks, which doubles the number of masks over previous datasets. We build a semi-automatic system to efficiently annotate high-quality masks for main characters — human, animal, or animated — whose position, pose, and appearance can change significantly across edited shots. Furthermore, we design a simple long-term crossshot tracking module (LCT) to enhance existing methods and provide stronger baselines. Finally, we show the limitation of current methods with a results analysis on our YouTop200 dataset to motivate future research.


------------------------------------------------------------------------------
## Semi-supervised Learning Based 3D Instance Segmentation of Scutoid <a name="scutoid"></a>

<!-- ![Two-stream active](/files/figures/Harvard/scutoid_fig.png) -->

<!-- <img src="/files/figures/Harvard/scutoid_fig.png" width = '960' height = '300'> -->
<!-- <img style="float:left;margin:10px 10px 0px 0px" src="/files/figures/Harvard/scutoid_fig.png" alt="MitoEM Logo" width="160" height="160"> -->
<img style="float:left;margin:10px 10px 0px 0px" src="/files/figures/Harvard/scutoid_fig.png" width="400" height="400">
Cells in bent epithelia can undergo intercalations along the apico-basal axis. This phenomenon forces cells to have different neighbours in their basal and apical surfaces. As a consequence, epithelial cells adopt a novel shape that is termed as “scutoid”. Machine learning applications in bio-medical imaging are frequently limited by the lack of quality labeled data. In this project, we explore the self training method, a form of semi-supervised learning, to leverage additional unlabelled 3D Electron Microscopy Scutoid volumes. We use a pre-trained Residual Symmetric 3D U-Net to generate pseudo-labels of additional unlabeled volumes. The model is then retrained using labelled and pseudo-labeled volumes to improve adapted rand index on a set of test volumes. The watershed segmentation algorithm is used to convert the binary foreground probability maps, instance contours and signed distance transform to instance mask



<!-- ### MitoEM Challenge: Large-scale 3D Mitochondria Instance Segmentation

<a href="https://mitoem.grand-challenge.org">
<img style="float:left;margin:10px 10px 0px 0px" src="/files/figures/challenges/mitoem_logo.png" alt="MitoEM Logo" width="160" height="160">
</a>

The task is the ***3D mitochondria instance segmentation*** on two 30x30x30 μm^3 datasets, 1000x4096x4096 in voxels at (30, 8, 8) nanometer (nm) resolution. The electron microscopy (EM) image volumes are acquired from a rat (MitoEM-R) and a human (MitoEM-H) tissue, respectively. The mitochondria can display a complex morphology, *e.g.*, mitochondria-on-a-string (MOAS) instances that are connected by thin microtubules, and multiple instances can entangle with each other. Our [MitoEM challenge](https://mitoem.grand-challenge.org) is held at [IEEE ISBI 2021](https://biomedicalimaging.org/2021/). -->
