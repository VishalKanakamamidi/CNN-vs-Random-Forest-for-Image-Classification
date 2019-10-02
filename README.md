# CNN-vs-Random-Forest-for-Image-Classification
● Here I have done image classification of 4 different types of furniture which are bed,chair,sofa,table.For training I have used Google Colab and the 2 different .pynb notebooks(Random Forest.ipynb,CNN-Transfer_Learning.ipynb).<br/>
● For each class I have 424 training images and 23 validation images.<br/>
● Here I have used 2 methods for image classification which are -<br/>
  ○ Random Forest method<br/>
  ○ CNN method using Transfer Learning<br/> 
# Random-Forest
● In Random Forest method I have used RandomForestClassifier from Sklearn library for training.<br/>
  ○ Here I got 65 % accuracy on my validation data.<br/>
  ○ I have converted the dataset into pickle files by using “Loading in our own data.ipynb” so that dataset can be converted into
    required format.<br/>
  ○ The Confusion matrix I got is shown below -<br/>
# CNN method using Transfer Learning
● In next method I have used CNN method by using transfer learning in which I have used pretrained weights of Imagenet.<br/>
  ○ The accuracy over here is 94 %<br/>
  ○ I have trained for 15 epochs and the batch size was 8.<br/>
  ○ The Confusion Matrix is shown below -<br/>

# Result
● In Conclusion using CNN method is very much better and efficient as compared to Random Forest method for image classification as
we can infer it from the confusion matrices.<br/>
● The Dataset for the training can be found here <br/>-
  https://drive.google.com/drive/folders/1Y4RHaYymlVcB77kdOuK8J5fZdwc48MAk?usp=sharing <br/>
● The trained CNN model can be found here -<br/>
  https://drive.google.com/file/d/113PCGaFMmB2aH0pvTnLoZ_WJ_io1BAp2/view?usp=sharing <br/>
