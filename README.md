

RegUn: Registration Uncertainty

## Introduction
Predicting registration error can be useful for evaluation of registration procedures, which is important for the adoption of registration techniques in the clinic. In addition, quantitative error prediction can be helpful in improving the registration quality. This work proposes a new automatic method to predict the registration error in a quantitative manner, and is applied to chest CT scans. A random regression forest is utilized to predict the registration error locally. The forest is built with features related to the transformation model and features related to the dissimilarity after registration.

### Citation
[1] Sokooti, H., Saygili, G., Glocker, B., Lelieveldt, B. P., & Staring, M. (2016, October). Accuracy estimation for medical image registration using regression forests. In International Conference on Medical Image Computing and Computer-Assisted Intervention (pp. 107-115). Springer, Cham.

## 1. Dependencies
- [numpy](http://www.numpy.org/) : General purpose array-processing package.
- [SciPy](https://www.scipy.org/) : A Python-based ecosystem of open-source software for mathematics, science, and engineering.
- [SimpleITK](http://www.simpleitk.org/) : Simplified interface to the Insight Toolkit for image registration and segmentation.
- [TBB](https://www.threadingbuildingblocks.org): Lets you easily write parallel C++ programs that take full advantage of multicore performance


## 2. Running RegUn
Run `uncertainty.py`. All of the addressess (images, results, etc) can be modified in  `Functions/Python/setting_utils.py`
