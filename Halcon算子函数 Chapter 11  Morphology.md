# HALCON 算子函数

## Chapter 11 : Morphology

### 11.1 Gray-Values

1.dual_rank

功能：打开、取中值和关闭圆和矩形掩码。

2.gen_disc_se

功能：为灰度形态学生成椭圆结构基础。

3.gray_bothat

功能：执行一个图像的一个灰度值bottom_hat变换（原图像和它的闭之间的差）。

4.gray_closing

功能：关闭一个图像的一个灰度值。

5.gray_closing_rect

功能：关闭带矩形掩码的灰度值。

6.gray_cl_osing_shape

功能：关闭带选择掩码的灰度值。

7.gray_dilation

功能：扩大一个图像上的灰度值。

8.gray_dilation_rect

功能：确定一个矩形的最小灰度值。

9.gray_dilation_shape

功能：确定一个选择的掩码的最大灰度值。

10.gray_erosion

功能：腐蚀一个图像的灰度值。

11.gray_erosion_rect

功能：确定一个矩形的最小灰度值。

12.gray_erosion_shape

功能：确定一个选择的掩码的最小灰度值。

13.gray_opening

功能：打开一个图像的灰度值。

14.gray_opening_rect

功能：打开一个矩形掩码的灰度值。

15.gray_openin_g_shape

功能：打开一个选择的掩码的灰度值。

16.gray_range_rect

功能：确定一个矩形的灰度值范围。

17.gray_tophat

功能：执行一个图像的一个灰度值top_hat变换（原图像和它的开之间的差）。

18.read_gray_se

功能：为灰度形态学下载一个结构基础。

### 11.2 Region

1.bottom_hat

功能：计算区域的bottom_hat（原图像和它的闭之间的差）。

2.boundary

功能：把一个区域减小到它的边界。

3.closing

功能：闭运算。

4.closing_circle

功能：用一个圆形结构基础区域进行闭运算。

5.closing_golay

功能：关闭格雷字母表中的元素的一个区域。

6.closing_rectangle1

功能：用一个矩形结构基础区域进行闭运算。

7.dilation1

功能：膨胀一个区域。

8.dilation2

功能：膨胀一个区域（使用一个参考点）。

9.dilation_circle

功能：用一个圆形结构基础区域进行膨胀。

10.dilation_golay

功能：扩大格雷字母表的元素的一个区域。

11.dilation_rectangle1

功能：用一个矩形结构基础区域进行膨胀。

12.dilation_seq

功能：顺序地扩大一个区域。

13.erosion1

功能：腐蚀一个区域。

14.erosion2

功能：腐蚀一个区域（使用参考点）。

15.erosion_circle

功能：腐蚀一个圆形结构基础的一个区域。

16.erosion_golay

功能：腐蚀格雷字母表的一个元素的一个区域。

17.erosion_rectangle1

功能：腐蚀一个矩形结构基础的一个区域。

18.erosion_seq

功能：按顺序腐蚀一个区域。

19.fitting

功能：执行多重结构基础的打开后关闭。

20.gen_struct_elements

功能：生成一个标准结构基础。

21.golay_elements

功能：生成格雷字母表的结构基础。

22.hit_or_miss

功能：区域的Hit-or-miss运行。

23.hit_or_miss_golay

功能：使用格雷字母表的区域的Hit-or-miss运行。

24.hit_or_miss_seq

功能：使用格雷字母表的区域的Hit-or-miss运行（按顺序）。

25.minkowski_add1

功能：执行一个区域的Minkowski添加。

26.minkowski_add2

功能：扩大一个区域（使用参考点）。

27.minkowski_sub1

功能：腐蚀一个区域。

28.minkowski_sub2

功能：腐蚀一个区域（使用参考点）。

29.morph_hat

功能：计算bottom_hat_和top_hat的联合。

30.morph_skeleton

功能：计算一个区域的形态学框架。

31.morph_skiz

功能：缩小一个区域。

32.opening

功能：打开一个区域。

33.opening_circle

功能：打开一个圆形结构基础的一个区域。

34.opening_golay

功能：打开格雷字母表的一个元素的一个区域。

35.opening_rectangle1

功能：打开一个矩形结构基础的一个区域。

36.opening_seg

功能：分离重叠区域。

37.pruning

功能：去掉一个区域的分支。

38.thickening

功能：把一个Hit-or-miss运行的结果添加到一个区域。

39.thickening_golay

功能：把一个Hit-or-miss运行的结果添加到一个区域中（使用一个Golay结构基础）。

40.thickening_seq

功能：把一个Hit-or-miss运行的结果添加到一个区域中（按顺序）。

41.thinning

功能：从一个区域移去一个Hit-or-miss运行的结果。

42.thinning_golay

功能：从一个区域移去一个Hit-or-miss运行的结果（使用一个Golay结构基础）。

43.thinning_seq

功能：从一个区域移去一个Hit-or-miss运行的结果（按顺序）。

44.top_hat

功能：计算区域的top_hat（原图像和它的开之间的差）。