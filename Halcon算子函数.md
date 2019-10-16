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

| 序号 | 函数名                            | 函数说明及注释                                               | 页码 |
| ---- | --------------------------------- | ------------------------------------------------------------ | ---- |
| 1    | binocular_disparity               | 通过相互关系来计算两个图像的双目视觉差                       | 53   |
| 2    | binocular_disparity_mg            | 通过多格子方法来计算两个图像的双目视觉差                     | 54   |
| 3    | binocular_distance                | 通过相互关系来计算两个立体图像的双目视觉差                   | 54   |
| 4    | binocular_distance_mg             | 通过多格子方法来计算两个立体图像的双目视觉差                 | 54   |
| 5    | disparity_image_to_xyz            | 把一个观影距离转变成一个被矫正的3D立体点                     | 55   |
| 6    | disparity_to_distance             | 将观影距离转换为矫正双目视觉立体系统中的间隔值               | 55   |
| 7    | disparity_to_point_3d             | 将一个图像点和它的观影距离转换为一个矫正立体系统中的三维点   | 55   |
| 8    | distance_to_disparity             | 将一个间隔值转换为一个矫正立体系统中的观影距离               | 56   |
| 9    | essential_to_fundamental_matrix   | 计算一个从原始矩阵衍生而来的基础矩阵                         | 56   |
| 10   | gen_binocular_proj_rectification  | 计算双目视觉立体系统图像的投射矫正值                         | 56   |
| 11   | gen_binocular_rectification_map   | 创建转换图，其描述从一个双目相机到一个普通的矫正图像面的图像映射 | 56   |
| 12   | intersect_lines_of_sight          | 从一个双目相机系统视觉中两条线的交点中获取一个三维点         | 57   |
| 13   | match_essential_matrix_ransack    | 通过自动发掘图像点间对应关系来计算立体图像对应的原始（本质）矩阵 | 57   |
| 14   | match_fundamental_matrix_ransack  | 通过自动发掘图像点间对应关系来计算立体图像对应的基本矩阵     | 58   |
| 15   | match_rel_pose_ransack            | 通过自动发掘图像点间对应关系来计算两个相机间的相对方位       | 58   |
| 16   | reconst3d_from_fundamental_matrix | 计算基于基本矩阵点投影的三位重建                             | 59   |
| 17   | rel_pose_to_fundamental_matrix    | 计算两个相机相关方向中获取的基本矩阵                         | 60   |
| 18   | vector_to_essential_matrix        | 计算给定图像点间映射和已知相机矩阵的原始矩阵，重建三维点     | 60   |
| 19   | vector_to_fundamental_matrix      | 计算给定图像点间映射的集合的基本矩阵，重建三维点             | 60   |
| 20   | vector_to_rel_pose                | 计算给定图像点对应关系和已知相机参数的两相机间相对方位，重建三维点 | 61   |

### 5.2 Depth From Focus 焦点深度

| 序号 | 函数名                          | 函数说明及注释                         | 页码 |
| ---- | ------------------------------- | -------------------------------------- | ---- |
| 1    | depth_from_focus                | 利用多倍聚集灰度级提取高度（厚度）     | 62   |
| 2    | select_grayvalues_from_channels | 利用索引图像选择一个多通道图像的灰度值 | 62   |

### 5.3 Multi-View Stereo 多视角立体模型

| 序号 | 函数名                       | 函数说明及注释                         | 页码 |
| ---- | ---------------------------- | -------------------------------------- | ---- |
| 1    | clear_all_stereo_models      | 清除所有的多视角立体模型，释放内存空间 | 62   |
| 2    | clear_stereo_model           | 清除指定的多视角立体模型，释放内存空间 | 62   |
| 3    | create_stereo_model          | 创建一个多视角立体模型                 | 62   |
| 4    | get_stereo_model_image_pairs | 获取立体模型中双目（成对）图像的列表   | 62   |
| 5    | get_stereo_model_object      | 获取立体重建的中间结果（图标）         | 63   |
| 6    | get_stereo_model_param       | 提取多视角立体模型参数                 | 63   |
| 7    | reconstruct_points_stereo    | 重建多视角立体3D参考点                 | 63   |
| 8    | reconstruct_surface_stereo   | 重建多视角3D曲面                       | 63   |
| 9    | set_stereo_model_image_pairs | 指定双目（成对）图像的表面立体重建     | 63   |
| 10   | set_stereo_model_param       | 设置多视角立体模型参数                 | 64   |

### 5.4 Photometric Stereo 估测光源

| 序号 | 函数名             | 函数说明及注释                         | 页码 |
| ---- | ------------------ | -------------------------------------- | ---- |
| 1    | estimate_al_am     | 估测一个平面的反射率和反射光的数目     | 64   |
| 2    | estimate_sl_al_lr  | 估测一个光源的倾斜度和一个平面的反射率 | 64   |
| 3    | estimate_sl_al_zc  | 估测一个光源的倾斜度和一个平面的反射率 | 64   |
| 4    | estimate_tilt_lr   | 估测一个光源的倾斜                     | 65   |
| 5    | estimate_tilt_zc   | 估测一个光源的倾斜                     | 65   |
| 6    | phot_stereo        | 根据至少三个灰度值的图像来重建一个平面 | 65   |
| 7    | sfs_mod_lr         | 从一个灰度值图像重建一个平面           | 65   |
| 8    | sfs_orig_lr        | 从一个灰度值图像重建一个平面           | 66   |
| 9    | sfs_pentland       | 从一个灰度值图像重建一个平面           | 66   |
| 10   | shade_height_field | 重建一个表面灰色突起的图像             | 66   |

### 5.5 Sheet of Light 片光

