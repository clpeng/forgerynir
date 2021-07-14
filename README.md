# ForgeryNIR: Deep Face Forgery and Detection in Near-Infrared Scenario

This repository provides the dataset and code for the following paper:

---
> **Abstract:** 
Deep face forgery and detection is an emerging topic due to the development of GANs. Face forgery detection relies greatly on existing databases for evaluation and adequate training examples for data-hungry machine learning algorithms. However, considering the wide application of face recognition in near-infrared scenarios, there is no publicly available face forgery database that includes near-infrared modality currently. In this paper, we present the first attempt at constructing a large-scale dataset for face forgery detection in the near-infrared modality. The proposed near-infrared face forgery dataset, named ForgeryNIR, contains a total of over 50,000 real and fake identities. A number of perturbations are applied to help simulate real-world scenarios. All source images in ForgeryNIR are collected from CASIA NIR-VIS 2.0, and fake images are generated via multiple GAN techniques. The proposed dataset fills the gap of face forgery detection research in the near-infrared modality. A comprehensive study on three representative detection baselines is conducted to evaluate the performance of face forgery detection algorithms in the NIR domain. We further construct a hard testing set, named ForgeryNIR+, which contains forged images that have bypassed existing face forgery detection methods. The proposed datasets will be publicly available and aim to help boost further research on face forgery detection, as well as NIR face detection and recognition.


## Dataset
---
![数据库总构成图](source/数据库总构成图.png)

![数据库示例](source/数据库示例.png)
---


## Summary
---
### Data Collection

CASIA NIR-VIS 2.0  is a dataset proposed for NIR-VIS recognition including 725 identities with 17,580 face images. and the ages of the identities are very wide, from children to old people. the faces in the near-infrared modality are selected as our face generation training source data.

### Forged Face Generation



### Face Augumentation

### Baselines

We select three representative forgery detection baselines using the ForgeryNIR dataset. Please refer to our paper for more information.

## Citation
---
If you find this work useful for your research, please cite our papers:

## Acknowledgments
---

## Download
---
