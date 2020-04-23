# tensorflow2-unet
1. Image segmentation
2. A tensorflow_2.0 implementation of U-Net.


## Requirements:
+ Python >= 3.6
+ TensorFlow == 2.1.0
+ opencv-python == 4.1.0.25

## Usage 
1. dataset_cell数据集下载地址：https://pan.baidu.com/s/1PfOMxGUwJhO-9p8yDsasag  提取码：nqhh
2. dataset_sidewalk数据集下载地址：https://pan.baidu.com/s/1SZ42yGLNf2C9XUNUQkQCbw  提取码：ntyh
3. dataset_trafficRoad数据集下载地址：https://pan.baidu.com/s/1mFFAx7dPcrdkXsbGQomGRg  提取码：20oh

## Test
1. 代码中 model = tf.keras.models.load_model('models/model-cell-0017-0.9356.h5')改成自己训练出来的模型名称。
2. 代码中 model = tf.keras.models.load_model('models/model-sidewalk-0016-0.9945.h5')改成自己训练出来的模型名称。
3. 代码中 model = tf.keras.models.load_model('models/model-trafficRoad-0017-0.9052.h5')改成自己训练出来的模型名称。

## References
+ 论文地址: [U-Net: Convolutional Networks for Biomedical Image Segmentation](http://www.arxiv.org/pdf/1505.04597.pdf)

