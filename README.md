# Deep-Residual-Unet
Mediacal Image Segmentation Using Deep Residual UNet.

ResUNet, a semantic segmentation model inspired by the deep residual learning and UNet. An architecture that take advantages from both(Residual and UNet) models.

![arch](https://user-images.githubusercontent.com/114977437/193758417-929e426f-c922-47ae-bc38-6110c58c01dd.png)

Residual units are used instead of plain neural units as basic blocks to build the deep Res-Unet.
The residual unit ease training of the network.
The skip connections within the network facilitates information propagation without degradation
Optimizer - Adam(Learning Rate 0.001) , Loss - Categorical Cross-entropy, Activation - ReLU
