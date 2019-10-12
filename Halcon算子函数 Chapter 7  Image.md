# HALCON 算子函数

## Chapter 7 : Image

### 7.1 Access

1.get_grayval

功能：获取一个图像目标的灰度值。

2.get_image_pointer1

功能：获取一个通道的指针。

3.get_image_pointer1_rect

功能：获取图像数据指针和输入图像区域内最小矩形内部的图像数据。

4.get_image_pointer3

功能：获取一个彩色图像的指针。

5.get_image_time

功能：查找图像被创建的时间。

### 7.2 Acquisition

1.close_all_framegrabbers

功能：关闭所有图像获取设备。

2.close_framegrabber

功能：关闭指定的图像获取设备。

3.get_framegrabber_lut

功能：查找图像获取设备的查询表。

4.get_framegrabber_param

功能：查找一个图像获取设备的指定参数。

5.grab_data

功能：从指定的图像获取设备获取图像和预处理图像数据。

6.grab_data_async

功能：从指定的图像获取设备获取图像和预处理图像数据并且开始下一个异步获取。

7.grab_image

功能：从指定的图像获取设备获取一个图像。

8.grab_image_async

功能：从指定的图像获取设备获取一个图像并且开始下一个异步获取。

9.grab_image_start

功能：从指定的图像获取设备开始下一个异步获取。

10.info_framegrabber

功能：从指定的图像获取设备查找信息。

11.open_framegrabber

功能：打开并配置一个图像获取设备。

12.set_framegrabber_lut

功能：设置图像获取设备查询表。

13.set_framegrabber_param

功能：设置一个图像获取设备的指定参数。

### 7.3 Channel

1.access_channel

功能：获取一个多通道图像的一个通道。

2.append_channel

功能：把附加模型（通道）添加到图像上。

3.channels_to_image

功能：把单通道图像转变为一个多通道图像。

4.compose2

功能：把两个图像转变为一个两通道图像。

5.compose3

功能：把三个图像转变为一个三通道图像。

6.compose4

功能：把四个图像转变为一个四通道图像。

7.compose5

功能：把五个图像转变为一个五通道图像。

8.compose6

功能：把六个图像转变为一个六通道图像。

9.compose7

功能：把七个图像转变为一个七通道图像。

10.count_channels

功能：计算图像的通道。

11.decompose2

功能：把一个两通道图像转变为两个图像。

12.decompose3

功能：把一个三通道图像转变为三个图像。

13.decompose4

功能：把一个四通道图像转变为四个图像。

14.decompose5

功能：把一个五通道图像转变为五个图像。

15.decompose6

功能：把一个六通道图像转变为六个图像。

16.decompose7

功能：把一个七通道图像转变为七个图像。

17.image_to_channels

功能：把一个多通道图像转变为一个通道图像。

### 7.4 Creation

1.copy_image

功能：复制一个图像并为它分配新内存。

2.gen_image1

功能：从像素的一个指针创建一个图像。

3.gen_image1_extern

功能：从带存储管理的像素的一个指针创建一个图像。

4.gen_image1_rect

功能：从像素（带存储管理）的指针创建一个矩形区域的图像。

5.gen_image3

功能：从像素（红、绿、蓝）的三个指针创建一个图像。

6.gen_image_const

功能：创建一个固定灰度值的图像。

7.gen_image_gray_ramp

功能：创建一个灰度值阶梯。

8.gen_image_interleaved

功能：从交叉像素的一个指针创建一个三通道图像。

9.gen_image_proto

功能：创建一个指定的固定灰度值的图像。

10.gen_image_surface_first_order

功能：创建一阶多项式的一个弯曲灰度表面。

11.gen_image_surface_second_order

功能：创建二阶多项式的一个弯曲灰度表面。

12.region_to_bin

功能：把一个区域转变为一个二进制字节图像。

13.region_to_label

功能：把区域转变为一个标签图像。

14.region_to_mean

功能：用它们的平均灰度值绘制区域。

### 7.5 Domain

1.add_channels

功能：把两个灰度值添加到区域中。

2.change_domain

功能：改变一个图像的定义区间。

3.full_domain

功能：把一个图像的区域扩大到最大值。

4.get_domain

功能：获取一个图像的区域。

5.rectangle1_domain

功能：把一个图像的区域缩小到一个矩形。

6.reduce_domain

功能：缩小一个图像的区域。

### 7.6 Features

1.area_center_gray

功能：计算一个灰度值图像的区域面积和重心。

2.cooc_feature_image

功能：计算一个同时出现的矩阵并得出相关灰度值特征。

3.cooc_feature_matrix

功能：从一个同时出现的矩阵计算灰度值特征。

4.elliptic_axis_gray

功能：在一个灰度值图像中计算一个区域的方位和主轴。

5.entropy_gray

功能：确定一个图像的熵和各向异性。

6.estimate_noise

功能：从一个单一图像估计图像噪声。

7.fit_surface_first_order

功能：通过一个一阶表面（平面）计算灰度值力矩和近似值。

8.fit_surface_second_order

功能：通过一个二阶表面（平面）计算灰度值力矩和近似值。

9.fuzzy_entropy

功能：确定区域的模糊熵。

10.fuzzy_perimeter

功能：计算一个区域的模糊周长。

11.gen_cooc_matrix

功能：在一个图像中计算一个区域中同时出现的矩阵。

12.gray_histo

功能：计算灰度值分布。

13.gray_histo_abs

功能：计算灰度值分布。

14.gray_projections

功能：计算水平和垂直灰度值预测。

15.histo_2dim

功能：计算两通道灰度值图像的直方图。

16.intensity

功能：计算灰度值的平均值和偏差。

17.min_max_gray

功能：计算区域内的最大和最小灰度值。

18.moments_gray_plane

功能：通过一个平面计算灰度值力矩和近似值。

19.plane_deviation

功能：从近似像平面计算灰度值的偏差。

20.select_gray

功能：选择基于灰度值特征的区域。

21.shape_histo_all

功能：用极限值确定特征的一个直方图。

22.shape_histo_point

功能：用极限值确定特征的一个直方图。

### 7.7 Format

1.change_format

功能：改变图像大小。

2.crop_domain

功能：去掉确定的灰度值。

3.crop_domain_rel

功能：去掉和定义域有关的图像区域。

4.crop_part

功能：去掉一个矩形图像区域。

5.crop_rectangle1

功能：去掉一个矩形图像区域。

6.tile_channels

功能：把多重图像拼成一个大图像。

7.tile_images

功能：把多重图像目标拼成一个大图像。

8.tile_images_offset

功能：把多重图像目标拼成一个有确定的位置信息的大图像。

### 7.8 Manipulation

1.overpaint_gray

功能：重新绘制一个图像的灰度值。

2.overpaint_region

功能：重新绘制一个图像的区域。

3.paint_gray

功能：把一个图像的灰度值画在另一个图像上。

4.paint_region

功能：把区域画在一个图像中。

5.paint_xld

功能：把XLD目标画在一个图像中。

6.set_grayval

功能：在一个图像中设置单灰度值。

### 7.9 Type-Conversion

1.complex_to_real

功能：把一个复杂图像转变为两个实际图像。

2.convert_image_type

功能：转变一个图像的类型。

3.real_to_complex

功能：把两个实际图像转变为一个复杂图像。

4.real_to_vector_field

功能：把两个实值图像转变为一个矢量域图像。

5.vector_field_to_real

功能：把一个矢量域图像转变为两个实值图像。