| 序号 | 函数名                                    | 函数说明及注释                               | 页码 |
| ---- | ----------------------------------------- | -------------------------------------------- | ---- |
| 1    | apply_sheet_of_light_calibration          | 应用校准变换到不一致的图像                   | 67   |
| 2    | clear_all_sheet_of_light_models           | 清除所有的片光模型，释放内存空间             | 67   |
| 3    | clear_sheet_of_light_model                | 清除指定片光模型，释放内存空间               | 67   |
| 4    | create_sheet_of_light_model               | 创建一个基于3D测量的片光模型                 | 67   |
| 5    | get_sheet_of_light_param                  | 提取片光模型的参数                           | 68   |
| 6    | get_sheet_of_light_result                 | 提取一个通过片光技术获得的测量结果（图标）   | 68   |
| 7    | get_sheet_of_light_result_object_model_3d | 提取一个通过片光技术获得的3D对象模型测量结果 | 68   |
| 8    | measure_profile_sheet_of_light            | 对输入和存储的轮廓图像记性片光技术处理       | 68   |
| 9    | query_sheet_of_light_params               | 提取参数列表                                 | 68   |
| 10   | set_sheet_of_light_param                  | 设置片光模型对应的参数                       | 68   |

## Chapter 6: 3D Tools(3D工具)

### 6.1 3D Object Model_3D 模型

| 序号 | 函数名                       | 函数说明及注释                          | 页码 |
| ---- | ---------------------------- | --------------------------------------- | ---- |
| 1    | affine_trans_object_model_3d | 应用校准变换到不一致的图像              | 73   |
| 2    | clear_all_object_model_3d    | 清除所有的片光模型，释放内存空间        | 73   |
| 3    | clear_object_model_3d        | 清除指定片光模型，释放内存空间          | 73   |
| 4    | copy_object_model_3d         | 创建一个基于3D测量的片光模型            | 73   |
| 5    | get_object_model_3d_params   | 提取一个3D对象模型的参数                | 73   |
| 6    | object_model_3d_to_xyz       | 把3D对象模型坐标变换到图像中            | 74   |
| 7    | prepare_object_model_3d      | 3D对象模型准备执行某一个操作            | 74   |
| 8    | project_object_model_3d      | 把一个3D对象模型的边沿投影到图像坐标中  | 74   |
| 9    | read_object_model_3d_dxf     | 读取一个3D对象模型，该文件格式为dxf格式 | 74   |
| 10   | write_object_model_3d        | 读取一个3D对象模型，该文件格式为dxf格式 | 74   |
| 11   | xyz_to_object_model_3d       | 把图像中对应的3D坐标转换到3D对象模型中  | 75   |

### 3D Segmentation_3D分割

| 序号 | 函数名                           | 函数说明及注释                   | 页码 |
| ---- | -------------------------------- | -------------------------------- | ---- |
| 1    | apply_sheet_of_light_calibration | 应用校准变换到不一致的图像       | 75   |
| 2    | segment_object_model_3d          | 清除所有的片光模型，释放内存空间 | 75   |

## Chapter 7: Calibration(校准)

### 7.1 Binocular 双目相机

| 序号 | 函数名                | 函数说明及注释       | 页码 |
| ---- | --------------------- | -------------------- | ---- |
| 1    | binocular_calibration | 测试双目相机系统参数 | 79   |

### 3D Segmentation_3D分割

| 序号 | 函数名              | 函数说明及注释                                         | 页码 |
| ---- | ------------------- | ------------------------------------------------------ | ---- |
| 1    | caltab_points       | 从标定板文件中读取标志的中心点                         | 79   |
| 2    | create_caltab       | 创建一个标定板描述文件和附加文件                       | 80   |
| 3    | disp_caltab         | 投射和视觉化图像中标定板的三维模型                     | 80   |
| 4    | find_caltab         | 在图像中根据标定板找出对应的区域                       | 80   |
| 5    | find_marks_and_pose | 从图像中提取二维校准标志和外部计算机参数来计算内部数值 | 80   |
| 6    | gen_caltab          | 创建一个标定板文件和相应的附文件                       | 81   |
| 7    | sim_caltab          | 根据标定板模拟一副图像                                 | 81   |

### 7.3 Camera Parameters 相机参数

| 序号 | 函数名             | 函数说明及注释                   | 页码 |
| ---- | ------------------ | -------------------------------- | ---- |
| 1    | cam_mat_to_cam_par | 从相机矩阵来获取的内部相机参数   | 81   |
| 2    | cam_par_to_cam_mat | 从相机内存参数来获取一个相机矩阵 | 81   |
| 3    | read_cam_par       | 从文本文件中读取内部相机参数     | 81   |
| 4    | write_cam_par      | 将内部相机参数写入文本文件中     | 82   |

### 7.4 Hand-Eye 手眼校正（机械手视觉校正）

| 序号 | 函数名               | 函数说明及注释   | 页码 |
| ---- | -------------------- | ---------------- | ---- |
| 1    | hand_eye_calibration | 执行一个手眼校准 | 82   |

### 7.5 Monocular 单目镜

| 序号 | 函数名             | 函数说明及注释                         | 页码 |
| :--- | ------------------ | -------------------------------------- | ---- |
| 1    | camera_calibration | 测顶同时发生的最小化程序的所有相机参数 | 82   |
| 2    | project_3d_point   | 将三维点投射到子像素图像坐标           | 83   |

### 7.6 Multi-View 多视角（校准或者矫正）

