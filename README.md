# tensorflow2-unet
Image segmentation(语义分割)
A tensorflow_2.0 implementation of U-Net(语义分割)


## Requirements:
+ Python >= 3.6
+ TensorFlow == 2.1.0
+ opencv-python == 4.1.0.25

## Usage
dataset_cell数据集下载地址：
dataset_sidewalk数据集下载地址：
dataset_trafficRoad数据集下载地址：

### Test
代码中 model = tf.keras.models.load_model('models/model-cell-0017-0.9356.h5')改成自己训练出来的模型名称。
代码中 model = tf.keras.models.load_model('models/model-sidewalk-0016-0.9945.h5')改成自己训练出来的模型名称。
代码中 model = tf.keras.models.load_model('models/model-trafficRoad-0017-0.9052.h5')改成自己训练出来的模型名称。


## References
+ 论文地址: [U-Net: Convolutional Networks for Biomedical Image Segmentation](http://www.arxiv.org/pdf/1505.04597.pdf)

