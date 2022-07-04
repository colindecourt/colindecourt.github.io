---
title: "Publications"
date: 2022-04-24T16:54:43+02:00
draft: false
resources:
- src: ../data/Mo1-Mo-SI2-DAROD-A-DEEP-AUTOMOTIVE-RADAR-OBJECT-DETECTOR-ON-RANGE-DOPPLER-MAPS.pdf
  title: test
  icon: pdf
---

### DAROD: A Deep Automotive Radar Object Detector on Range-Doppler maps
*Colin Decourt, Rufin VanRullen, Didier Salle, Thomas Oberlin*  
*IEEE Intelligent Vehicles Symposium 2022*

{{< admonition type=abstract title="Abstract" open=false >}}
Due to the small number of raw data automotive radar datasets and the low resolution of such radar sensors, automotive radar object detection has been little explored with deep learning models in comparison to camera and lidar-based approaches. However, radars are low-cost sensors able to accurately sense surrounding object characteristics (e.g., distance, radial velocity, direction of arrival, radar cross-section) regardless of weather conditions (e.g., rain, snow, fog). Recent open-source datasets such as CARRADA, RADDet or CRUW have opened up research on several topics ranging from object classification to object detection and segmentation. In this paper, we present DAROD, an adaptation of Faster R-CNN object detector for automotive radar on the range-Doppler spectra. We propose a light architecture for features extraction, which shows an increased performance compare to heavier vision-based backbone architectures. Our models reach respectively an mAP$\@$0.5 of 55.83 and 46.57 on CARRADA and RADDet datasets, outperforming competing methods. 
{{< /admonition >}}

[IEEE version (soon)](#) [Poster (.pdf)](/pdf/poster_IV22_decourt_darod.pdf)

### Semi-supervised generative adversarial networks for the segmentation of the left ventricle in pediatric MRI  
*Colin Decourt, Luc Duong*  
*Computers in Biology and Medicine, Volume 123, 2020*

{{< admonition type=abstract title="Abstract" open=false >}}
Segmentation of the left ventricle in magnetic resonance imaging (MRI) is important for assessing cardiac function. We present DT-GAN, a generative adversarial network (GAN) segmentation approach for the identification of the left ventricle in pediatric MRI. Segmentation of the left ventricle requires a large amount of annotated data; generating such data can be time-consuming and subject to observer variability. Additionally, it can be difficult to accomplish in a clinical setting. During the training of our GAN, we therefore introduce a semi-supervised semantic segmentation to reduce the number of images required for training, while maintaining a good segmentation accuracy. The GAN generator produces a segmentation label map and its discriminator outputs a confidence map, which gives the probability of a pixel coming from the label or from the generator. Moreover, we propose a new formulation of the GAN loss function based on distance transform and pixel-wise cross-entropy. This new loss function provides a better segmentation of boundary pixels, by favoring the correct classification of those pixels rather than focusing on pixels that are farther away from the boundary between anatomical structures. Our proposed method achieves a mean Hausdorff distance of 2.16 mm $\pm$  0.42 mm (2.28 mm $\pm$ 0.21 mm for U-Net) and a Dice score of 0.88 $\pm$ 0.08 (0.91 $\pm$ 0.12 for U-Net) for the endocardium segmentation, using 50% of the annotated data. For the epicardium segmentation, we achieve a mean Hausdorff distance of 2.23 mm $\pm$ 0.35 mm (2.34 mm $\pm$ 0.39 mm for U-Net) and a Dice score of 0.93 mm $\pm$ 0.04 mm (0.89 $\pm$ 0.09 for U-Net). For the myocardium segmentation, we achieve a mean Hausdorff distance of 2.98 mm $\pm$ 0.43 mm (3.04 mm $\pm$ 0.27 mm for U-Net) and a Dice score of 0.79 mm $\pm$ 0.10 mm (0.74 $\pm$ 0.04 for U-Net). This new model could be very useful for the automatic analysis of cardiac MRI and for conducting large-scale studies based on MRI readings, with a limited amount of training data.
{{< /admonition >}}

[Journal version](https://doi.org/10.1016/j.compbiomed.2020.103884)
