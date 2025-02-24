---
layout: post
title: "三味书屋多页TIFF软件"
date:   2025-02-21
tags: [三味书屋多页TIFF软件,TIFF合并,TIFF拆分,TIFF压缩,分辨率检测,TIFF编辑,多页TIFF,TIFF,TIF]
comments: true
author: 君子聆听
---

三味书屋多页TIFF软件是一款专业性质的免费TIFF软件，主要专注于TIFF文件的处理，包括**TIFF合并**、**TIFF拆分**、**TIFF调整**、**TIFF统计**、**TIFF压缩**、**分辨率检测**、**颜色检测**，以及**TIFF查看与编辑功能**。

# 一、下载地址
    
	国际地址：https://1drv.ms/f/c/bcdc59f9d7581800/Eh73yCS-AH1BiRLUrHROMrYB1ZIq-kkFfcdgnXPC_FkdVg?e=4GqwHD
	中国大陆：链接地址：https://pan.baidu.com/s/1sQ7etC3JT-VmpOJ79assDg?pwd=3u2e
		 提取码：3u2e

# 二、更新说明（最新为8.0 版本）
    
1. 图形处理库切换为开源的Magick.NET；
2. 对软件的浏览与编辑模块的部分功能进行了增强与完善：
	- 替换图像现在可以同时替换多张；
	- 新增“粘贴并替换”功能；
	- 新增“另存为其它”功能模块，包括压缩后的PDF、单页图像、以及另存为PDF；
	- 对打印功能进行了性能改进，现在有更快的打印速度，页面范围的选项新增“选定范围”和“当前页面”；
	- 图像窗口的缩放与平移机制以及其它的一些细节得到了改进，现在有更好的使用体验；
3. TIFF合并、TIFF拆分、TIFF压缩等模块的压缩方案已切换到Magick.NET所支持的压缩方案。

# 三、运行环境
    
	操作系统：Windows 64位
	版本支持：Windows 7 / 8 / 8.1 / 10 / 11
	注意事项：
		① Windows 7 需升级SP1，并且需要安装补丁：KB3063858

# 四、功能说明

