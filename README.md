# ShorelineNet

This notebooks trains an image segementation network with modified MobileNetV3 + UNet structure on the full MaSTr1325 dataset. The results are preliminarily evaluated based on a shoreline per-pixel accuracy, and subsequently exported and evaluated separately in MATLAB. 

```
Dataset   : 'mastr.zip' 
                1325 images 

Labels
  Obstacles and environment = 0
  Water = 1
  Sky = 2
  Ignore region / unknown category = 4

X: ? x 384 x 512 x 3 .png files
y: ? x 384 x 512     .png files 
```

Note that this script was originally ran in google colab and processed dataset is loaded from the drive. You can recreate the workflow by following documentations below

Find evaluation code here:  https://github.com/bborja/modd

Find dataset here: https://box.vicos.si/borja/viamaro/index.html

We kindly ask you to cite our papers if you use the provided code below.

```
@inproceedings{yao2021shorelinenet,
  title={ShorelineNet: An Efficient Deep Learning Approach for Shoreline Semantic Segmentation for Unmanned Surface Vehicles},
  author={Yao, Linghong and Kanoulas, Dimitrios and Ji, Ze and Liu, Yuanchang},
  booktitle={Proceedings of the... IEEE/RSJ International Conference on Intelligent Robots and Systems. IEEE/RSJ International Conference on Intelligent Robots and Systems},
  year={2021},
  organization={IEEE}
}
```


