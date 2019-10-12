# HALCON 算子函数

## Chapter 6 : Graphics

### 6.1 Drawing

1.drag_region1

功能：一个区域的交互运动。

2.drag_region2

功能：一个带有定点规格区域的交互运动。

3.drag_region3

功能：一个带有限制位置区域的交互运动。

4.draw_circle

功能：一个圆的交互绘图。

5.draw_circle_mod

功能：一个圆的交互绘图。

6.draw_ellipse

功能：一个椭圆的交互绘图。

7.draw_ellipse_mod_

功能：一个椭圆的交互绘图。

8.draw_line

功能：画一根线。

9.draw_line_mod

功能：画一根线。

10.draw_nurbs

功能：一个NURBS曲线的交互绘图。

11.draw_nurbs_interp

功能：使用插值的一个NURBS曲线的交互绘图。

12.draw_nurbs_interp_mod

功能：使用插值的一个NURBS曲线的交互修正。

13.draw_nurbs_mod

功能：一个NURBS曲线的交互修正。

14.draw_point

功能：画一个点。

15.draw_point_mod

功能：画一个点。

16.draw_polygon

功能：一个多边形的交互绘图。

17.draw_rectangle1

功能：画一个与坐标轴平行的矩形。

18.draw_rectangle1_mod

功能：画一个与坐标轴平行的矩形。

19.draw_rectangle2

功能：任意定向矩形的交互绘图。

20.draw_rectangle2_mod

功能：任意定向矩形的交互绘图。

21.draw_region

功能：一个闭区域的交互绘图。

22.draw_xld

功能：一个轮廓的交互绘图。

23.draw_xld_mod

功能：一个轮廓的交互修正。

### 6.2 Gnuplot

1.gnuplot_close

功能：关闭所有打开的gnuplot文件或者终止一个活动的gnuplot子流程。

2.gnuplot_open_file

功能：为图像和控制量的可视化打开一个gnuplot文件。

3.gnuplot_open_pipe

功能：为图像和控制量的可视化打开一个通道的gnuplot流程。

4.gnuplot_plot_ctrl

功能：使用gnuplot显示控制量。

5.gnuplot_plot_funct_1d

功能：使用gnuplot显示控制量的功能。

6.gnuplot_plot_image

功能：使用gnuplot使一个图像可视化。

### 6.3 LUT

1.disp_lut

功能：查询表的图解。

2.draw_lut

功能：交互利用查询表。

3.get_fixed_lut

功能：为实际彩色图像获取固定查询表。

4.get_lut

功能：获取现在的查询表。

5.get_lut_style

功能：获取查询表的修正参数。

6.query_lut

功能：查询所有可得到的查询表。

7.set_fixed_lut

功能：为实际彩色图像固定查询表。

8.set_lut

功能：设置查询表。

9.set_lut_style

功能：改变查询表。

10.write_lut

功能：把查询表作为文件写入。

### 6.4 Mouse

1.get_mbutton

功能：等待直到一个鼠标键被按下。

2.get_mposition

_功能：查询鼠标位置。

3.get_mshape

功能：查询现在鼠标指针形状。

4.query_mshape

功能：查询所有可得到的鼠标指针形状。

5.set_mshape

功能：设置现在鼠标指针形状。

### 6.5 Output

1.disp_arc

功能：在一个窗口中显示圆形弧。

2.disp_arrow

功能：在一个窗口中显示箭头。

3.disp_channel

功能：用几个通道显示图像。

4.disp_circle

功能：在一个窗口中显示圆。

5.disp_color

功能：显示一个彩色（RGB）图像。

6.disp_cross

功能：在一个窗口中显示交叉。

7.disp_distribution

功能：显示一个噪声分布。

8.disp_ellipse

功能：显示椭圆。

9.disp_image

功能：显示灰度值图像。

10.disp_line

功能：在窗口中画一条线。

11.disp_obj

功能：显示图像目标（图像，区域，XLD）。

12.disp_polygon

功能：显示一个多叉线。

13.disp_rectangle1

功能：显示和坐标轴对齐的矩形。

14.disp_rectangle2

功能：显示任意方向的矩形。

15.disp_region

功能：在一个窗口中显示区域。

16.disp_xld

功能：显示一个XLD物体。

### 6.6 Parameters

1.get_comprise

功能：获取一个图像矩阵的输出处理。

2.get_draw

功能：获取现在区域填充模式。

3.get_fix

