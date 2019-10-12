# HALCON 算子函数

## Chapter 1 : Classification

### 1.1 Gaussian-Mixture-Models

1.add_sample_class_gmm

功能：把一个训练样本添加到一个高斯混合模型的训练数据上。

2.classify_class_gmm

功能：通过一个高斯混合模型来计算一个特征向量的类。

3.clear_all_class_gmm

功能：清除所有高斯混合模型。

4.clear_class_gmm

功能：清除一个高斯混合模型。

5.clear_samples_class_gmm

功能：清除一个高斯混合模型的训练数据。

6.create_class_gmm

功能：为分类创建一个高斯混合模型。

7.evaluate_class_gmm

功能：通过一个高斯混合模型评价一个特征向量。

8.get_params_class_gmm

功能：返回一个高斯混合模型的参数。

9.get_prep_info_class_gmm

功能：计算一个高斯混合模型的预处理特征向量的信息内容。

10.get_sample_class_gmm

功能：从一个高斯混合模型的训练数据返回训练样本。

11.get_sample_num_class_gmm

功能：返回存储在一个高斯混合模型的训练数据中的训练样本的数量。

12.read_class_gmm

功能：从一个文件中读取一个高斯混合模型。

13.read_samples_class_gmm

功能：从一个文件中读取一个高斯混合模型的训练数据。

14.train_class_gmm

功能：训练一个高斯混合模型。

15.write_class_gmm

功能：向文件中写入一个高斯混合模型。

16.write_samples_class_gmm

功能：向文件中写入一个高斯混合模型的训练数据。

### 1.2 Hyperboxes

1.clear_sampset

功能：释放一个数据集的内存。

2.close_all_class_box

功能：清除所有分类器。

3.close_class_box

功能：清除分类器。

4.create_class_box

功能：创建一个新的分类器。

5.descript_class_box

功能：分类器的描述。

6.enquire_class_box

功能：为一组属性分类。

7.enquire_reject_class_box

功能：为一组带抑制类的属性分类。

8.get_class_box_param

功能：获取关于现在参数的信息。

9.learn_class_box

功能：训练分类器。

10.learn_sampset_box

功能：用数据组训练分类器。

11.read_class_box

功能：从一个文件中读取分类器。

12.read_sampset

功能：从一个文件中读取一个训练数据组。

13.set_class_box_param

功能：为分类器设计系统参数。

14.test_sampset_box

功能：为一组数组分类。

15.write_class_box

功能：在一个文件中保存分类器。

### 1.3 Neural-Nets

1.add_sample_class_mlp

功能：把一个训练样本添加到一个多层感知器的训练数据中。

2.classify_class_mlp

功能：通过一个多层感知器计算一个特征向量的类。

3.clear_all_class_mlp

功能：清除所有多层感知器。

4.clear_class_mlp

功能：清除一个多层感知器。

5.clear_samples_class_mlp

功能：清除一个多层感知器的训练数据。

6.create_class_mlp

功能：为分类或者回归创建一个多层感知器。

7.evaluate_class_mlp

功能：通过一个多层感知器计算一个特征向量的评估。

8.get_params_class_mlp

功能：返回一个多层感知器的参数。

9.get_prep_info_class_mlp

功能：计算一个多层感知器的预处理特征向量的信息内容。

10.get_sample_class_mlp

功能：从一个多层感知器的训练数据返回一个训练样本。

11.get_sample_num_class_mlp

功能：返回存储在一个多层感知器的训练数据中的训练样本的数量。

12.read_class_mlp

功能：从一个文件中读取一个多层感知器。

13.read_samples_class_mlp

功能：从一个文件中读取一个多层感知器的训练数据。

14.train_class_mlp、

功能：训练一个多层感知器。

15.write_class_mlp

功能：向一个文件中写入一个多层感知器。

16.write_samples_class_mlp

功能：向一个文件中写入一个多层感知器的训练数据。

### 1.4 Support-Vector-Machines

1.add_sample_class_svm

功能：把一个训练样本添加到一个支持向量机的训练数据上。

2.classify_class_svm

功能：通过一个支持向量机为一个特征向量分类。

3.clear_all_class_svm

功能：清除所有支持向量机。

4.clear_class_svm

功能：清除一个支持向量机。

5.clear_samples_class_svm

功能：清除一个支持向量机的训练数据。

6.create_class_svm

功能：为模式分类创建一个支持向量机。

7.get_params_class_svm

功能：返回一个支持向量机的参数。

8.get_prep_info_class_svm

功能：计算一个支持向量机的预处理特征向量的信息内容。

9.get_sample_class_svm

功能：从一个支持向量机的训练数据返回一个训练样本。

10.get_sample_num_class_svm

功能：返回存储在一个支持向量机训练数据中的训练样本的数量。

11.get_support_vector_class_svm

功能：从一个训练过的支持向量机返回一个支持向量的索引。

12.get_support_vector_num_class_svm

功能：返回一个支持向量机的支持向量的数量。

13.read_class_svm

功能：从一个文件中读取一个支持向量机。

14.read_samples_class_svm

功能：从一个文件中读取一个支持向量机的训练数据。

15.reduce_class_svm

功能：为了更快分类，用一个降低的支持向量机近似一个训练过的支持向量机。

16.train_class_svm

功能：训练一个支持向量机。

17.write_class_svm

功能：向一个文件中写入一个支持向量机。

18.write_samples_class_svm

功能：向一个文件中写入一个支持向量机的训练数据。
