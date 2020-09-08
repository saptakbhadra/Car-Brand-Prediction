# Car-Brand-Prediction
## <p align="right">  
  Is it a Lamborgini, Audi or a Ferrari ?
</p>
### Deep Learning Model for predicting Car brands from their Images Using Transfer Learning 

#### Model Used: *Resnet 50*
Here we have used **Resnet 50** to train the model for Predicting the Brand of the Car 
<p align="center">
<img src="https://miro.medium.com/max/1059/1*hEU7S-EiVqcmtAlj6kgfRA.png" alt=".." title="Resnet50 Architecture"/>
Resnet50 Architecture</p>

[Click Here to know more about **RESNET 50**](https://www.kaggle.com/keras/resnet50)

#### Use of Transfer Learning to train the Model

<dl>
  <dt>What is Transfer Learning?</dt>
  <dd> It is the process in which we use the stored knowledge of one probelem and use it in some other problem.This is very helpful for training deep learning Models
    Especially if one doesn't have the hardware requirements. Here we use IMAGENET as the pretrained model for getting the weights and traing the model for a fraction of the time required . </dd>  
 </dl>
 
[Click Here to know more about Transfer Learning](https://en.wikipedia.org/wiki/Transfer_learning#:~:text=Transfer%20learning%20(TL)%20is%20a,when%20trying%20to%20recognize%20trucks.)

<dl>
  <dt>What is ImageNet?</dt>
  <dd>ImageNet is an image database organized according to the WordNet hierarchy (currently only the nouns), in which each node of the hierarchy is depicted by hundreds and thousands of images. Currently we have an average of over five hundred images per node. We hope ImageNet will become a useful resource for researchers, educators, students and all of you who share our passion for pictures.</dd>
</dl>

[Click Here to know more about Imagenet](http://www.image-net.org/about-overview)