| 序号 | 函数名                          | 函数说明及注释                                       | 页码 |
| ---- | ------------------------------- | ---------------------------------------------------- | ---- |
| 1    | calibrate_cameras               | 矫正相机                                             | 83   |
| 2    | clear_all_calib_data            | 清除所有的矫正数据模型，释放内存空间                 | 83   |
| 3    | clear_all_camera_setup_models   | 清除所有的相机设备模式，释放内存空间                 | 84   |
| 4    | clear_calib_data                | 清除指定的矫正数据模型，释放内存空间                 | 84   |
| 5    | clear_camera_setup_model        | 清除指定的相机设备模式，释放内存空间                 | 84   |
| 6    | create_calib_data               | 创建一个矫正数据模型                                 | 84   |
| 7    | create_camera_setup_model       | 创建一个相机设备模式                                 | 84   |
| 8    | get_calib_data                  | 提取矫正数据模型参数                                 | 84   |
| 9    | get_calib_data_observ_points    | 提取标定板上圆点的中心坐标和各个校正目标物体的坐标系 | 84   |
| 10   | get_camera_setup_param          | 提取相机设备模式的参数                               | 85   |
| 11   | query_calib_data_observ_indices | 获取指定的（相机对应的被测）                         | 85   |
| 12   | read_calib_data                 | 读取矫正数据模型对应的文件                           | 85   |
| 13   | read_camera_setup_model         | 读取相机设备模式对应的文件                           | 85   |
| 14   | set_calib_data                  | 配置矫正数据模型                                     | 85   |
| 15   | set_calib_data_calib_object     | 指定矫正对象                                         | 86   |
| 16   | set_calib_data_cam_param        | 相机的类型，初始化相机内存参数                       | 86   |
| 17   | set_calib_data_observ_points    | 设置标定板上圆点的中心坐标和各个校正目标物体的坐标系 | 86   |
| 18   | set_camera_setup_cam_param      | 设置相机设备模式，默认类型，参数和相等坐标点         | 87   |
| 19   | set_cameras_setup_param         | 配置相机设备模式参数                                 | 87   |
| 20   | write_calib_data                | 保存矫正数据模型到一个文件中                         | 87   |
| 21   | write_camera_setup_model        | 保存相机设备模式参数到一个文件中                     | 87   |

### 7.7 Rectification 矫正

| 序号 | 函数名                                | 函数说明及注释                                 | 页码 |
| ---- | ------------------------------------- | ---------------------------------------------- | ---- |
| 1    | change_radial_distortion_cam_par      | 依照测定的径向畸变决定相机的新参数             | 87   |
| 2    | change_radial_distortion_contours_xld | 矫正轮廓的畸变                                 | 88   |
| 3    | change_radial_distortion_image        | 矫正图像的畸变                                 | 88   |
| 4    | change_radial_distortion_points       | 矫正像素坐标的畸变                             | 88   |
| 5    | contour_to_world_plane_xld            | 把xld轮廓转为大地坐标系统，z轴为0，即没有z轴   | 88   |
| 6    | gen_image_to_world_plane_map          | 生成一张投影图，在大地坐标系中描绘该图像的映射 | 88   |
| 7    | gen_radial_distortion_map             | 生成一张投影图，改变图像像素的径向畸变         | 89   |
| 8    | image_points_to_world_plane           | 在大地坐标系中变换图像像素点                   | 89   |
| 9    | image_to_world_plane                  | 矫正一副图像，把它转换为大地坐标               | 89   |

### 7.8 Self-Calibration 自动矫正

| 序号 | 函数名                             | 函数说明及注释                 | 页码 |
| ---- | ---------------------------------- | ------------------------------ | ---- |
| 1    | radial_distortion_self_calibration | 校准畸变                       | 89   |
| 2    | radiometric_self_calibration       | 矫正相机曝光                   | 90   |
| 3    | stationary_camera_self_calibration | 对已经固定的照相机执行自动矫正 | 90   |

## Chapter 8: Classification(分类)

### 8.1 Gaussian-Mixture-Models 高斯混合模型

| 序号 | 函数名                   | 函数说明及注释                                     | 页码 |
| ---- | ------------------------ | -------------------------------------------------- | ---- |
| 1    | add_sample_class_gmm     | 把一个模型范本添加到一个高斯混合模型的范本数据库上 | 95   |
| 2    | classify_class_gmm       | 通过一个高斯混合模型来计算一个特征向量的类         | 95   |
| 3    | clear_all_class_gmm      | 清除所有高斯混合模型                               | 95   |
| 4    | clear_class_gmm          | 清除一个高斯混合模型                               | 95   |
| 5    | clear_samples_class_gmm  | 清除一个高斯混合模型的范本数据库                   | 95   |
| 6    | create_class_gmm         | 创建一个高斯混合模型分类                           | 96   |
| 7    | evaluate_class_gmm       | 通过一个高斯混合模型评价一个特征向量               | 96   |
| 8    | get_params_class_gmm     | 提取一个高斯混合模型的参数                         | 96   |
| 9    | get_prep_info_class_gmm  | 提取一个高斯混合模型的预处理特征向量的信息内容     | 96   |
| 10   | get_sample_class_gmm     | 提取一个高斯混合模型的模型范本                     | 96   |
| 11   | get_sample_num_class_gmm | 提取一个高斯混合模型的样品模型的数量               | 97   |
| 12   | read_class_gmm           | 从一个文件中读取一个高斯混合模型                   | 97   |
| 13   | read_samples_class_gmm   | 从一个文件中读取一个高斯混合模型范本               | 97   |
| 14   | train_class_gmm          | 训练一个高斯混合模型                               | 97   |
| 15   | write_class_gmm          | 向一个文件中写入高斯混合模型                       | 97   |
| 16   | write_samples_class_gmm  | 向一个文件中写入高斯混合模型的范本数据             | 97   |

### 8.2 Hyperboxed 分类器

