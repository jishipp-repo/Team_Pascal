# Team_Pascal - haQathon 2020
## Medical Diagnosis with Deep Learning on Chest X-Ray

We will be using the ChestX-Ray dataset which contains 108,948 frontal-view X-ray images of 32,717 unique patients. Each image in the data set contains multiple text-mined labels identifying 14 different pathological conditions. We will use this data to develop a single model that will provide binary classification predictions for each of the 14 labeled pathologies. In other words it will predict 'positive' or 'negative' for each of the pathologies.<br/>

List of pathological conditions:
- Atelectasis
- Cardiomegaly
- Consolidation
- Edema	
- Effusion	
- Emphysema	
- Fibrosis	
- Hernia	
- Infiltration	
- Mass	
- Nodule	
- Pleural_Thickening	
- Pneumonia	
- Pneumothorax
- No Finding	

### Screenshots
![alt text](https://github.com/jishipp-repo/Team_Pascal/blob/main/image.PNG)

### Architecture
![alt text](https://github.com/jishipp-repo/Team_Pascal/blob/main/densenet2.png)

### Application Components
Used TensorFlow framework with Keras backend. Trained the model using DenseNet121 pretrained model in GPU.

### Dependencies
Python, TensorFlow, Keras, Pandas, Numpy

h5py==2.10.0
joblib==0.17.0
jsonschema==3.2.0
jupyter-client==6.1.7
jupyter-core==4.7.0
jupyterlab-pygments==0.1.2
Keras==2.4.3
Keras-Applications @ file:///tmp/build/80754af9/keras-applications_1594366238411/work
Keras-Preprocessing==1.1.2
matplotlib==3.3.3
notebook==6.1.5
numpy==1.18.5
oauthlib==3.1.0
opencv-python==4.4.0.46
pandas==1.1.4
protobuf==3.13.0
pywin32==300
pywinpty==0.5.7
PyYAML==5.3.1
scikit-learn==0.23.2
scipy==1.4.1
seaborn==0.11.0
sklearn==0.0
tensorboard==2.2.2
tensorboard-plugin-wit==1.7.0
tensorflow==2.2.0
tensorflow-estimator==2.2.0
tensorflow-gpu==2.3.1
tensorflow-gpu-estimator==2.3.0
tornado==6.1

### Contributors:
- Ideated by: Jishi P P
- Mentor(s): Akhil Verma
- Team: Jishi P P, Anitha Ch
