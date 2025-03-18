# Bishe is saved!

## 1. Oxford 102 flowers dataset
- https://www.robots.ox.ac.uk/~vgg/data/flowers/102/
- if you have a pre-selected model for your task, please take it. And you can use it to train your model. (e.g., resnet)
- if you don't have a pre-selected model, very likely you won't get a good result.



### 2. Fatigue check
- 5 face or 68 face points
- https://ibug.doc.ic.ac.uk/resources/facial-point-annotations/
- https://dlib.net/files/



### 3. Orbit prediction
- Argoverse api detects the orbit of the car
- https://arxiv.org/abs/2005.04259
- https://github.com/argoverse/argoverse-api
- https://www.argoverse.org/av1.html#download-link

- version:
    - python3.7
    - numpy==1.19.0
    - rosetta 2 -> X86_64
    - CONDA_SUBDIR=osx-64 conda create -n argoverse_env -c conda-forge python=3.8 numpy=1.19.0
    - SKLEARN_ALLOW_DEPRECATED_SKLEARN_PACKAGE_INSTALL=True pip3 install -e argoverse-api-master/


## References:
- https://www.bilibili.com/video/BV1n3rhYwE7G?spm_id_from=333.788.player.switch&vd_source=5b38429dc2a3c27f4efb082ccdfe871a&p=4