| 序号 | 函数名                   | 函数说明及注释                       | 页码 |
| ---- | ------------------------ | ------------------------------------ | ---- |
| 1    | clear_sampset            | 释放一个数据集                       | 98   |
| 2    | close_all_class_box      | 关闭所有分类器                       | 98   |
| 3    | close_class_box          | 关闭指定分类器                       | 98   |
| 4    | create_class_box         | 创建一个新的分类器                   | 98   |
| 5    | descript_class_box       | 分类器的描述                         | 98   |
| 6    | enquire_class_box        | 为一组属性分类                       | 98   |
| 7    | enquire_reject_class_box | 为一组带抑制类的属性分类             | 98   |
| 8    | get_class_box_param      | 获取分类器对应的参数信息             | 98   |
| 9    | learn_class_box          | 分类器范本                           | 99   |
| 10   | learn_sampset_box        | 用数据组指定分类器范本               | 99   |
| 11   | read_class_box           | 从一个文件中读取分类器               | 99   |
| 12   | read_sampset             | 从一个文件中读取一个分类器范本数据集 | 99   |
| 13   | set_class_box_param      | 为分类器设置系统参数                 | 99   |
| 14   | test_sampset_box         | 为一组数组分类                       | 99   |
| 15   | write_class_box          | 将分类器保存到文件中                 | 99   |

### 8.3 Look_Up Table 颜色查询表

| 序号 | 函数名               | 函数说明及注释                                    | 页码 |
| ---- | -------------------- | ------------------------------------------------- | ---- |
| 1    | clear_all_class_lut  | 清除所有的颜色查找表分类器                        | 100  |
| 2    | clear_class_lut      | 清除指定的颜色查找表分类器                        | 100  |
| 3    | create_class_lut_gmm | 产生一个基于高斯矩阵模型（gmm）的颜色查找表分类器 | 100  |
| 4    | create_class_lut_mlp | 产生一个基于多层感知器（mlp）的颜色查找表分类器   | 100  |
| 5    | create_class_lut_svn | 产生一个基于支持向量机（svm）的颜色查找表分类器   | 100  |

### 8.4 Neural-Nets 感知网络

| 序号 | 函数名                   | 函数说明及注释                               | 页码 |
| ---- | ------------------------ | -------------------------------------------- | ---- |
| 1    | add_sample_class_mlp     | 把一个范文添加到一个多层感知器的范本数据集中 | 101  |
| 2    | classify_class_mlp       | 通过一个多层感知器计算一个特征向量的类       | 101  |
| 3    | clear_all_class_mlp      | 清除所有多层感知器                           | 101  |
| 4    | clear_class_mlp          | 清除一个指定的多层感知器                     | 101  |
| 5    | clear_samples_class_mlp  | 清除一个多层感知器的范本数据                 | 101  |
| 6    | create_class_mlp         | 为样式分类创建一个多层感知器                 | 102  |
| 7    | evaluate_class_mlp       | 通过一个多层感知器计算一个特征向量的评估     | 102  |
| 8    | get_params_class_mlp     | 提取一个多层感知器的参数                     | 102  |
| 9    | get_prep_info_class_mlp  | 提取一个多层感知器的预处理特征向量的信息内容 | 102  |
| 10   | get_sample_class_mlp     | 提取一个多层感知器的范本                     | 102  |
| 11   | get_sample_num_class_mlp | 提取一个多层感知器的范本数量                 | 102  |
| 12   | read_class_mlp           | 从一个文件中读取一个多层感知器               | 102  |
| 13   | read_samples_class_mlp   | 从一个文件中读取一个多层感知器的范本数据     | 103  |
| 14   | train_class_mlp          | 训练多层感知器                               | 103  |
| 15   | write_class_mlp          | 向一个文件中写入一个多层感知器               | 103  |
| 16   | write_samples_classs_mlp | 向一个文件中写入一个多层感知器的范本数据     | 103  |

### 8.5 Support-Vector-Machines 矢量

| 序号 | 函数名                           | 函数说明及注释                                               | 页码 |
| ---- | -------------------------------- | ------------------------------------------------------------ | ---- |
| 1    | add_sample_class_svm             | 把一个范本添加到一个支持向量机的训练数据上                   | 104  |
| 2    | classify_class_svm               | 通过一个支持向量机为一个特征向量分类                         | 104  |
| 3    | clear_all_class_svm              | 清除所有支持向量机                                           | 104  |
| 4    | clear_class_svm                  | 清除一个支持向量机                                           | 104  |
| 5    | clear_samples_class_svm          | 清除一个支持向量机的范本数据                                 | 104  |
| 6    | create_class_svm                 | 为模式分类创建一个支持向量机                                 | 104  |
| 7    | get_params_class_svm             | 提取一个支持向量机的参数                                     | 105  |
| 8    | get_prep_info_class_svm          | 提取一个支持向量机的预处理特征向量的信息内容                 | 105  |
| 9    | get_sample_class_svm             | 提取一个支持向量机的范本                                     | 105  |
| 10   | get_sample_num_class_svm         | 提取一个支持向量机范本的数量                                 | 105  |
| 11   | get_support_vector_class_svm     | 提取一个支持向量机范本的索引                                 | 105  |
| 12   | get_support_vector_num_class_svm | 提取一个支持向量机中支持向量的数量                           | 105  |
| 13   | read_class_svm                   | 从一个文件中读取一个支持向量机                               | 106  |
| 14   | read_samples_class_svm           | 从一个文件中读取一个支持向量机的范本数据                     | 106  |
| 15   | reduce_class_svm                 | 根据一个简化的支持向量机来近似一个范本的支持向量机（为了更快分类） | 106  |
| 16   | train_class_svm                  | 训练一个支持向量机模型                                       | 106  |
| 17   | write_class_svm                  | 向一个文件中写入一个支持向量机                               | 106  |
| 18   | write_samples_class_svm          | 向一个文件中写入一个支持向量机的示范数据                     | 106  |

