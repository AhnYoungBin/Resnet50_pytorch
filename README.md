Resnet50 Pytorch Code
===================

Dataset
-------
>CIFAR10    

<img src="/image/0.JPG" width="80%" height="80%" title="img1" alt="img1"></img>   
     
>Data Split   

<img src="/image/1.JPG" width="80%" height="80%" title="img1" alt="img1"></img>   
   
CIFAR-10 dataset은 32x32픽셀의 60000개 컬러이미지가 포함되어있으며, 각 이미지는 10개의 클래스로 라벨링이 되어있습니다.
아래 그림과 같이 train: 40000, val : 10000 , test : 10000장으로 나누었다.

Model Architecture   
------------------   
<img src="/image/2.JPG" width="80%" height="80%" title="img1" alt="img1"></img>   
Resnet50 이외에도 다른 Resnet도 구현은 하였다.

Option
------
#### pytorch version : 1.4
#### input_shape : [32,32,3], Batch_size : 32, epochs = 30
#### compile option : optimizers= SGD(lr=0.01, momentum=0.9, weight_decay=5e-4), loss=nn.CrossEntropyLoss()
   
Result
------
<img src="/image/3.JPG" width="80%" height="80%" title="img1" alt="img1"></img>   

