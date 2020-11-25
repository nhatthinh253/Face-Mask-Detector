# Face Mask Detector
![](https://i.imgur.com/anxeE2K.png)
> Model to predict whether someone is wearing a face mask or not

Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization. With this dataset, it is possible to create a model to detect people wearing masks or not wearing them.  
- The dataset includes train, validation, and test data, already split into seperate folders.
- The classes are: Withmask and Withoutmask  

Dataset can be accessed from Kaggle via this link: https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset?select=Face+Mask+Dataset

### Sample train images: 
![](https://i.imgur.com/ePCphDP.jpg)

### Testing:
<img src="https://i.imgur.com/p5i0kKl.png" width="300">

<img src="https://i.imgur.com/VP4fZJG.png" width="300">

### Conclusion
- The model works well in the ideal condtions: clear images, no obstacle.
- However, the model fails to detect when someone is covering his/her face with other objects (bottles of water, hands,...) not face masks.
- To improve the model, we should collect more data of various scenarios, not just in the ideal conditions.