## Chapter 9: File(文件)

### 9.1 Images  图像

| 序号 | 函数名           | 函数说明及注释                   | 页码 |
| ---- | ---------------- | -------------------------------- | ---- |
| 1    | read_image       | 读取不同文件格式的图像           | 109  |
| 2    | read_sequence    | 读取图像                         | 109  |
| 3    | write_image      | 用图形格式写图像                 | 109  |
| 4    | list_image_files | 获取所有图像文件的目录           | 109  |
| 5    | parse_filename   | 获取图像的文件描述，后缀名及目录 | 109  |

### 9.2 Misc 混合体

| 序号 | 函数名          | 函数说明及注释                       | 页码 |
| ---- | --------------- | ------------------------------------ | ---- |
| 1    | delete_file     | 删除一个文件                         | 110  |
| 2    | file_exists     | 检查文件是否存在                     | 110  |
| 3    | list_files      | 列出目录中的所有文件                 | 111  |
| 4    | read_world_file | 从一个ARC/INFO世界文件中读取地理编码 | 111  |

### 9.3 Region 区域

| 序号 | 函数名       | 函数说明及注释             | 页码 |
| ---- | ------------ | -------------------------- | ---- |
| 1    | read_region  | 读取二值图像或者HALCON区域 | 111  |
| 2    | write_region | 在文件中写入区域           | 112  |

### 9.4 Text 文

| 序号 | 函数名          | 函数说明及注释               | 页码 |
| ---- | --------------- | ---------------------------- | ---- |
| 1    | close_all_files | 关闭所有打开的文件           | 112  |
| 2    | close_file      | 关闭一个文本文件             | 112  |
| 3    | fnew_line       | 创建一个换行符               | 112  |
| 4    | fread_char      | 从一个文本文件中读取一个字符 | 112  |
| 5    | fread_line      | 从一个文本文件中读取一行     | 113  |
| 6    | fread_string    | 从一个文本文件中读取字符串   | 113  |
| 7    | fwrite_string   | 向一个文本文件中写入值       | 113  |
| 8    | open_file       | 打开文本文件                 | 113  |

### 9.5 Tuple 数组

| 序号 | 函数名      | 函数说明及注释           | 页码 |
| ---- | ----------- | ------------------------ | ---- |
| 1    | read_tuple  | 从一个文件中读取一个数组 | 113  |
| 2    | write_tuple | 向一个文件中写入一个数组 | 114  |

### 9.6 XLD

| 序号 | 函数名                     | 函数说明及注释                                | 页码 |
| ---- | -------------------------- | --------------------------------------------- | ---- |
| 1    | read_contour_xld_arc_info  | 从用ARC/INFO生成格式表示的文件读取XLD轮廓     | 114  |
| 2    | read_contour_xld_dxf       | 从一个DXF文件汇总读取XLD轮廓。DXF:CAD绘图格式 | 114  |
| 3    | read_polygon_xld_arc_info  | 从用ARC/INFO生成格式表示的文件读取XLD多边形   | 114  |
| 4    | read_polygon_xld_dxf       | 从一个DXF文件中读取XLD多边形                  | 115  |
| 5    | write_contour_xld_arc_info | 向用ARC/INFO生成格式表示的文件写入XLD轮廓     | 115  |
| 6    | write_contour_xld_dxf      | 向一个DXF格式的文件中写入XLD轮廓              | 115  |
| 7    | write_polygon_xld_arc_info | 向用ARC/INFO生成格式表示的文件写入XLD多边形   | 115  |
| 8    | write_polygon_xld_dxf      | 向一个DXF格式的文件中写入XLD多边形            | 115  |

## Chapter 10: Filter(过滤)

### 10.1 Arithmetic 图像算数处理

| 序号 | 函数名         | 函数说明及注释               | 页码 |
| ---- | -------------- | ---------------------------- | ---- |
| 1    | abs_diff_image | 计算两个图像的绝对差别       | 119  |
| 2    | abs_image      | 计算一个图像的绝对值（模数） | 119  |
| 3    | add_image      | 使两个图像相加               | 120  |
| 4    | div_image      | 使两个图像相除               | 120  |
| 5    | invert_image   | 使一个图像反像               | 121  |
| 6    | max_image      | 按像素计算两个图像的最大值   | 121  |
| 7    | min_image      | 按像素计算两个图像的最小值   | 121  |
| 8    | mult_image     | 使两个图像相乘               | 122  |
| 9    | scale_image    | 为一个图像的灰度值分级       | 122  |
| 10   | sqrt_image     | 计算一个图像的平方根         | 123  |
| 11   | sub_image      | 使两个图像相减               | 123  |

### 10.2 Bit 图位像素处理

| 序号 | 函数名     | 函数说明及注释                   | 页码 |
| ---- | ---------- | -------------------------------- | ---- |
| 1    | bit_and    | 输入图像对应的所有像素的逐位与   | 124  |
| 2    | bit_lshift | 图像对应的所有像素的左移         | 124  |
| 3    | bit_mask   | 使用位掩码对每个像素的逻辑与     | 125  |
| 4    | bit_not    | 对像素的所有位进行求补           | 125  |
| 5    | bit_or     | 输入图像对应的所有像素的逐位或   | 125  |
| 6    | bit_rshift | 图像对应的所有像素的右移         | 126  |
| 7    | bit_slice  | 从像素中提取一位                 | 126  |
| 8    | bit_xor    | 输入图像对应的所有像素的逐位异或 | 127  |

