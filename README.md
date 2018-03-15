## HENet

This is caffe implementation of HENet, For details, you can read the original paper:

["HENet:A Highly Efficient Convolutional Neural Networks Optimized for Accuracy, Speed and Storage" by Qiuyu zhu, Ruixin zhang][1].  This model's cuda file for acceleration is based on [farmingyard/ShuffleNet][2]. 



### Note: If you want to train HENet in Caffe，you need to add ShuffleChannel layer to Caffe first. You can download from [farmingyard/ShuffleNet][2]. If you have no clue about how to add the ShuffleChannel layer, take this blog["ShuffleNet在Caffe框架下的实现"][3] as a reference.



[1]:https://arxiv.org/abs/1803.02742
[2]:https://github.com/farmingyard/ShuffleNet
[3]:http://blog.csdn.net/chris_zhangrx/article/details/78277957
