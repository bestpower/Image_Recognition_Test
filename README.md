# Image_Recognition_Test

本项目主要实现图片识别的功能，识别对象为花朵，利用当前较为流行的TensorFlow机器学习框架进行学习训练与测试  
# 运行环境：
Windows7x64 + Anaconda3x64 + Jupyter Notebook + Python3.6.2 （最好是带支持CUDA的英伟达显卡，便于训练加速）  
# 项目中所用到的训练图片下载地址为：
链接：https://pan.baidu.com/s/1sHysscInV6OI_QuZfxjBSw   
提取码：09f6  
# 运行方法：
1、安装Jupyter Notebook（也可安装Anaconda内含该工具）  
2、下载安装代码运行所需Python包（tensorflow numpy）  
可通过Anaconda安装，也可通过pip命令  
3、打开Jupyter Notebook工具，转到源码所在目录，并将下载的训练数据解压放到源码同级目录下  
4、运行训练程序train.ipynb，大概一两分钟的时间，模型会保存至Model文件夹中以便后续调用  
（本人用的是tensorflow-gpu版本+GTX1050Ti显卡，cpu版本训练会慢一些）  
5、运行测试程序test.ipynb，会调用上一步训练出的模型对指定的一些图片进行分类，大概十几秒会显示出预测分类结果  
# 注意事项：
1、运行本项目程序之前请确保python环境及tensorflow包已安装成功（网上的安装方法有很多。可自行搜索查找）  
2、该程序也可通过命令行，其他IDE或者其他操作系统上运行，大家可自行决定怎么运行  
3、该程序模型的训练步数可自行指定（一般是到了训练准确率无法再提高、训练损失率无法再下降为止）  
4、该程序模型的测试可自行指定要分类的图片（可以是本程序所用图片库中的，也可自行查找一些其他分类中的图片用于检测模型的泛化能力）  