### 10.3 Color图像颜色处理

| 序号 | 函数名                     | 函数说明及注释                                       | 页码 |
| ---- | -------------------------- | ---------------------------------------------------- | ---- |
| 1    | apply_color_trans_lut      | 申请使用颜色查找表（lut）                            | 127  |
| 2    | cfa_to_rgb                 | 把一个单通道颜色滤波阵列图像（带RGB成分）变成RGB图像 | 127  |
| 3    | clear_all_color_trans_luts | 清除所有的颜色查找表，释放内存空间                   | 127  |
| 4    | clear_color_trans_lut      | 清除颜色查找表，释放内存空间                         | 128  |
| 5    | create_color_trans_lut     | 创建一个颜色查询表，该表为RGB图像提供转换服务        | 128  |
| 6    | gen_principal_comp_trans   | 计算多通道图像的PCA（主要部分分析）的转换矩阵        | 128  |
| 7    | linear_trans_color         | 计算多通道图像的颜色值的一个仿射变换                 | 128  |
| 8    | principal_comp             | 计算多通道图像的PCA（主要部分分析）                  | 128  |
| 9    | rgb1_to_gray               | 把一个RGB图像转变成一个灰度图像                      | 128  |
| 10   | rgb3_to_gray               | 把一个RGB图像转变成一个灰度图像                      | 128  |
| 11   | trans_from_rgb             | 把一个图像从RGB颜色空间转变成任意颜色空间            | 129  |
| 12   | trans_to_rgb               | 把一个图像从任意颜色空间转变成RGB颜色空间            | 129  |

### 10.4 Edges 图像边沿处理

| 序号 | 函数名              | 函数说明及注释                                             | 页码 |
| ---- | ------------------- | ---------------------------------------------------------- | ---- |
| 1    | close_edges         | 使用边缘幅值图像清除边缘缺陷                               | 131  |
| 2    | close_edges_length  | 使用边缘幅值图像清除边缘缺陷                               | 131  |
| 3    | derivate_gauss      | 用高斯派生物对一个图像卷积                                 | 132  |
| 4    | diff_of_gauss       | 近似高斯的拉普拉斯算子                                     | 133  |
| 5    | edges_color         | 使用Canny、Deriche或者Shen滤波器提取颜色边缘               | 133  |
| 6    | edges_color_sub_pix | 使用Canny、Deriche或者Shen滤波器提取子像素精确颜色边缘     | 134  |
| 7    | edges_image         | 使用Deriche、Lanser、Shen或者Canny滤波器提取边缘           | 134  |
| 8    | edges_sub_pix       | 使用Deriche、Lanser、Shen或者Canny滤波器提取子像素精确边缘 | 135  |
| 9    | frei_amp            | 使用Frei-Chen算子检测边缘（幅值）                          | 136  |
| 10   | frei_dir            | 使用Frei-Chen算子检测边缘（幅值和相位）                    | 136  |
| 11   | highpass_image      | 从一个图像提取高频成分                                     | 137  |
| 12   | info_edges          | 在edges_image估计滤波器的宽度                              | 137  |
| 13   | kirsch_amp          | 使用Kirsch算子检测边缘（幅值）                             | 138  |
| 14   | kirsch_dir          | 使用Kirsch算子检测边缘（幅值和相位）                       | 138  |
| 15   | laplace             | 使用有限差计算拉普拉斯算子                                 | 139  |
| 16   | laplace_of_gauss    | 高斯的拉普拉斯算子                                         | 139  |
| 17   | prewitt_amp         | 使用Prewitt算子检测边缘（幅值）                            | 140  |
| 18   | prewitt_dir         | 使用Prewitt算子检测边缘（幅值和相位）                      | 140  |
| 19   | roberts             | 使用Roberts滤波器检测边缘                                  | 141  |
| 20   | robinson_amp        | 使用Robinson算子检测边缘（幅值）                           | 141  |
| 21   | robinson_dir        | 使用Robinson算子检测边缘（幅值和相位）                     | 142  |
| 22   | sobel_amp           | 使用Sobel算子检测边缘（幅值）                              | 142  |
| 23   | sobel_dir           | 使用Sobel算子检测边缘（幅值和相位）                        | 143  |

### 10.5 Enhancement 增强图形

| 序号 | 函数名                   | 函数说明及注释                         | 页码 |
| ---- | ------------------------ | -------------------------------------- | ---- |
| 1    | coherence_enhancing_diff | 执行图像的一致性增强扩散               | 143  |
| 2    | emphasize                | 增强图像对比度                         | 144  |
| 3    | equ_histo_image          | 图像的柱状线性比                       | 144  |
| 4    | illuminate               | 增强图像对比度                         | 145  |
| 5    | mean_curvature_flow      | 把平均曲率应用在一个图像中             | 145  |
| 6    | scale_image_max          | 增强图像反差，最大灰度值在0到255范围内 | 146  |
| 7    | shock_filter             | 把一个冲击滤波器应用到一个图像中       | 146  |

### 10.6 FFT快速博氏变换算法

