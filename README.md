## ⚡ COVID-19 / Pneumonia /Normal Prediction Version-2.

Predicting Noval Corona, Pneumonia, Healthy from X-ray scans using Keras and Scikit Learn.<br>

In this project, I am using X-ray images to analyze the health of the patient lungs since COVID-19 attacks the epithelial cells (cells that come from surfaces of the respiratory tract) and X-ray scans are easy to get than CT scans. <br>
The COVID-19  virus spreads by droplets produced as a result of coughing or sneezing of a COVID-19 infected person. This could happen either by direct close contact with an infected person or by indirect contact like the droplets on surfaces and clothes.<br>

**_Note:_ I have made `Training_multiple_models.ipynb` private to avoid misuse, contact me @v.snehith999@gmail.com for complete directory ☺**<br>

### 🌀 Application Interface 
![Output](https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/dataset/streamlit-output.jpeg)
The trained model is deployed using Streamlit module on local system.
### 📁 Dataset
* Go ahead and download the training and testing dataset from the link given<br> 
[Drive Link]https://drive.google.com/drive/folders/1aA-RK0ImIAtKkGqg_-I0rAOsEOZRSSQZ?usp=sharing).<br>
_**Note:** This is an year old dataset that I have managed to collect. Rightnow there are n number of standerdized datasets avilable online. A quick google seach will do the work._<br> 
* Detailed blog on working and implementation: [`Medium Blog`](https://v-snehith999.medium.com/covid-19-pneumonia-prediction-using-deep-learning-3fcddba12df5)

| 📂 Dataset |  📑 Blog   |
|:-:|:-:|
|[Dataset](https://drive.google.com/drive/folders/1aA-RK0ImIAtKkGqg_-I0rAOsEOZRSSQZ?usp=sharing)| [Medium](https://v-snehith999.medium.com/covid-19-pneumonia-prediction-using-deep-learning-3fcddba12df5) |

### 🗃 Directory structure 
<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Healthy-Prediction/blob/master/dataset/dir.PNG" width="400">

### 🔥 Sample of Dataset images
<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Healthy-Prediction/blob/master/dataset/a2.png" width="400">

### ⚖ Model evaluation and Visualization

|   📈 Model     |  🛠  model_loss   |   💡  model_acc    |
|------------------|------------------|------------------|
| Custom Model|<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/Custom-model_loss.png" width="300"> | <img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/Custom-model_accuracy.png" width="300"> |
| RESNET50|<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/RESNET50-model_loss.png" width="300"> | <img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/ResNet50-model_accuracy.png" width="300"> |
| VGG16 |<img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/VGG16-model_loss.png" width="300"> | <img src="https://github.com/snehitvaddi/NovelCorona-Pneumonia-Prediction_V2/blob/master/Evaluation%20Graphs/VGG16-model_accuracy.png" width="300"> |
  
### 🧠 Conclusion : 
* To this end, I am open sourcing  my code, model, and results. You can access it here: [Code](https://jovian.ml/v-snehith999/corona-pneumonia-normal-keras).
* Out of three models(Custom model, VGG 16, ResNet50), Custom model and VGG16 are performing better.
* Wise picking of Augmentation features lead to robust dataset generation.
* Introducing Batch Normalization would uplift model performance.

### 📑 Future Actions :
* Due to time constraints, I am unable to implement all of my thoughts, but I am planning out to make an end-to-end Web based application hosted on heroku<br>
* Updating datasets as per the avilability. 
* Version-2 dataset is collected during the July month-end. I will keep updating dataset as more and more data gets open-sourced.
NOTE: If anybody got better metrics than me, please do share your knowledge after all Knowledge is Sharing!!

### ⚠ Disclaimer
<i>This blog post on COVID-19 prediction is a proof-of-concept and for educational purposes only. It is not meant to replace professional medical advice.</i>

### ✍ Author:
<b>Linkedin</b>: https://www.linkedin.com/in/snehitvaddi/ <br>
<b>Github</b>: https://github.com/snehitvaddi

### 📑 References: 
https://towardsdatascience.com/using-deep-learning-to-detect-ncov-19-from-x-ray-images-1a89701d1acd
https://jovian.ai/v-snehith999/covid19-training-different-models-v2
