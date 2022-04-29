DDRIM
========
Pytorch implementation of the paper [Distortion Detection and Removal Integrated Method for Image Restoration](https://www.sciencedirect.com/science/article/abs/pii/S1051200422001452)

Image restoration has been the focus of research in image processing, and current methods mainly target specific single distortion or hybrid distortion with known distortion types. However, real-world images generally affected hybrid distortions of unknown quantity and type, there is no restoration method applicable to such complex hybrid distortion. Therefore, we propose a distortion detection and removal integrated method. Firstly, the distortion detection module is designed based on the idea of multi-label classification, which can detect the type and level of distortion in the distorted image. The type and level of distortion can be used as a piece of prior information to control the subsequent image restoration process. Then, the image restoration module is designed based on controllable residual connection, which enables the network to restore images with different types and levels of distortion, and the attention parallel convolution block is designed by using a parallel convolution layer and coordinated attention mechanism to enhance the feature extraction ability of the network and improve the quality of the restored image. The experimental results show that the proposed method achieves superior performance.

![The architecture of the proposed distortion detection and removal integrated method.](https://github.com/sspBIT/DDRIM/blob/main/image/Fig1.png)

The proposed method is compared with [DnCNN](https://github.com/cszn/DnCNN), [RL-Restore](https://github.com/yuke93/RL-Restore) and [OWAN](https://github.com/sg-nm/Operation-wise-attention-network). The proposed method can better remove distortion from the images and reconstruct detailed images than the other three methods, whether the distorted images contain three hybrid distortions, two hybrid distortions, or single distortion.

![Image restoration results of different methods on single distorted images.](https://github.com/sspBIT/DDRIM/blob/main/image/Fig6.png)
![Image restoration results of different methods on two hybrid-distorted images.](https://github.com/sspBIT/DDRIM/blob/main/image/Fig7.png)

![Image restoration results of different methods on three hybrid-distorted images.](https://github.com/sspBIT/DDRIM/blob/main/image/Fig8.png)


# How to run
We will release the source code soon.