| 序号 | 函数名                      | 函数说明及注释                            | 页码 |
| ---- | --------------------------- | ----------------------------------------- | ---- |
| 1    | convol_fft                  | 用在频域内的滤波器使一个图像卷积          | 148  |
| 2    | convol_gabor                | 用在频域内的一个Gabor滤波器使一个图像卷积 | 148  |
| 3    | correlation_ffg             | 计算在频域内的两个图像的相互关系          | 148  |
| 4    | energy_gabor                | 计算一个两通道图像的能量                  | 149  |
| 5    | fft_generic                 | 计算一个图像的快速傅里叶变换              | 149  |
| 6    | fft_image                   | 计算一个图像的快速傅里叶变换              | 149  |
| 7    | fft_image_inv               | 计算一个图像的快速傅里叶逆变换            | 150  |
| 8    | gen_bandfilter              | 生成一个理想带状滤波器                    | 150  |
| 9    | gen_bandpass                | 生成一个理想带通滤波器                    | 151  |
| 10   | gen_derivative_filter       | 在频域内生成一个派生滤波器                | 151  |
| 11   | gen_filter_mask             | 在空域内存储一个滤波器掩码作为实时图像    | 152  |
| 12   | gen_gabor                   | 生成一个Gabor滤波器                       | 153  |
| 13   | gen_gauss_filter            | 在频域内生成一个高斯滤波器                | 153  |
| 14   | gen_highpass                | 生成一个理想高通滤波器                    | 154  |
| 15   | gen_lowpass                 | 生成一个理想低通滤波器                    | 154  |
| 16   | gen_mean_filter             | 生成一个均值滤波器                        | 155  |
| 17   | gen_sin_bandpass            | 用正弦形状生成一个带通滤波器              | 155  |
| 18   | gen_std_bandpass            | 用高斯或者正弦形状生成一个带通滤波器      | 156  |
| 19   | optimize_fft_speed          | 使FFT的运行时间最优化                     | 156  |
| 20   | optimize_rft_speed          | 使实值的FFT的运行时间最优化               | 156  |
| 21   | phase_deg                   | 返回用角度表示一个复杂图像的相位          | 157  |
| 22   | phase_rad                   | 返回用弧度表示一个复杂图像的相位          | 157  |
| 23   | power_byte                  | 返回一个复杂图像的功率谱                  | 157  |
| 24   | power_ln                    | 返回一个复杂图像的功率谱                  | 158  |
| 25   | power_real                  | 返回一个复杂图像的功率谱                  | 158  |
| 26   | read_fft_optimization_data  | 从一个文件中下载FFT速度最优数据           | 158  |
| 27   | rft_generic                 | 计算一个图像的实值快速傅里叶变换          | 158  |
| 28   | write_fft_optimization_data | 把FFT速度最优数据存储在一个文件中         | 159  |

### 10.7 Geometric-Transformations 图像几何变换

| 序号 | 函数名                      | 函数说明及注释                                   | 页码 |
| ---- | --------------------------- | ------------------------------------------------ | ---- |
| 1    | affine_trans_image          | 把任意仿射2D变换应用在图像中                     | 159  |
| 2    | affine_trans_image_size     | 把任意仿射2D变换应用在图像中并且指定输出图像大小 | 160  |
| 3    | convert_map_type            | 将图像转换为其它类型                             | 161  |
| 4    | map_image                   | 把一个一般变换应用于一个图像中                   | 161  |
| 5    | mirror_image                | 镜像一个图像                                     | 162  |
| 6    | polar_trans_image           | 把一个图像转换成极坐标                           | 162  |
| 7    | polar_trans_image_ext       | 把一个图像中的环形弧转变成极坐标                 | 162  |
| 8    | polar_trans_image_inv       | 把极坐标中的图像转变成直角坐标                   | 163  |
| 9    | projective_trans_image      | 把投影变换应用于一个图像中                       | 164  |
| 10   | projective_trans_image_size | 把投影变换应用于一个图像中并且指定输出图像的大小 | 165  |
| 11   | rotate_image                | 以一个图像的中心为圆心旋转                       | 166  |
| 12   | zoom_image_factor           | 把一个图像缩放到指定比例大小                     | 166  |
| 13   | zoom_image_size             | 把一个图像缩放到指定大小                         | 166  |

### 10.8 Inpainting 图像修复

| 序号 | 函数名                 | 函数说明及注释                 | 页码 |
| ---- | ---------------------- | ------------------------------ | ---- |
| 1    | harmonic_interpolation | 对一个图像区域执行谐波插值     | 167  |
| 2    | inpainting_aniso       | 通过各向异性扩散执行图像修复   | 168  |
| 3    | inpainting_ced         | 通过一致性增强扩散执行图像修复 | 168  |
| 4    | inpainting_ct          | 通过连贯传送执行图像修复       | 169  |
| 5    | inpainting_mcf         | 通过水平线平滑执行图像修复     | 169  |
| 6    | inpainting_texture     | 通过结构传导执行图像修复       | 170  |

### 10.9 Lines 色线

| 序号 | 函数名         | 函数说明及注释         | 页码 |
| ---- | -------------- | ---------------------- | ---- |
| 1    | bandpass_image | 使用带通滤波器提取边缘 | 170  |
| 2    | lines_color    | 检测色线和它们的宽度   | 171  |
| 3    | lines_facet    | 使用面模型检测线       | 171  |
| 4    | lines_gauss    | 检测线和它们的宽度     | 172  |

### 10.10 Match 图像匹配

| 序号 | 函数名              | 函数说明及注释                       | 页码 |
| ---- | ------------------- | ------------------------------------ | ---- |
| 1    | exhaustive_match    | 模板和图像的匹配                     | 173  |
| 2    | exhaustive_match_mg | 在一个分辨率塔式结构中匹配模板和图像 | 173  |
| 3    | gen_gauss_pyramid   | 计算一个高斯金字塔                   | 174  |
| 4    | monotony            | 计算单调（无聊）操作                 | 174  |

### 10.11 Misc 混合

