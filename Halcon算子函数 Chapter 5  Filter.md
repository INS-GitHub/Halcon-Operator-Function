# HALCON 算子函数

## Chapter 5 : Filter

### 5.1 Arithmetic

1.abs_image

功能：计算一个图像的绝对值（模数）。

2.add_image

功能：使两个图像相加。

3.div_image

功能：使两个图像相除。

4.invert_image

功能：使一个图像反像。

5.max_image

功能：按像素计算两个图像的最大值。

6.min_image

功能：按像素计算两个图像的最大小值。

7.mult_image

功能：使两个图像相乘。

8.scale_image

功能：为一个图像的灰度值分级。

9.sqrt_image

功能：计算一个图像的平方根。

10.sub_image

功能：使两个图像相减。

### 5.2 Bit

1.bit_and

功能：输入图像的所有像素的逐位与。

2.bit_lshift

功能：图像的所有像素的左移。

3.bit_mask

功能：使用位掩码的每个像素的逻辑与。

4.bit_not

功能：对像素的所有位求补。

5.bit_or

功能：输入图像的所有像素的逐位或。

6.bit_rshift

功能：图像的所有像素的右移。

7.bit_slice

功能：从像素中提取一位。

8.bit_xor

功能：输入图像的所有像素的逐位异或。

### 5.3 Color

1.cfa_to_rgb

功能：把一个单通道颜色滤波阵列图像变成RGB图像。

2.gen_principal_comp_trans

功能：计算多通道图像的主要部分分析的转换矩阵。

3.linear_trans_color

功能：计算多通道图像的颜色值的一个仿射转换。

4.principal_comp

功能：计算多通道图像的主要部分。

5.rgb1_to_gray

功能：把一个RGB图像转变成一个灰度图像。

6.rgb3_to_gray

功能：把一个RGB图像转变成一个灰度图像。

7.trans_from_rgb

功能：把一个图像从RGB颜色空间转变成任意颜色空间。

8.trans_to_rgb

功能：把一个图像从任意颜色空间转变成RGB颜色空间。

### 5.4 Edges

1.close_edges

功能：使用边缘幅值图像消除边缘缺陷。

2.close_edges_length

功能：使用边缘幅值图像消除边缘缺陷。

3.derivate_gauss

功能：用高斯派生物对一个图像卷积。

4.diff_of_gauss

功能：近似高斯的拉普拉斯算子。

5.edges_color

功能：使用Canny、Deriche或者_Shen_滤波器提取颜色边缘。

6.edges_color_sub_pix

功能：使用Canny、Deriche或者_Shen_滤波器提取子像素精确颜色边缘。

7.edges_image

功能：使用Deriche、_Lanser、Shen或者_Canny滤波器提取边缘。

8.edges_sub_pix

功能：使用Deriche、_Lanser、Shen或者_Canny滤波器提取子像素精确边缘。

9.frei_amp

功能：使用Frei-Chen算子检测边缘（幅值）。

10.frei_dir

功能：使用Frei-Chen算子检测边缘（幅值和相位）。

11.highpass_image

功能：从一个图像提取高频成分。

12.info_edges

功能：在edges_image估计滤波器的宽度。

13.kirsch_amp

功能：使用Kirsch算子检测边缘（幅值）。

14.kirsch_dir

功能：使用Kirsch算子检测边缘（幅值和相位）。

15.laplace

功能：使用有限差计算拉普拉斯算子。

16.laplace_of_gauss

功能：高斯的拉普拉斯算子。

17.prewitt_amp

功能：使用Prewitt算子检测边缘（幅值）。

18.prewitt_dir

功能：使用Prewitt算子检测边缘（幅值和相位）。

19.Roberts

功能：使用Roberts滤波器检测边缘。

20.robinson_amp

功能：使用Robinson算子检测边缘（幅值）。

21.robinson_dir

功能：使用Robinson算子检测边缘（幅值和相位）。

22.sobel_amp

功能：使用Sobel算子检测边缘（幅值）。

23.sobel_dir

功能：使用Sobel算子检测边缘（幅值和相位）。

### 5.5 Enhancement

1.adjust_mosaic_images

功能：全景图像的自动颜色更改。

2.coherence_enhancing_diff

功能：执行一个图像的一个一致性增强扩散。

3.emphasize

功能：增强图像对比度。

