# HALCON 算子函数

## Chapter 2 : Develop(外部函数)

| 序号 | 函数名                      | 函数说明及注释                                               | 页码 |
| ---- | --------------------------- | ------------------------------------------------------------ | ---- |
| 1    | dev_clear_obj               | 从Halcon数据库中删除一个不需要的图标物体                     | 23   |
| 2    | dev_clear_window            | 清除活动图形窗口的图形                                       | 24   |
| 3    | dev_close_inspect_ctrl      | 关闭一个控制变量的检查/测量窗口                              | 24   |
| 4    | dev_close_window            | 关闭活动图形窗口                                             | 24   |
| 5    | dev_display                 | 在现有图形窗口中显示图像目标                                 | 24   |
| 6    | dev_error_var               | 定义一个错误变量，并设置是否打开该错误状态                   | 24   |
| 7    | dev_get_exception_data      | 存取一个数组的元素                                           | 24   |
| 8    | dev_get_preferences         | 通过设计查询HDevelop的参数选择                               | 24   |
| 9    | dev_inspect_ctrl            | 打开一个或多个控制变量的监视窗口                             | 24   |
| 10   | dev_map_par                 | 打开一个可视化对话框来设置参数，相当于打开菜单/可视化/设置参数 | 24   |
| 11   | dev_map_prog                | 是HDevelop的主窗口可视化                                     | 24   |
| 12   | dev_map_var                 | 在屏幕上打开一个变量窗口                                     | 25   |
| 13   | dev_open_window             | 打开一个图形窗口                                             | 25   |
| 14   | dev_set_check               | 指定错误检查，检测错误状态是否为 2(H_MSG_TRUE)               | 25   |
| 15   | dev_set_color               | 设置一个颜色用在某个显示region（区域），图形或XLD            | 25   |
| 16   | dev_set_colored             | 设置混合颜色用在某个显示region（区域），图形或XLD            | 25   |
| 17   | dev_set_draw                | 定义区域填充模式                                             | 25   |
| 18   | dev_set_line_width          | 定义区域轮廓输出的线宽                                       | 25   |
| 19   | dev_set_lut                 | 设置颜色查询表                                               | 25   |
| 20   | dev_set_paint               | 定义灰度值输出模式                                           | 25   |
| 21   | dev_set_part                | 在当前窗口显示设定区域大小的图像                             | 26   |
| 22   | dev_set_preferences         | 通过设计设置HDevelop的参数选择                               | 26   |
| 23   | dev_set_shape               | 定于区域输出形状（原始、图形、随意圆、小圆、矩形、椭圆、图标等） | 26   |
| 24   | dev_set_window              | 激活一个图形窗口                                             | 26   |
| 25   | dev_set_window_externs      | 改变一个图形窗口的大小及位置                                 | 26   |
| 26   | dev_unmap_par               | 关闭一个可视化对话框来设置参数                               | 26   |
| 27   | dev_unmap_prog              | 关闭一个Halcon主窗口，关闭一个Halcon软件                     | 26   |
| 28   | dev_unmap_var               | 在屏幕上关闭一个变量窗口                                     | 26   |
| 29   | dev_update_pc               | 在程序执行中指定PC的行为，更新程序计数器                     | 26   |
| 30   | dev_update_time             | 为操作符打开或关闭切换时间测量，显示处理时间                 | 27   |
| 31   | dev_update_var              | 在程序执行中指定活动窗口的行为，更新变量                     | 27   |
| 32   | dev_update_window           | 在程序执行中指定输出行为，更新图像窗口                       | 27   |
| 33   | dev_open_window_fit_image   | 按指定图像的大小来打开一个窗口                               | 27   |
| 34   | dev_open_window_fit_size    | 按指定图像的尺寸开打开一个窗口                               | 27   |
| 35   | dev_resize_window_fit_image | 按图像的大小刷新一个窗口                                     | 28   |
| 36   | dev_resize_window_fit_size  | 按给定的尺寸来刷新一个窗口大小                               | 28   |
| 37   | dev_update_off              | 关闭dev_update_pc/_var/dev_update_window,停止刷新pc/变量/窗口 | 28   |
| 38   | dev_update_on               | 打开dev_update_pc/_var/dev_update_window,停止刷新pc/变量/窗口 | 28   |

