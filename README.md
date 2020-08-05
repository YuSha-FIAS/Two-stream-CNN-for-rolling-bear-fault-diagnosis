# Two-stream-CNN-for-rolling-bear-fault-diagnosis
Based on the dual-flow CNN, a new bearing fault diagnosis model is proposed. The model is composed of 2D-CNN and 1D-CNN. Among them, 2D-CNN takes wavelet time-frequency map as input, and 1D-CNN takes FFT feature as input. After the feature extraction is implemented by the convolutional layer and the pooling layer, the output of the pooling layer of the two is spliced using a fully connected layer, and then the fault classification is achieved through the fully connected layer，On the bearing data of Western Reserve University, the training set, test set and validation set all achieve 100% classification accuracy,
基于双流CNN,提出一种新的轴承故障诊断模型，该模型由2D-CNN与1D-CNN构成，其中2D-CNN以小波时频图为输入，1D-CNN以FFT频谱为输入，分别经卷积层与池化层实现特征抽取后，采用全连接层对两者的池化层输出进行拼接，然后经全连接层实现故障分类，在西储大学轴承数据上，测试集达到100%的分类正确率。
小波时频图采用matlab，双流CNN采用pytorch实现，需要的可以加我qq2919218574，有偿出售，白嫖勿扰，相关知识可以看我csdn博客https://blog.csdn.net/qq_41043389/article/details/106692362