4.equ_histo_image

功能：图像的柱状图线性化。

5.illuminate

功能：增强图像对比度。

6.mean_curvature_flow

功能：把平均曲率应用在一个图像中。

7.scale_image_max_

功能：最大灰度值在0到255范围内。

8.shock_filter

功能：把一个冲击滤波器应用到一个图像中。

### 5.6 FFT

1.convol_fft

功能：用在频域内的滤波器使一个图像卷积。

2.convol_gabor

功能：用在频域内的一个Gabor滤波器使一个图像卷积。

3.correlation_fft

功能：计算在频域内的两个图像的相互关系。

4.energy_gabor

功能：计算一个两通道图像的能量。

5.fft_generic

功能：计算一个图像的快速傅里叶变换。

6.fft_image

功能：计算一个图像的快速傅里叶变换。

7.fft_image_inv

功能：计算一个图像的快速傅里叶逆变换。

8.gen_bandfilter

功能：生成一个理想带通滤波器。

9.gen_bandpass

功能：生成一个理想带通滤波器。

10.gen_derivative_filter

功能：在频域内生成一个倒数滤波器。

11.gen_filter_mask

功能：在空域内存储一个滤波器掩码作为实时图像。

12.gen_gabor

功能：生成一个Gabor滤波器。

13.gen_gauss_filter

功能：在频域内生成一个高斯滤波器。

14.gen_highpass

功能：生成一个理想高通滤波器。

15.gen_lowpass

功能：生成一个理想低通滤波器。

16.gen_sin_bandpass

功能：用正弦形状生成一个带通滤波器。

17.gen_std_bandpass

功能：用高斯或者正弦形状生成一个带通滤波器。

18.optimize_fft_speed

功能：使FFT的运行时间最优化。

19.optimize_rft_speed

功能：使实值的FFT的运行时间最优化。

20.phase_deg

功能：返回用角度表示的一个复杂图像的相位。

21.phase_rad

功能：返回用弧度表示的一个复杂图像的相位。

22.power_byte

功能：返回一个复杂图像的功率谱。

23.power_ln_

功能：返回一个复杂图像的功率谱。

24.power_real

功能：返回一个复杂图像的功率谱。

25.read_fft_optimization_data

功能：从一个文件中下载FFT速度最优数据。

26.rft_generic

功能：计算一个图像的实值快速傅里叶变换。

27.write_fft_optimization_data

功能：把FFT速度最优数据存储在一个文件中。

### 5.7 Geometric-Transformations

1.affine_trans_image

功能：把任意仿射2D变换应用在图像中。

2.affine_trans_image_size

功能：把任意仿射2D变换应用在图像中并且指定输出图像大小。

3.gen_bundle_adjusted_mosaic

功能：把多重图像合成一个马赛克图像。

4.gen_cube_map_mosaic

功能：创建球形马赛克的6方位图像。

5.gen_projective_mosaic

功能：把多重图像合成一个马赛克图像。

6.gen_spherical_mosaic

功能：创建一个球形马赛克图像。

7.map_image

功能：把一个一般变换应用于一个图像中。

8.mirror_image

功能：镜像一个图像。

9.polar_trans_image

功能：把一个图像转换成极坐标。

10.polar_trans_image_ext

功能：把一个图像中的环形弧转变成极坐标。

11.polar_trans_image_inv

功能：把极坐标中的图像转变成直角坐标。

12.projective_trans_image

功能：把投影变换应用于一个图像中。

13.projective_trans_image_size

功能：把投影变换应用于一个图像中并且指定输出图像的大小。

14.rotate_image

功能：以一个图像的中心为圆心旋转。

15.zoom_image_factor

功能：把一个图像缩放规定因子倍。

16.zoom_image_size

功能：把一个图像缩放到规定大小。

### 5.8 Inpainting

1.harmonic_interpolation

功能：对一个图像区域执行谐波插值。

2.inpainting_aniso

功能：通过各向异性扩散执行图像修复。

3.inpainting_ced

功能：通过一致性增强扩散执行图像修复。

4.inpainting_ct

功能：通过连贯传送执行图像修复。

5.inpainting_mcf

功能：通过水平线平滑执行图像修复。

6.inpainting_texture

功能：通过结构传导执行图像修复。

### 5.9 Lines

1.bandpass_image

