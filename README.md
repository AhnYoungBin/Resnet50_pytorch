Resnet50 Pytorch Code
===================

Dataset
-------
>cifar10 
<img src="/image/0.JPG" width="80%" height="80%" title="img1" alt="img1"></img>
CIFAR-10 dataset은 32x32픽셀의 60000개 컬러이미지가 포함되어있으며, 각 이미지는 10개의 클래스로 라벨링이 되어있습니다.   
   
>Split
<img src="/image/1.JPG" width="80%" height="80%" title="img1" alt="img1"></img>
   
Model Architecture
------------------
<img src="/image/2.JPG" width="80%" height="80%" title="img1" alt="img1"></img>

Option
------
#### input_shape : [224,224,3], Batch_size : 32,step= 30, epochs = 400
#### compile option : optimizers= 'Adadelta', loss='binary_crossentropy', metrics=['acc']
   
Result
