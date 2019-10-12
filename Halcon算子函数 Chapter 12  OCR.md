# HALCON 算子函数

## Chapter 12 : OCR

### 12.1 Hyperboxes

1.close_all_ocrs

功能：删除所有光字符，释放存储空间，但会丢失所有的测试数据。

2.close ocr_

功能：重新分配拥有OcrHandle数目的分级器的存储，但所有相应的数据会丢失，不过这些数据可由write ocr事先保存。

3.create ocr class box

功能：创建新的OCR分级器。

4.do ocr multi

功能：给每一个Character（字符）分配一个类。

5.do ocr single

功能：给一些Character（字符）分配一些类。

6.info ocr class box

功能：反馈ocr的有关信息。

7.ocr change char

功能：为字符建立新的查阅表。

8.ocr get features

功能：计算给定Character（字符）的特征参数。

9.read ocr

功能：从文件的FileName（文件名）读取OCR分级器。

10.testd ocr class box

功能：测试给定类中字符的置信度。

11.traind ocr class box

功能：通过一幅图像的特定区域直接测试分级器。

12.trainf ocr class box

功能：根据指定测试文件测试分级器的OCRHandle。

13.write ocr

功能：将OCR分级器的OCRHandle写入文件的FileName（文件名）。

### 12.2 Lexica

1.clear_all_lexica

功能：清除所有的词汇（词典），释放它们的资源。

2.clear lexicon

功能：清除一个词汇（词典），释放相应的资源。

3.create lexicon

功能：根据一些Words(单词)的元组创建一个新的词汇（词典）。

4.Import lexicon

功能：通过FileName(文件名)选定的文件中的一系列单词创建一个新的词典。

5.inspect lexicon

功能：返回Words参数的词典中所有单词的元组。

6.lookup lexicon

功能：检查Word（单词）是否在词典的LexiconHandle中，若在返回1否则返回0。

7.suggest lexicon

功能：将Word（单词）与词典中所有词汇相比较，计算出将Word从词典中导入单词中所需的足校的编辑操作符NUMcorrections。

### 12.3 Neural-Nets（神经网络）

1.clear all ocr class mlp

功能：清除所有的create ocr class mlp创建的OCR分级器，释放分级器占据的存储空间。

2.clear ocr class mlp

功能：清除所有的由OCRHandle给定的且由create ocr class mlp创建的OCR分级器，释放所有的分级器占据的存储空间。

3.create ocr class mlp

功能：利用MLP（多层感知器）创建一个新的OCR分级器。

4.do ocr multi class mlp

功能：为根据给定区域字符和OCR分级器OCRHandle的灰度图像值而给定的每个字符计算出最好的类，将类返回到Class中，且将类的置信度返回到Confidence中。

5.do ocr single class mlp

功能：为根据给定区域字符和OCR分级器OCRHandle的灰度图像值而给定的字符计算出最好的Num类，将类返回到Class中，且将类的置信度返回到Confidence中。

6.do ocr word mlp

功能：功能与do ocr multi class mlp相同，只是do ocr word mlp将字符组作为一个实体。

7.get_features_ocr_class_mlp

功能：为根据OCR分级器OCRHandle确定的字符计算其特征参数，并将它们返回到Features。

8.get params ocr class mlp

功能：返回一个OCR分级器的参数只有当分级器由do ocr multi class mlp创建时。

9.get prep info ocr class mlp

功能：计算OCR分级器预设定矢量特性的信息。

10.read ocr class mlp

功能：从一个文件中读取OCR分级器。

11.trainf ocr class mlp

功能：测试OCR 分级器的OCRHandle，根据存储在OCR 文件中的测试特性

12.write ocr class mlp

功能：将OCR分级器的OCRHandle写入由文件名确定的文件中。

### 12.4 Support-Vector-Machines_（支持矢量机）

1.clear_all ocr class svm

功能：清除所有的基于OCR分级器的SVM，释放相应的存储空间。

2.clear ocr class svm

功能：清除基于OCR分级器的一个SVM，释放相应的存储空间。

3.create ocr class svm

功能：利用支持向量机创建一个OCR分级器。

4.do ocr multi class svm

功能：根据基于OCR分级器的SVM将大量字符分类。

5.do ocr single class svm

功能：根据基于OCR分级器的SVM将单个字符分类。

6.do ocr word svm

功能：利用OCR分级器将一系列相关字符分类。

7.get features ocr class svm

功能：计算一个字符的特征。

8.get params ocr class svm

功能：返回一个OCR分级器的参数。

9.get prep info ocr class svm

功能：计算基于OCR分级器的SVM的预定义特征矢量的信息内容。

10.get support vector num ocr class svm

功能：返回OCR分级器支持的矢量的数目。

11.get support vector ocr class svm

功能：返回基于支持向量机的已测试OCR分级器中支持向量的索引。

12.read ocr class svm

功能：从文件中读取基于OCR分级器的SVM。

13.reduce ocr class svm

功能：根据一个减小的SVM来接近一个基于OCR分级器的SVM。

14.Trainf ocr class svm

功能：测试一个OCR分级器。

15.write ocr class svm

功能：将一个OCR分级器写入文件。

### 12.5 Tools

1.Segment characters

功能：将一副图像给定区域的字符分割。

2.select characters

功能：从一个给定区域中选择字符。

3.text line orientation

功能：决定一个文本行或段落的定向（定位）。

4.text_line slant

功能：决定一个文本行或段落的字符的倾斜。

### 12.6 Training-Files

1.append ocr trainf

功能：将字符添加到一个测试文件中。

2.concat ocr trainf

功能：合并测试文件。

3.read_ocr trainf

功能：从文件中读取字符，将其转换到图像中。

4.read ocr trainf names

功能：查询哪些字符存储在测试文件中。

5.read ocr trainf_select

功能：从文件中读取测试特定字符，将其转换到图像中。

6.write ocr trainf

功能：将已测试的字符存储到文件中。

7.write ocr trainf image

功能：将字符写入正在测试的文件中。