功能：使用带通滤波器提取边缘。

2.lines_color

功能：检测色线和它们的宽度。

3.lines_facet

功能：使用面模型检测线。

4.lines_gauss

功能：检测线和它们的宽度。

### 5.10 Match

1.exhaustive_match

功能：模板和图像的匹配。

2.exhaustive_match_mg

功能：在一个分辨率塔式结构中匹配模板和图像。

3.gen_gauss_pyramid

功能：计算一个高斯金字塔。

4.monotony

功能：计算单一操作。

### 5.11 Misc

1.convol_image

功能：用一个任意滤波掩码对一个图像卷积。

2.expand_domain_gray

功能：扩大图像区域并且在扩大的区域中设置灰度值。

3.gray_inside

功能：对图像中的每一点在图像边界的任意路径计算尽可能低的灰度值。

4.gray_skeleton

功能：灰度值图像的细化。

5.lut_trans

功能：使用灰度值查询表转换一个图像。

6.symmetry

功能：沿一行的灰度值的对称性。

7.topographic_sketch

功能：计算一个图像的地理原始草图。

### 5.12 Noise

1.add_noise_distribution

功能：向一个图像添加噪声。

2.add_noise_white

功能：向一个图像添加噪声。

3.gauss_distribution

功能：产生一个高斯噪声分布。

4.noise_distribution_mean

功能：测定一个图像的噪声分布。

5.sp_distribution

功能：产生一个椒盐噪声分布。

### 5.13 Optical-Flow

1.optical_flow_mg

功能：计算两个图像之间的光流。

2.unwarp_image_vector_field

功能：使用一个矢量场来展开一个图像。

3.vector_field_length

功能：计算一个矢量场的矢量长度。

### 5.14 Points

1.corner_response

功能：在图像中寻找角点。

2.dots_image

功能：在一个图像中增强圆形点。

3.points_foerstner

功能：使用Förstner算子检测关注点。

4.points_harris

功能：使用Harris算子检测关注点。

5.points_sojka

功能：使用Sojka算子找出角点。

### 5.15 Smoothing

1.anisotrope_diff

功能：通过保边各向异性扩散平滑一个图像。

2.anisotropic_diffusion

功能：对一个图像执行各向异性扩散。

3.binomial_filter

功能：使用binomial滤波器平滑一个图像。

4.eliminate_min_max

功能：在空域内平滑一个图像来抑制噪声。

5.eliminate_sp

功能：用中值替代阀值外的值。

6.fill_interlace

功能：插补两个半个视频图像。

7.gauss_image

功能：使用离散高斯函数平滑图像。

8.info_smooth

功能：平滑滤波器smooth_image的信息。

9.isotropic_diffusion

功能：对一个图像执行各向同性扩散。

10.mean_image

功能：通过平均平滑一个图像。

11.mean_n

功能：几个通道的平均灰度值。

12.mean_sp

功能：抑制椒盐噪声。

13.median_image

功能：使用不同级别掩码的中值滤波。

14.median_separate_

功能：使用矩形掩码的离散中值滤波。

15.median_weighted

功能：使用不同级别掩码的加权中值滤波。

16.midrange_image

功能：计算掩码内最大和最小值的平均。

17.rank_image

功能：通过一个任意等级掩码平滑一个图像。

18.sigma_image

功能：使用sigma滤波器的非线性平滑。

19.smooth_image

功能：使用递归滤波器平滑一个图像。

20.trimmed_mean

功能：使用任意等级掩码平滑一个图像。

### 5.16 Texture

1.deviation_image

功能：计算矩形窗口内的灰度值的标准偏差。

2.entropy_image

功能：计算矩形窗口内的灰度值的熵。

3.texture_laws

功能：使用一个Laws文本滤波器过滤一个图像。

### 5.17 Wiener-Filter

1.gen_psf_defocus

功能：产生一个均匀散焦模糊的脉冲相应。

2.gen_psf_motion

功能：产生一个（线性）运动模糊的脉冲相应。

3.simulate_defocus

功能：对一个图像的均匀散焦模糊进行仿真。

4.simulate_motion

功能：（线性）运动模糊的仿真。

5.wiener_filter

功能：通过Wiener滤波进行图像恢复。

6.wiener_filter_ni

功能：通过Wiener 滤波进行图像恢复。