## Chapter 3 : Measuring-1D(1D测量)

### 3.1 Measuring-1D高斯混合模型

| 序号 | 函数名                      | 函数说明及注释                                               | 页码 |
| ---- | --------------------------- | ------------------------------------------------------------ | ---- |
| 1    | close_all_measures          | 清除所有测量对象                                             | 31   |
| 2    | close_measure               | 清除一个测量对象                                             | 31   |
| 3    | fuzzy_meausre_pairing       | 模糊测量配对，提取与矩形或环状弧垂直的直线边缘的起点、终点、中间点的坐标值，并提供起点和终点两点之间的间距 | 31   |
| 4    | fuzzy_measure_pairs         | 模糊测量配对，提取与矩形或环状弧垂直的直线边缘的起点、终点、中间点的坐标值，并提供起点和终点两点之间的间距，终点至下一配对起点的间距 | 32   |
| 5    | fuzzy_measure_pos           | 模糊测量配对，提取与矩形或环状弧垂直的直线边缘，提供匹配边缘的中点坐标值，并提供该点至下一匹配点的间距 | 32   |
| 6    | gen_measure_arc             | 提取与圆弧垂直中心轴线的直线边沿，设定ROI                    | 33   |
| 7    | gen_measure_rectangle2      | 提取与矩形垂直中心轴线的直线边沿，设定ROI                    | 33   |
| 8    | measure_pairs               | 提取与矩形或环状弧垂直的直线边缘的起点、终点、中间点的坐标值，并提供起点和终点两点之间的间距，终点至下一配对起点的间距 | 36   |
| 9    | measure_pos                 | 提取与矩形或环状弧垂直的直线边缘，提供匹配边缘的中点坐标值，并提供该点至下一匹配点的间距 | 37   |
| 10   | measure_projection          | 提取垂直与一个矩形或环状弧的灰度值轮廓(contour)              | 38   |
| 11   | measure_thresh              | 提取沿着一个矩形或环状弧，特殊灰度值的点                     | 38   |
| 12   | reset_fuzzy_measure         | 重置一个模糊元函数                                           | 38   |
| 13   | set_fuzzy_measure           | 指定一个模糊元函数                                           | 38   |
| 14   | set_fuzzy_measure_norm_pair | 为边缘匹配指定一个规范画模糊元函数                           | 38   |
| 15   | translate_measure           | 转化（解释）一个测试对象                                     | 39   |

## Chapter 4: Matching-3D(3D匹配)

### 4.1 Shape-Based外形匹配

| 序号 | 函数名                        | 函数说明及注释                                               | 页码 |
| ---- | ----------------------------- | ------------------------------------------------------------ | ---- |
| 1    | clear_all_shape_model_3d      | 清除所有3D轮廓模型，释放内存空间                             | 45   |
| 2    | clear_shape_model_3d          | 清除指定3D轮廓模型，释放内存空间                             | 45   |
| 3    | create_cam_pose_look_at_point | 创建一个3D摄像机位置（从摄像机中心观察方向）                 | 45   |
| 4    | create_shape_model_3d         | 创建一个3D目标模型                                           | 45   |
| 5    | find_shape_model_3d           | 从图像中找出一个3D模型的最佳匹配                             | 46   |
| 6    | get_shape_model_3d_contours   | 提取3D轮廓目标                                               | 46   |
| 7    | get_shape_model_3d_params     | 提取一个3D轮廓模型的参数                                     | 46   |
| 8    | project_shape_model_3d        | 把一个3D轮廓模型的边缘投影到图像坐标中                       | 47   |
| 9    | read_shape_model_3d           | 读取一个3D轮廓模型文件                                       | 47   |
| 10   | trans_pose_shape_model_3d     | 把一个3D目标模型的坐标系中的位置转变为一个3D轮廓模型的参考坐标系中的位置，反之亦然 | 47   |
| 11   | write_shape_model_3d          | 把一个3D轮廓模型保存到文件中                                 | 47   |

