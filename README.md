# DeepLearning_Demo  
some demo for practice DL
# My goal  
Image:http://img.blog.csdn.net/20170202162540980?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvc3hmMTA2MTkyNjk1OQ==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast
1. 训练这个网络，输出可以忽略掉分类：
输入不再是单个样本，而是一对样本，不再给单个的样本确切的标签，而且给定一对样本是否来自同一个类的标签，是就是0，不是就是1 
2. 网络可以用来检测之前人脸识别中返回的结果，对flann返回的n个输出结果进行选择，增加系统的准确率
