# Algebraic Shape Operator

This c++ project is the authors implementation of the following article

## Stable and efficient differential estimators on oriented point clouds [(PDF)](TODO)

*Thibault Lejemble*  
*David Coeurjolly*  
*Loïc Barthe*  
*Nicolas Mellado*

Computer Graphics Forum 2021  
Symposium on Geometry Processing (SGP) 2021

**Abstract**  
Point clouds are now ubiquitous in computer graphics and computer vision. Differential properties of the point-sampled surface, such as principal curvatures, are important to estimate in order to locally characterize the scanned shape. To approximate the surface from unstructured points equipped with normal vectors, we rely on the Algebraic Point Set Surfaces (APSS) [GG07] for which we provide convergence and stability proofs for the mean curvature estimator. Using an integral invariant viewpoint, this first contribution links the algebraic sphere regression involved in the APSS algorithm to several surface derivatives of different orders. As a second contribution, we propose an analytic method to compute the shape operator and its principal curvatures from the fitted algebraic sphere. We compare our method to the state-of-the-art with several convergence and robustness tests performed on a synthetic sampled surface. Experiments show that our curvature estimations are more accurate and stable while being faster to compute compared to previous methods. Our differential estimators are easy to implement with little memory footprint and only require a unique range neighbors query per estimation. Its highly parallelizable nature makes it appropriate for processing large acquired data, as we show in several real-world experiments.

![teaser](https://github.com/STORM-IRIT/algebraic-shape-operator/blob/single-header-file/image/teaser.png)
**Caption**: Differential estimations computed with our stable estimators on a large point cloud with normals (2.5M points). Zoom on: (a) the initial point cloud, (b) our corrected normal vectors, (c) mean curvature, (d,e) principal curvatures, and (f) principal curvature directions.

## Getting Started

TODO

___

Please cite this paper if you use this code
```
@article{lejemble2021stable,
  author = {Lejemble, Thibault and Coeurjolly, David and Barthe, Loïc and Mellado, Nicolas},
  title = {Stable and efficient differential estimators on oriented point clouds},
  journal = {Computer Graphics Forum},
  volume = {40},
  number = {5},
  year = {2021}
}
```  
