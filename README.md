<p align="center">
  <img src="figures/logo.png" height="150">
</p>

<div align="center">
    <b><font size="5">An industry-leading data provider in autonomous driving field</font></b>
    <sup>
      <a href="https://boden.ai/">
        <i><font size="4">Website</font></i>
      </a>
    </sup>
  </div>

<div align="center">

English | [简体中文](README_zh-CN.md)

</div>

## News
[2025] We have released 20K images and fully labeled annotations!

## Introduction

**Boden Around View Monitor Dataset** is an open source dataset for academic and industrial purpose, which consists of 20k desensitized images with fully labeled annotations. 

The images in this dataset are around-view images synthesized from four fisheye cameras. The detailed description of images are as follows:
* Resolution: 1024 x 1024 pixels
* View Range: 15m x 15m
* Sample video of stitching images from 4 fisheye cameras
* All images are anonymized to protect private information, such as number plates, faces and etc.

  [![sample video](http://img.youtube.com/vi/ejiigCk7eM0/0.jpg)](https://www.youtube.com/watch?v=ejiigCk7eM0)

**Sensor setup**:
* Fisheye cameras: SG2-IMX390C-GMSL2-H190s
  * HFOV: 216°
  * VFOV: 124°
  * Resolution: 1920 x 1080 pixels
  
  <p align="left">
  <img src="figures/sensor_setup.png" height="300">
  </p>

**Scenes**: The dataset was recorded in various indoor and outdoor parking sites. In order to cover scenes as much as we can, different illumination conditions and weather conditions were considered while collecting the data. Following are some examples: 
* Underground Parking lot
* Indoor Parking Building
* Surface Parking lot
* Roadside Parking lot

**Annotations**: Annotations of the dataset have following forms:
* Parking Slot (released)
* Freespace (released)
* Semantic Segmentation (released)
* Detailed description of annotation specification can be seen [here](docs/annotation.md).

**Planning**
- [x] release images and annotations
- [ ] release visualization script

## How to Download
* Download links for 2k sample images and annotations (Google Cloud)
  * [Images](https://drive.google.com/file/d/1Ny5rzYkyNYyX-YVsuMf3Q6zkCzn-Lzgk/view?usp=drive_link)
  * [Parking Slot Labels](https://drive.google.com/file/d/1K-uHvHfXJ1IsTctzhFC-1yP9G1K1aZ1i/view?usp=drive_link)
  * [Semantic Segmentation Labels](https://drive.google.com/file/d/1MMHc9ti-LRHWsL6rrGGCu_6Pc24hSf3n/view?usp=drive_link)
  * [Freespace Labels](https://drive.google.com/file/d/1gDcxc052jwSc9wCVU0jjTkyY6VWvGjUZ/view?usp=drive_link)
* 18K images and annotations (Google Cloud)
  * [Images](https://drive.google.com/file/d/1ZZVGbOVOOI8Z3iTQUYGZp9dUSJ1c0FBM/view?usp=drive_link)
  * [Parking Slot Labels](https://drive.google.com/file/d/19KQ9TqvCoMkuqqqezuX2dPEuplErv8Db/view?usp=drive_link)
  * [Semantic Segmentaion Labels](https://drive.google.com/file/d/19KQ9TqvCoMkuqqqezuX2dPEuplErv8Db/view?usp=drive_link)
  * [Freespace Labels](https://drive.google.com/file/d/1jVUDgTkAaXiaO1Zd0ZsRNcZp3_61zAyo/view?usp=drive_link)
* [Baidu Cloud](https://pan.baidu.com/s/1osNbB1vy6kCZci0J_ifAhg?pwd=rf8f), code:rf8f 

## Terms of Use
The images and annotations of this dataset are licensed under a [Creative Commons Attribution 4.0 License](LICENSE).

## Contact Us
For mistakes in annotations submmision, professional support requests, or commercial cooperation, please contact us through the email address: company@bodenai.com.