| 序号 | 函数名             | 函数说明及注释                                           | 页码 |
| ---- | ------------------ | -------------------------------------------------------- | ---- |
| 1    | convol_image       | 用一个任意滤波掩码对一个图像卷积                         | 175  |
| 2    | expand_domain_gray | 扩大图像区域并且在扩大的区域中设置灰度值                 | 175  |
| 3    | gray_inside        | 对图像中的每一点在图像边界的任意路径计算尽可能低的灰度值 | 176  |
| 4    | gray_skeleton      | 灰度值图像的细化                                         | 176  |
| 5    | lut_trans          | 使用灰度值查询表转换一个图像                             | 176  |
| 6    | symmetry           | 沿一行灰度值的对称性                                     | 177  |
| 7    | topographic_sketch | 计算一个图像的地理原始草图                               | 177  |

### 10.12 Noise 噪声

| 序号 | 函数名                  | 函数说明及注释         | 页码 |
| ---- | ----------------------- | ---------------------- | ---- |
| 1    | add_noise_distribution  | 向一个图像添加噪声     | 178  |
| 2    | add_noise_white         | 向一个图像添加噪声     | 178  |
| 3    | gauss_distribution      | 产生一个高斯噪声分布   | 178  |
| 4    | noise_distribution_mean | 测定一个图像的噪声分布 | 178  |
| 5    | sp_distribution         | 产生一个椒盐噪声分布   | 178  |

### 10.13 Optical-FLow 光流

| 序号 | 函数名                    | 函数说明及注释               | 页码 |
| ---- | ------------------------- | ---------------------------- | ---- |
| 1    | optical_flow_mg           | 计算两个图像之间的光流       | 178  |
| 2    | unwarp_image_vector_field | 使用一个矢量场来展开一个图像 | 179  |
| 3    | vector_field_length       | 计算一个矢量场的矢量长度     | 180  |

### 10.14 Points 角点

| 序号 | 函数名                 | 函数说明及注释            | 页码 |
| ---- | ---------------------- | ------------------------- | ---- |
| 1    | corner_response        | 在图像中寻找角点          | 180  |
| 2    | dots_image             | 在一个图像中增强圆形点    | 181  |
| 3    | points_foerstner       | 使用Foerstner算子检测角点 | 182  |
| 4    | points_harris          | 使用Harris算子检测角点    | 183  |
| 5    | points_harris_binomial | 使用Harris二项式找出角点  | 183  |
| 6    | points_lepetit         | 使用Lepetit算子找出角点   | 184  |
| 7    | points_sojka           | 使用Sojka算子找出角点     | 185  |

### 10.15 Smoothing  滤波处理

| 序号 | 函数名                | 函数说明及注释                     | 页码 |
| ---- | --------------------- | ---------------------------------- | ---- |
| 1    | anisotropic_diffusion | 对一个图像执行各向异性扩散         | 186  |
| 2    | binomial_filter       | 使用binomial滤波器平滑一个图像     | 186  |
| 3    | eliminate_min_max     | 在空域内平滑一个图像来抑制噪声     | 187  |
| 4    | eliminate_sp          | 用中值代替阀值外的值               | 187  |
| 5    | fill_interlace        | 插补两个对半视频图像               | 187  |
| 6    | gauss_image           | 使用离散高斯函数平滑图像           | 188  |
| 7    | info_smooth           | 平滑滤波器smooth_image的信息       | 188  |
| 8    | isotropic_diffusion   | 对一个图像执行各向同性扩散         | 188  |
| 9    | mean_image            | 通过均值平滑一个图像               | 189  |
| 10   | mean_n                | 几个通道的平均灰度值               | 189  |
| 11   | mean_sp               | 抑制椒盐噪声                       | 190  |
| 12   | median_image          | 使用不同级别掩码的中值滤波         | 190  |
| 13   | median_rect           | 使用中值平滑滤波图像（橡皮擦功能） | 191  |
| 14   | median_separate       | 使用矩形掩码的离散中值滤波         | 191  |
| 15   | median_weighted       | 使用不同级别掩码的加权中值滤波     | 192  |
| 16   | midrange_image        | 计算掩码内最大和最小值的平均       | 192  |
| 17   | rank_n                | 几个通道的平均灰度值               | 192  |
| 18   | rank_rect             | 通过一个矩形掩码平滑一个图像       | 193  |
| 19   | rank_image            | 通过一个任意等级掩码平滑一个图像   | 193  |
| 20   | sigma_image           | 使用sigma滤波器的非线性平滑        | 194  |
| 21   | smooth_image          | 使用递归滤波器平滑一个图像         | 194  |
| 22   | trimmed_mean          | 使用任意等级掩码平滑一个图像       | 195  |

### 10.16 Texture 图像质感

| 序号 | 函数名          | 函数说明及注释                                 | 页码 |
| ---- | --------------- | ---------------------------------------------- | ---- |
| 1    | deviation_image | 计算矩形窗口内的灰度值的标准偏差               | 195  |
| 2    | entropy_image   | 计算矩形窗口内的灰度值的平均信息量             | 196  |
| 3    | texture_laws    | 使用一个Laws文本滤波器（地质变形）过滤一个图像 | 196  |

### 10.17 Wiener-Filter 维纳滤波器

| 序号 | 函数名           | 函数说明及注释                     | 页码 |
| ---- | ---------------- | ---------------------------------- | ---- |
| 1    | gen_psf_defocus  | 产生一个均匀散焦模糊的脉冲相应     | 197  |
| 2    | gen_psf_motion   | 产生一个（线性）运动模糊的脉冲相应 | 197  |
| 3    | simulate_defocus | 对一个图像的均匀散焦模糊进行仿真   | 197  |
| 4    | simulate_motion  | （线性）运动模糊的仿真             | 198  |
| 5    | wiener_filter    | 通过Wiener滤波进行图像恢复         | 198  |
| 6    | wiener_filter_ni | 通过Wiener滤波进行图像恢复         | 198  |

























