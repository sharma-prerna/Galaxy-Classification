## MORPHOLOGICAL CLASSIFICATION OF GALAXIES
---
# OBJECTIVE: 
This project intends to classify galaxies using machine learning models specifically ResNet50 and MLP. The sole purpose of these models is to obtain maximum accuracy in classification and replace manual classification with automation. I have used total of six models that are the variation of two primary models as mentioned before. These models are mainly used for comparison and optimization. The results are as follows

---
|Model|Data Augemntation|Image Color Mode|RMSE|
|---|---|---|---|
|MLP|No|GrayScale|0.0897|
|MLP|Yes|Grayscale|0.0555|
|MLP|No|RGB|0.0756|
|MLP|Yes|RGB|0.0498|
|Resnet50|No|RGB|0.0450|
|Resnet50|Yes|RGB|0.0289|

#Dataset
I have used galaxy-zoo2 dataset that is available on [!emoji]https://emojipedia.org/backhand-index-pointing-down/
https://www.kaggle.com/c/galaxy-zoo-the-galaxy-challenge 

#Conclusion
The whole analysis concludes that Resnet50 Model surpassed MLP model and 3 channel images produced better accuracy than single-channel images. It is important to note that for grayscale images training gets saturated after few epochs but for RGB images it continues to slow down. It is because 3 channel images contain more information than single-channel images. Indeed, color holds huge importance in the evolution of galaxies. It is challenging to extract the complete features of the galaxies, however, most of the prominent features of a galaxy lie in its center and so is its deep history. Therefore, the center of a galaxy must be observed thoroughly to extract maximum features out of that. Though astronomers are regularly trying to write better and better algorithms to unveil the complete history of our mesmerising universe, there is still a long way to go. But it is worth remembering that "The Universe has a way of leading you where you are supposed to be at the moment you are supposed to be there". Hence, never stop searching, discovering, and learning.

##NOTE
For more information about dataset and models read document/report.

