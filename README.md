# COVID-19 / Pneumonia /Normal Prediction Version-2.

Predicting Noval Corona, Pneumonia, Healthy from X-ray scans using Keras and Scikit Learn.
Right now the world is in the fear of Noval Coronavirus (COVID-19). By this time, there are approximately 3.12 Million. The COVID-19  virus spreads by droplets produced as a result of coughing or sneezing of a COVID-19 infected person. This could happen either by direct close contact with an infected person or by indirect contact like the droplets on surfaces and clothes.

Predicting COVID-19 using X-ray images.
In this tutorial, I am using X-ray images to analyze the health of the patient lungs since COVID-19 attacks the epithelial cells (cells that come from surfaces of the respiratory tract) and X-ray scans are easy to get than CT scans. <br>

## 📚 Dataset
Go ahead and download the training and testing dataset from the link given<br> [Drive Link - https://drive.google.com/open?id=1wwXhV2pNJjGdC4dsMz3NQxfhojthUbeB](https://drive.google.com/open?id=1wwXhV2pNJjGdC4dsMz3NQxfhojthUbeB).
## 📂 Directory structure 
<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Healthy-Prediction/blob/master/dataset/dir.PNG" width="400">

## 😎 Sample of Dataset images
<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Healthy-Prediction/blob/master/dataset/a2.png" width="400">

## 📈 Model evaluation and Visualization

|   Model      |   model_loss      |   model_acc      |
|--------------|-------------------|------------------|
| Custom Model|<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/Custom-model_loss.png" width="300"> | <img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/Custom-model_accuracy.png" width="300"> |
| RESNET50|<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/RESNET50-model_loss.png" width="300"> | <img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/ResNet50-model_accuracy.png" width="300"> |
| VGG16 |<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/VGG16-model_loss.png" width="300"> | <img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/VGG16-model_accuracy.png" width="300"> |
  
## 📋 Conclusion : 
To this end, I am making my code, model, and results available here [Code](https://jovian.ml/v-snehith999/corona-pneumonia-normal-keras).
<br>
* Due to time constraints, I am unable to implement all of my thoughts, but I am planning out to make an end-to-end heroku application<br>
* I am figuring out different architectures and introspecting why some are not giving great results.
* Version 2 Data set is taken in the month on the end of July month. I will keep updating dataset as more and more data gets open-sourced.
NOTE: If anybody got better metrics than me, please do share your knowledge after all Knowledge is Sharing!!

## 🙏 Disclaimer
<i>This blog post on COVID-19 prediction is a proof-of-concept and for educational purposes only. It is not meant to replace professional medical advice.</i>

## 😇 Author:
<b>Linkedin</b>: https://www.linkedin.com/in/snehit-vaddi-73a814158/ <br>
<b>Github</b>: https://github.com/snehitvaddi

## 🙌 References: 
https://towardsdatascience.com/using-deep-learning-to-detect-ncov-19-from-x-ray-images-1a89701d1acd
