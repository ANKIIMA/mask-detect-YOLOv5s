1. voc2yolo_and_divide.py 将数据集从xml格式转化为yolo格式（txt）并划分为训练集和测试集；
2. yolo2voc.py 将数据集标注从txt格式转化为xml格式；
3. 所有工作参照博客 https://blog.csdn.net/kushe123/article/details/113702225 完成；https://ankiima.github.io/2022/07/04/mask/#more是个人详细记录教程；
4. train文件夹包括训练中结果，未完全训练完成；
5. 其他文件为修改好的配置文件，参照博客进行修改；
6. 最终使用detect.py进行验证，输入流可以是摄像头（0），也可以是图片路径；
7. 简单来说首先将数据集从txt转换为xml，更加规范，然后再使用xml信息直接转换为txt的训练集和测试集，最后就完成了数据集的划分，复制到yolo项目中即可训练；
8. 当然，如果需要自己使用，路径要重新修改，参照博客；