### 4.2 Shrface-Based曲面匹配

| 序号 | 函数名                             | 函数说明及注释                       | 页码 |
| ---- | ---------------------------------- | ------------------------------------ | ---- |
| 1    | clear_all_surface_matching_results | 清除所有的曲面匹配目标，释放内存空间 | 48   |
| 2    | clear_all_surface_models           | 清除所有的曲面匹配模型，释放内存空间 | 48   |
| 3    | clear_surface_matching_result      | 清除指定的曲面匹配目标，释放内存空间 | 48   |
| 4    | clear_surface_model                | 清除指定的曲面匹配模型，释放内存空间 | 48   |
| 5    | create_surface_model               | 创建一个曲面匹配模型                 | 48   |
| 6    | find_surface_model                 | 从3D背景中找出最佳匹配               | 48   |
| 7    | get_surface_matching_result        | 提取曲面匹配目标                     | 49   |
| 8    | get_surface_model_param            | 提取曲面匹配模型参数                 | 49   |
| 9    | read_surface_model                 | 读取曲面匹配模型文件                 | 49   |
| 10   | refine_surface_model_pose          | 使3D背景中曲面模型坐标完善           | 49   |
| 11   | write_surface_model                | 将一个曲面匹配模型保存到文件中       | 49   |

## Chapter 5: Reconstruction-3D(3D复原)

### 5.1 Binocular Stereo 双目

| 序号 | 函数名                           | 函数说明及注释                                               | 页码 |
| ---- | -------------------------------- | ------------------------------------------------------------ | ---- |
| 1    | binocular_disparity              | 通过相互关系来计算两个图像的双目视觉差                       | 53   |
| 2    | binocular_disparity_mg           | 通过多格子方法来计算两个图像的双目视觉差                     | 54   |
| 3    | binocular_distance               | 通过相互关系来计算两个立体图像的双目视觉差                   | 54   |
| 4    | binocular_distance_mg            | 通过多格子方法来计算两个立体图像的双目视觉差                 | 54   |
| 5    | disparity_image_to_xyz           | 把一个观影距离转变成一个被矫正的3D立体点                     | 55   |
| 6    | disparity_to_distance            | 将观影距离转换为矫正双目视觉立体系统中的间隔值               | 55   |
| 7    | disparity_to_point_3d            | 将一个图像点和它的观影距离转换为一个矫正立体系统中的三维点   | 55   |
| 8    | distance_to_disparity            | 将一个间隔值转换为一个矫正立体系统中的观影距离               | 56   |
| 9    | essential_to_fundamental_matrix  | 计算一个从原始矩阵衍生而来的基础矩阵                         | 56   |
| 10   | gen_binocular_proj_rectification | 计算双目视觉立体系统图像的投射矫正值                         | 56   |
| 11   | gen_binocular_rectification_map  | 创建转换图，其描述从一个双目相机到一个普通的矫正图像面的图像映射 | 56   |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |
|      |                                  |                                                              |      |

### 4.1 Shape-Based外形匹配

| 序号 | 函数名 | 函数说明及注释 | 页码 |
| ---- | ------ | -------------- | ---- |
|      |        |                |      |
|      |        |                |      |

### 4.1 Shape-Based外形匹配

| 序号 | 函数名 | 函数说明及注释 | 页码 |
| ---- | ------ | -------------- | ---- |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |

### 4.1 Shape-Based外形匹配

| 序号 | 函数名 | 函数说明及注释 | 页码 |
| ---- | ------ | -------------- | ---- |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |

### 4.1 Shape-Based外形匹配

| 序号 | 函数名 | 函数说明及注释 | 页码 |
| ---- | ------ | -------------- | ---- |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |
|      |        |                |      |