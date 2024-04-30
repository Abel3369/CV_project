# CV_project
Project for the course of Comp. Vision in Georgetown University
- reference: https://github.com/Abel3369/pytorch-animeGAN

## 1.slides and model
we put our slides and the model trained by ourselves in this file:
- The slides&model.zip

## 2.Environmental setup
```xml
- torch>=1.8.0
- torchvision==0.9.0
- numpy==1.21.1
- ipython==7.21.0
- opencv-python==4.3.0.38
- tqdm==4.21.0
- moviepy==1.0.3
```

## 3. Dataset
https://github.com/Abel3369/CV_project/releases/tag/dataset1.0
- The file "real-world" contains 6,656 real-world photos, which are 256 x 256 JPEG images used as inputs for the model.
- The file "anime_images" contains 2000 smoothed anime-style images , which are 256 x 256 JPEG images used as inputs for the model.
- We captured images from anime movies using a script and selected some that are brightly lit. After smoothing these images, we then used them as inputs.

## 4. Results
