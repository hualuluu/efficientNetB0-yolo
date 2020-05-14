# efficientNetB0-yolo-caffe
efficientNetB0-yolo to caffe
**项目的目的是提供将efficientNetB0-yolo转caffe的文件 darknet2caffe.py

-------------------------------05.14初次------------------------

我又来了，转caffe的文章能写3篇我也是厉害，hhhh

这里用的官方effi_b0.cfg文件,默认大家用过darknet做过yolo训练，所以训练步骤不详述
caffe版本在今天弄通了。 是基于前辈们的工作做的粗糙的改动，因为没时间继续钻研，做系统性的封装。【永远没时间，就是懒.】

##A.需要用到的前辈项目

darknet的版本：AlexeyAB大神的 git clone https://github.com/AlexeyAB/darknet 嗯，大佬地址

darknet to caffe:  https://github.com/marvis/pytorch-caffe-darknet-convert

caffe-yolo：       https://github.com/ChenYingpeng/caffe-yolov3

**B.本项目提供的是转caffe时的darknet2caffe.py文件

**C.简单流程：

***【caffe转换的具体操作，和文件修改的解释博客在这里https://blog.csdn.net/weixin_38715903/article/details/106124518 】


**一些PS：

1.3layers也可以改，目前还没有时间，如果改好效果不错，再放上来

2.同样的数据集，比我之前的模型误检会降低，还不错。更具体就没测试了，没时间QAQ.

2.如果Yolo不会训练，编译可以参考博客：https://blog.csdn.net/weixin_38715903/article/details/103695844

4.大概就是这样，如果有机会再尝试封装吧
