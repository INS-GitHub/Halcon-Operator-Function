# HALCON 算子函数

## Chapter 9 : Matching

### 9.1 Component-Based

1.clear_all_component_models

功能：释放所有组件模型的内存。

2.clear_all_training_components

功能：释放所有组件训练结果的内存。

3.clear_component_model

功能：释放一个组件模型的内存。

4.clear_training_components

功能：释放一个组件训练结果的内存。

5.cluster_model_components

功能：把用于创建模型组件的新参数用于训练结果。

6.create_component_model

功能：基于确定的指定组件和关系准备一个匹配的组件模型。

7.create_trained_component_model

功能：基于训练过的组件准备一个匹配的组件模型。

8.find_component_model

功能：在一个图像中找出一个组件模型的最佳匹配。

9.gen_initial_components

功能：提取一个组件模型的最初组件。

10.get_component_model_params

功能：返回一个组件模型的参数。

11.get_component_model_tree

功能：返回一个组件模型的查找树。

12.get_component_relations

功能：返回包含在训练结果内的模型组件间的关系。

13.get_found_component_model

功能：返回一个组件模型的一个创建例子的组件。

14.get_training_components

功能：在一个特定的图像中返回初始值或者模型组件。

15.inspect_clustered_components

功能：检查从训练获取的刚性的模型组件。

16.modify_component_relations

功能：修改一个训练结果中的关系。

17.read_component_model

功能：从一个文件中读取组件模型。

18.read_training_components

功能：从一个文件中读取组件训练结果。

19.train_model_components

功能：为基于组件的匹配训练组件和关系。

20.write_component_model

功能：把一个组件模型写入一个文件中。

21.write_training_components

功能：把一个组件训练结果写入一个文件中。

### 9.2 Correlation-Based

1.clear_all_ncc_models

功能：释放NCC模型的内存。

2.clear_ncc_model

功能：释放NCC模型的内存。

3.create_ncc_model

功能：为匹配准备一个NCC模型。

4.find_ncc_model

功能：找出一个图像中的一个NCC模型的最佳匹配。

5.get_ncc_model_origin

功能：返回一个NCC模型的原点（参考点）。

6.get_ncc_model_params

功能：返回一个NCC模型的参数。

7.read_ncc_model

功能：从一个文件中读取一个NCC模型。

8.set_ncc_model_origin

功能：设置一个NCC模型的原点（参考点）。

9.write_ncc_model

功能：向一个文件中写入NCC模型。

### 9.3 Gray-Value-Based

1.adapt_template

功能：把一个模板用于一个图像的大小。

2.best_match

功能：寻找一个模板和一个图像的最佳匹配。

3.best_match_mg

功能：在金字塔中寻找最佳灰度值匹配。

4.best_match_pre_mg

功能：在预生成的金字塔中寻找最佳灰度值匹配。

5.best_match_rot

功能：寻找一个模板和一个旋转图像的最佳匹配。

6.best_match_rot_mg

功能：寻找一个模板和一个旋转金字塔的最佳匹配。

7.clear_all_templates

功能：所有模板的内存分配。

8.clear_template

功能：一个模板的内存分配。

9.create_template

功能：为模板匹配准备一个格式。

10.create_template_rot

功能：为旋转模板匹配准备一个格式。

11.fast_match

功能：寻找一个模板和一个图像的所有好的匹配。

12.fast_match_mg

功能：在金字塔中寻找所有好的灰度值匹配。

13.read_template

功能：从一个文件中读取一个模板。

14.set_offset_template

功能：模板的灰度值偏差。

15.set_reference_template

功能：为一个匹配模板定义参考位置。

16.write_template

功能：向一个文件中写入模板。

### 9.4 Shape-Based

1.clear_all_shape_models

功能：释放所有轮廓模型的内存。

2.clear_shape_model

功能：释放一个轮廓模型的内存。

3.create_aniso_shape_model

功能：为各向异性尺度不变匹配准备一个轮廓模型。

4.create_scaled_shape_model

功能：为尺度不变匹配准备一个轮廓模型。

5.create_shape_model

功能：为匹配准备一个轮廓模型。

6.determine_shape_model_params

功能：确定一个轮廓模型的参数。

7.find_aniso_shape_model

功能：在一个图像中找出一个各向异性尺度不变轮廓的最佳匹配。

8.find_aniso_shape_models

功能：找出多重各向异性尺度不变轮廓模型的最佳匹配。

9.find_scaled_shape_model

功能：在一个图像中找出一个尺度不变轮廓模型的最佳匹配。

10.find_scaled_shape_models

功能：找出多重尺度不变轮廓模型的最佳匹配。

11.find_shape_model

功能：在一个图像中找出一个轮廓模型的最佳匹配。

12.find_shape_models

功能：找出多重轮廓模型的最佳匹配。

13.get_shape_model_contours

功能：返回一个轮廓模型的轮廓表示。

14.get_shape_model_origin

功能：返回一个轮廓模型的原点（参考点）。

15.get_shape_model_params

功能：返回一个轮廓模型的参数。

16.inspect_shape_model

功能：创建一个轮廓模型的表示。

17.read_shape_model

功能：从一个文件中读取一个轮廓模型。

18.set_shape_model_origin

功能：设置一个轮廓模型的原点（参考点）。

19.write_shape_model

功能：向一个文件中写入一个轮廓模型。