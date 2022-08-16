<p align="center">
  <img src="figures/logo.png" height="150">
</p>

<div align="center">
    <b><font size="4">自动驾驶行业领先的数据提供商</font></b>
    <sup>
      <a href="https://www.bodenai.com/">
        <i><font size="2">网址</font></i>
      </a>
    </sup>
  </div>
<div align="center">

[English](README.md) | 简体中文

</div>


## 简介

**Boden Around View Monitor Dataset** 博登AVM数据集是一个为学术和商业目的而建立的开源数据集，包含20000张经过脱敏和手工标注的图片。

数据集中的图片是由4个鱼眼相机的图像合成的环视拼接图。以下是关于图片的一些详细信息：

* 分辨率: 1024 x 1024 像素
* 视野距离: 15 x 15 米
* 所有的图片都做过匿名处理以保护个人信息，所做的匿名处理包括车牌脱敏和人脸脱敏等。
* 下面提供了环视拼接图的一段视频样本

  [![video](http://img.youtube.com/vi/ejiigCk7eM0/0.jpg)](https://www.youtube.com/watch?v=ejiigCk7eM0)

**传感器设定**:
* 鱼眼相机: SG2-IMX390C-GMSL2-H190s
  * 水平FOV: 216°
  * 垂直FOV: 124°
  * 分辨率: 1920 x 1080 像素
  
  <p align="left">
  <img src="figures/sensor_setup.png" height="300">
  </p>

**场景**: 该数据集包含了在不同光照、天气、室外、室内场景下采集的图片。采集场景包括：
* 地下停车场
* 室内停车场
* 地面停车场
* 路边停车位

**标注**: 该数据集的标签内容包括：
* 库位角点 (已发布)
* 可行驶区域 (计划中)
* 语义分割 (计划中)
* 关于标注规范的细节描述请参见 [此处](docs/annotation.md).

**计划**
- [x] 发布图片和标签
- [ ] 发布可视化工具

## 如何下载

* 样本数据 ---- 2000 张带标签图片
  * [百度网盘](https://pan.baidu.com/s/14SOdWhwHweOhCI6By9i9Ww), 提取码: 40pt
  * [谷歌网盘](https://drive.google.com/drive/folders/1ipQpQmPlfzKhyKQ4ANFsnr2wDEwOAQUf?usp=sharing)
* 完整数据 ---- 18000 张带标签图片
  * 即将发布 （2022年9月1号）.
  * 仅支持申请。如需获取我们的完整数据集，请填写申请表并发送邮件至我们的邮箱（company@bodenai.com）。  [申请表模版](docs/Application_template.docx).

## 使用条例
数据集的图片和标签是基于CCBY-4.0开源许可证 [Creative Commons Attribution 4.0 License](LICENSE)

## 联系我们
如您发现了标签错误，或需要专业支持、寻求商业合作，欢迎联系我们（company@bodenai.com）。
