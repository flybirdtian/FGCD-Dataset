# FGCD-Dataset
The dataset for evaluating fine-grained change detection (published in ICCV 2015)

## Dataset descriptions
There are total three datasets: Dp, Db and Ds.
1. Dp include two outdoors scenes in the Summer Palace.
2. Db include 10 groups of images of laboratory testing blocks for the ageing simulation tests of mural deteriorations.
3. Ds are collected from 4 small statues.

Some detailed descriptions：

* Each group of images includes two observations, fine change detection ground truth (GT.bmp) and a mask (mask.bmp), two observations are not well aligned. 
* Each Observation contains 7 images under different illumations, including an environment lighting (EL) image and six directional side lighting (DSL) images.
* The first observation is named as 1-1.bmp to 1-7.bmp, and the second observation is named as 2-1.bmp to 2-7.bmp.
* The ground truth images are aligned with the second observations.
* Masks are used for the finally quantitative evaluation in our Paper[1].

# References
Please cite the following paper if you use this dataset in your work.

[1] W. Feng, F.-P. Tian, Q. Zhang, N. Zhang, L. Wan, J.-Z. Sun. Fine-Grained Change Detection of Misaligned Scenes with Varied Illuminations. In ICCV, 2015.
