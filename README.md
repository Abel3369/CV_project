# CV_project
Project for the course of Comp. Vision in Georgetown University
Team Members: Shuheng Gong, Wei Li


## 1.slides and model
we put our slides and the model trained by ourselves in this file:
- The slides&model.zip

## 2.Environmental setup of Colab
```xml
Python 3 Google Compute Engine backend
V100 GPU
```

## 3. Dataset
https://github.com/Abel3369/CV_project/releases/tag/dataset1.0
- The file "real-world" contains 6,656 real-world photos, which are 256 x 256 JPEG images used as inputs for the model.
- The file "anime_images" contains 2000 smoothed anime-style images , which are 256 x 256 JPEG images used as inputs for the model.
- In the existing dataset, we captured images from Makoto Shinkai's latest anime movies ("The Garden of Words") and a previous film ("5 Centimeters Per Second") using an FFMPEG script and selected some that are brightly lit. After smoothing these images, we then used them as inputs.

## 4. Results
| Input | Shinkai style |
|--|--|
|![](./examples/input/1.jpg)|![](./examples/output/1.jpg)|
|![](./examples/input/2.jpg)|![](./examples/output/2.jpg)|
|![](./examples/input/3.jpg)|![](./examples/output/3.jpg)|
|![](./examples/input/4.jpg)|![](./examples/output/4.jpg)|
|![](./examples/input/5.jpg)|![](./examples/output/5.jpg)|

## 5. refernce:
- reference:
- https://github.com/Abel3369/pytorch-animeGAN
