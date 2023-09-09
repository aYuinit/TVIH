# TVIH Dataset

This Thermal infrared/Visible Images in Haze (TVIH) dataset consists of registered high-resolution thermal infrared and visible image pairs captured in outdoor dense haze and mist conditions. The dataset is utilized in our recent paper titled "Thermal infrared guided color image dehazing" in 2023 IEEE International Conference on Image Processing (ICIP 2023)

## Overview

Publicly available datasets comprising visible/thermal infrared image pairs that capture outdoor scenes under natural hazy conditions are limited. In response to this need, we propose the Thermal Infrared/Visible Images in Haze (TVIH) dataset. This dataset includes registered, high-resolution thermal infrared and visible image pairs captured under hazy outdoor conditions. 

After  data collection, at least ten corresponding points are manually  marked in each image pair to compute the 3×3 homography  matrix. Finally, each visible image is warped and registered  to the corresponding thermal infrared image to achieve pixelto-pixel alignments. Most image resolutions are 1280×1024.

## Thermal Infrared/Visible Images in Haze

- **Image size**: 1280 x 1024(Most images)

-  **Channels**: 
  + Infrared: Gray
  + Visible: RGB
  
-  **Spectral range**: 
  
  + Thermal infrared: 8 ~ 14µm
  + Visible: 400 ~  780nm
  
-  **Quantity:**
  
  + 58  pairs of thermal/visible images in dense haze scenes

  + 23  pairs in  thermal/visible images in mist.
  
    
  
- **Image Sample**

<p align="center">
  <img src="samples\image_densehaze.png" alt="Alternate text"/>
  <br>
  <em> Some sample pairs of the visible/thermal images in dense haze</em>
</p>

<p align="center">
  <img src="samples\image_mist.png" alt="Alternate text"/>
  <br>
  <em> Some sample pairs of the visible/thermal images in mist</em>
</p>


## Where to Download

- **Google Drive**: Download from our Google Drive folder available [here](https://drive.google.com/file/d/1CNf9kzmSB2DTtd_KpAFAqB6r2LfUcxgg/view?usp=drive_link).
- **Baidu Pan**: Download from Baidu Pan with this link: [here](https://pan.baidu.com/s/11n0aGtai1RQP4q22kyNLZQ) and the extraction code: `hqaq`.


## License

This dataset is for academic research purpose only.

## Citation

If you use the TVIH Dataset in your research, please cite our paper. A suggested citation is provided below:

```
@INPROCEEDINGS{,
  author={Xie, Jiayu and Jin, Xin},
  booktitle={2023 IEEE International Conference on Image Processing (ICIP)}, 
  title={Thermal infrared guided color image dehazing}, 
  year={2023},
  volume={},
  number={},
  pages={1-5},
  doi={}}
```