![image](https://github.com/user-attachments/assets/6c511588-07b0-4fe2-b581-16ef3b36717d)

## 4.1 查看与编辑

提供一些常用的查看与编辑功能。
注意：缩略图支持拖动更改位置顺序。

![image](https://github.com/user-attachments/assets/bf4842fd-6129-40bd-8f76-0da432aab353)

![image](https://github.com/user-attachments/assets/0d6f240a-6881-4b2c-8667-63abb04db8d6)

注意事项： 
- 缩略图支持拖动更改位置顺序；
- 支持打开的最大单个TIFF文件大小为 64GB ； 
- 支持打开的TIFF文件最大单帧尺寸为 65535 × 65535 。

## 4.2 TIFF合并

将jpg、bmp、png、tiff等图像合并成多页TIFF文件。

![image](https://github.com/user-attachments/assets/56d15b8d-78d0-47f9-a9b9-83e43c09f66d)

参数说明：
1. 合并方式：
	- 将每个子文件夹合并成一个TIFF文件；
	- 将所有图像合并成一个TIFF文件。
2. 压缩方案： 
	- Zip：Zip 压缩方案，一种高效的无损图像压缩算法。
	- JPEG：JPEG (联合摄影专家组) 压缩方案，一种高质量的有损图像压缩算法，在互联网领域广泛采用，适用于灰度图像和彩色图像。
	- LZW：LZW (Lempel-Ziv & Welch) 压缩方案，一种无损压缩算法，适用于灰度图像和彩色图像。
	- RLE：RLE（CCITT1D）压缩方案，一种简单的无损数据压缩算法，与PackBits压缩采用相同原理，常用于传真。(注意：此压缩方案会将图像转换为黑白（BlackWhite）像素格式。)
	- Group4：CCITT Group 4 Fax 压缩方案，比Group3和RLE更高效的传真压缩方式，适用于传真图像。(注意：此压缩方案会将图像转换为黑白（BlackWhite）像素格式。)
	- NoCompression：不使用压缩方案。

注意：RLE和 Group4会自动将要合并的图像转换为黑白（BlackWhite）像素格式。

## 4.3 TIFF拆分

将多页TIFF文件拆分成 jpg、bmp、png、tiff等格式。

![image](https://github.com/user-attachments/assets/bd23563c-b5fc-43fe-b48d-8bb2f5ca80d3)

参数说明：
1. 拆分方式： 
	- 每个TIFF文件拆分成一个单独文件夹；
	- 所有TIFF文件拆分至同一个文件夹。
2. 保存格式： 
	- JPG、BMP、PNG、TIFF
3. JPG质量（当保存格式为JPG时可设置） 
4. 隔行扫描（当保存格式为PNG时可设置）
	- fault：自动选择是否应该对图像进行隔行扫描；
	- On：对生成的位图图像进行隔行扫描；
	- Off：不对生成的位图图像进行隔行扫描。
5. 压缩类型（当保存格式为TIFF时可设置）
	- Zip：Zip 压缩方案，一种高效的无损图像压缩算法。
	- JPEG：JPEG (联合摄影专家组) 压缩方案，一种高质量的有损图像压缩算法，在互联网领域广泛采用，适用于灰度图像和彩色图像。
	- LZW：LZW (Lempel-Ziv & Welch) 压缩方案，一种无损压缩算法，适用于灰度图像和彩色图像。
	- RLE：RLE（CCITT1D）压缩方案，一种简单的无损数据压缩算法，与PackBits压缩采用相同原理，常用于传真。
	- Group4：CCITT Group 4 Fax 压缩方案，比Group3和RLE更高效的传真压缩方式，适用于传真图像。
	- NoCompression：不使用压缩方案。
	- 注意：RLE和 Group4会自动将要合并的图像转换为黑白（BlackWhite）像素格式。
5. 命名格式
	- 可以选择是否保留原始文件名并作为拆分文件名前缀
6. 分隔符号（当勾选命名格式时可设置） 
	- 可以选择或输入符号以将其用作分隔原始文件名的符号。
7. 是否补零
	- 可以选择是否对拆分的文件名进行补零，
	- 例如：未选择此选项时，拆分文件命名格式为1.jpg，2.jpg……9.jpg等，如果选择此选项，则拆分文件命名格式为0001.jpg，0002.jpg……0009.jpg等。 
8. 补零长度（当选择补零可设置）
	- 补零长度可设置为3~8位，注意：当拆分的文件顺序号大于所设置的补零长度时，将不会补零，而是保留原有顺序名称。
	- 例如：当设置补零长度为3位时，但有一份多页TIFF文件有1001帧图像，那么拆分后的第1000帧图像和第1001帧图像的命名是1000.jpg、1001.jpg。

## 4.4 TIFF调整

可以对多页TIFF文件进行逐帧缩放、DPI更改、像素格式更改等。

![image](https://github.com/user-attachments/assets/0ab8ed96-5941-452f-aad4-de9f125dcea0)

参数说明：
1. 启用缩放：对TIFF文件启用缩放操作； 
2. 缩放模式： 
	- 保持缩放纵横比
	- 自定义宽度和高度的缩放比例
3. 缩放比例：可以选择或输入1~100%的缩放比例，默认为85%。 
4. DPI更改：对TIFF文件启用DPI更改操作；
5. DPI模式 
	- 保持DPI纵横比
	- 自定义宽度和高度的DPI
6. DPI数值：可以选择预定义或输入自定义的DPI数值。 
7. 像素格式：对TIFF文件启用像素格式更改操作；
8. 像素格式
	- https://learn.microsoft.com/zh-cn/dotnet/api/system.windows.media.pixelformats?view=windowsdesktop-6.0&devlangs=csharp&f1url=%3FappId%3DDev16IDEF1%26l%3DZH-CN%26k%3Dk(System.Windows.Media.PixelFormats)%3Bk(DevLang-csharp)%26rd%3Dtrue
9. 调色板格式（仅当像素格式为Indexed索引系列时可选） 
	- https://learn.microsoft.com/zh-cn/dotnet/api/system.windows.media.imaging.bitmappalettes?view=windowsdesktop-8.0
10. 保存方式 
	- 保存并替换原文件
	- 另存为新文件（保留文件夹结构）

## 4.5 TIFF统计

可以对多页TIFF文件的帧数进行统计，并导出为Excel表。

注意：当TIFF统计的份数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总份数为200万时，此时导出的Excel会自动分割为两份Excel文件。

![image](https://github.com/user-attachments/assets/ccbafe54-dd51-495a-962e-58764b0c330d)

## 4.6 TIFF压缩

可以对多页TIFF文件进行压缩，以减少文件体积，并支持将压缩结果导出为Excel表。

注意：当TIFF统计的份数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总份数为200万时，此时导出的Excel会自动分割为两份Excel文件。

![image](https://github.com/user-attachments/assets/1cec3035-8a35-4413-99a0-eb3dd4ca87ae)

![image](https://github.com/user-attachments/assets/ac339a2b-72fc-44ae-badd-0965d12b201e)

参数说明：
1. 压缩方案 
	- Zip：Zip 压缩方案，一种高效的无损图像压缩算法。
	- JPEG：JPEG (联合摄影专家组) 压缩方案，一种高质量的有损图像压缩算法，在互联网领域广泛采用，适用于灰度图像和彩色图像。；
	- LZW：LZW (Lempel-Ziv & Welch) 压缩方案，一种无损压缩算法，适用于灰度图像和彩色图像。
	- RLE：RLE（CCITT1D）压缩方案，一种简单的无损数据压缩算法，与PackBits压缩采用相同原理，常用于传真。
	- Group4：CCITT Group 4 Fax 压缩方案，比Group3和RLE更高效的传真压缩方式，适用于传真图像。
	- NoCompression：不使用压缩方案。
	- 注意：RLE和 Group4会自动将要合并的图像转换为黑白（BlackWhite）像素格式。
2. 保存方式 
	- 保存并替换原文件
	- 另存为新文件（保留文件夹结构）

## 4.7 TIFF分辨率检测

可以对多页TIFF文件的分辨率进行逐帧检测，并导出为Excel表。

注意：当TIFF检测的帧数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总帧数为200万时，此时导出的Excel会自动分割为两份Excel文件。

![image](https://github.com/user-attachments/assets/37d4eb8a-49c6-44aa-9edf-3f27f805b20d)

![image](https://github.com/user-attachments/assets/a5d8b096-3735-4699-8833-5bd8306d98d1)

参数说明： 
1. 检测DPI： 
	- 可以选择或输入用作参照标准的DPI。 
2. 检测条件： 
	- 可以选择大于、等于、小于的比较条件。 

## 4.8 颜色检测

可以对多页TIFF文件的颜色类型进行逐帧检测，并导出为Excel表。

注意：当TIFF检测的帧数超过Excel行数限制（1048576）时，导出Excel时会自动对Excel文件进行分割，例如：当TIFF总帧数为200万时，此时导出的Excel会自动分割为两份Excel文件。

![image](https://github.com/user-attachments/assets/f14d26dc-6042-4deb-9dc6-5f79b9bb29f9)

![image](https://github.com/user-attachments/assets/2cb09441-6105-4d68-ba24-d37bd83ae93a)

参数说明：
1. 检测模式： 
	- 依据像素格式检测
	- 依据图像内容检测
2. 检测颜色 
	- 可以选择彩色、灰度、黑白； 
3. 模糊匹配（当检测模式为“依据图像内容检测”时可选） 
	- 是否启用黑白颜色模糊匹配，当启用该选项后，黑白颜色的RGB判断值将由（0，255）改为（0~30，230~255） 
4. 检测条件 
	- 可以选择等于或不等于。


