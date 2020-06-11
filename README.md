# Two-stream-CNN-for-rolling-bear-fault-diagnosis
Based on the dual-flow CNN, a new bearing fault diagnosis model is proposed. The model is composed of 2D-CNN and 1D-CNN. Among them, 2D-CNN takes wavelet time-frequency map as input, and 1D-CNN takes original vibration signal as input. After the feature extraction is implemented by the convolutional layer and the pooling layer, the output of the pooling layer of the two is spliced using a fully connected layer, and then the fault classification is achieved through the fully connected layer
基于双流CNN,提出一种新的轴承故障诊断模型，该模型由2D-CNN与1D-CNN构成，其中2D-CNN以小波时频图为输入，1D-CNN以原始振动信号为输入，分别经卷积层与池化层实现特征抽取后，采用全连接层对两者的池化层输出进行拼接，然后经全连接层实现故障分类
小波时频图采用matlab，双流CNN采用pytorch实现，需要的可以加我qq2919218574，有偿出售，白嫖勿扰，相关知识可以看我csdn博客
