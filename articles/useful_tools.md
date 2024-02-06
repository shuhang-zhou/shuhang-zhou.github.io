---
export_on_save:
  html: true
---

# 内容搭建小工具

这里记录一些在搭建网站内容的时候，用到的一些小工具。

[TOC]

## 画质增强工具

Real-ESRGAN 开源工具，它提供了绿色版exe文件。地址<https://github.com/xinntao/Real-ESRGAN>，直接下载对应的版本即可。

对于Windows，下载后在终端输入命令
```cmd
//定位到.exe 所在文件夹
cd .\realesrgan-ncnn-vulkan-20220424-windows
```
```cmd
//将input.jpg 画质增强并储存到 output.png
./realesrgan-ncnn-vulkan.exe -i input.jpg -o output.png
```

Real-ESRGAN 功能强大，有多种画质增强模型，还有视频增强功能。但是只能逐个增强，后续会介绍一个小的脚本，用于批量进行突变画质增强。编写自 @ChatGPT 。

## 图片压缩、转化

Imagine 开源工具，作为桌面APP并有用户友好的UI界面（有简体中文），pngquant，mozjpeg，WebP，Electron 的集大成者。地址<https://github.com/meowtec/Imagine>，下载对应版本。

操作简单明了，不再赘述。


##续：批量画质增强脚本

aaaaa啊啊7777啊富士康

![There is a PHTOT](/photos/articles/testphoto.png)