功能：获取现在查询表的固定模式。

4.get_hsi

功能：获取现在颜色的HSI编码。

5.get_icon

功能：查询区域输出的图标。

6.get_insert

功能：获取现在显示模式。

7.get_line_approx

功能：获取轮廓显示的现在近似误差。

8.get_line_style

功能：获取轮廓的现在图解模式。

9.get_line_width

功能：获取轮廓显示的现在线宽。

10.get_paint

功能：获取灰度值的现在显示模式。

11.get_part

功能：获取图像部分。

12.get_part_style

功能：获取灰度值显示的现在插值模式。

13.get_pixel

功能：获取查询表索引的现在颜色。

14.get_rgb

功能：获取RGB编码中的现在颜色。

15.get_shape

功能：获取现在区域输出形状。

16.query_all_colors

功能：查询所有颜色名称。

17.query_color

功能：查询窗口中显示的所有颜色名称。

18.query_colored

功能：查询颜色输出的颜色数目。

19.query_gray

功能：查询显示的灰度值。

20.query_insert

功能：查询可能的图解模式。

21.query_line_width

功能：查询可能的线宽。

22.query_paint

功能：查询灰度值显示模式。

23.query_shape

功能：查询区域显示模式。

24.set_color

功能：设置输出颜色。

25.set_colored

功能：设置多输出颜色。

26.set_comprise

功能：定义图像矩阵输出剪辑。

27.set_draw

功能：定义区域填充模式。

28.set_fix

功能：设置固定的查询表。

29.set_gray

功能：定义区域输出的灰度值。

30.set_hsi

功能：定义输出颜色（HSI编码）。

31.set_icon

功能：区域输出的图标定义。

32.set_insert

功能：定义图像输出功能。

33.set_line_approx

功能：定义输出显示的近似误差。

34.set_line_style

功能：定义一个轮廓输出模式。

35.set_line_width

功能：定义区域轮廓输出的线宽。

36.set_paint

功能：定义灰度值输出模式。

37.set_part

功能：修正显示图像部分。

38.set_part_style

功能：为灰度值输出定义一个插值方法。

39.set_pixel

功能：定义一个颜色查询表索引。

40.set_rgb

功能：通过RGB值设置颜色定义。

41.set_shape

功能：定义区域输出轮廓。

### 6.7 Text

1.get_font

功能：获取现在字体。

2.get_string_extents

功能：获取一个字符串的空间大小。

3.get_tposition

功能：获取光标位置。

4.get_tshape

功能：获取文本光标的形状。

5.new_line

功能：设置下一行的开始文本光标的位置。

6.query_font

功能：查询可得到的字体。

7.query_tshape

功能：查询文本光标的所有可得到的形状。

8.read_char

功能：从一个文本窗口读取一个字符。

9.read_string

功能：从一个文本窗口读取一个字符串。

10.set_font

功能：设置文本输出的字体。

11.set_tposition

功能：设置文本光标的位置。

12.set_tshape

功能：设置文本光标的形状。

13.write_string

功能：在一个窗口中打印文本。

### 6.8 Window

1.clear_rectangle

功能：在输出窗口中删除一个矩形。

2.clear_window

功能：删除一个输出窗口。

3.close_window

功能：关闭一个输出窗口。

4.copy_rectangle

功能：在输出窗口间复制矩形内所有像素。

5.dump_window

功能：把窗口内容写入一个文件。

6.dump_window_image

功能：在一个图像目标中写窗口内容。

7.get_os_window_handle

功能：获取操作系统图像处理。

8.get_window_attr

功能：获取窗口特征。

9.get_window_extents

功能：一个窗口大小和位置的信息。

10.get_window_pointer3

功能：一个窗口像素数据的通道。

11.get_window_type

功能：获取窗口类型。

12.move_rectangle

功能：在一个输出窗口内部复制。

13.new_extern_window

功能：在Windows_NT下创建一个虚拟图形窗口。

14.open_textwindow

功能：打开一个文本窗口。

15.open_window

功能：打开一个图形窗口。

16.query_window_type

功能：查询所有可得到的窗口类型。

17.set_window_attr

功能：设置窗口特征。

18.set_window_dc

功能：设置一个虚拟图形窗口（Windows_NT）的设计背景。

19.set_window_extents

功能：修正一个窗口的位置和大小。

20.set_window_type

功能：指定一个窗口类型。

21.slide_image

功能：两个窗口缓冲区的交互输出。