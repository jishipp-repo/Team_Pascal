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

### Dependencies (Python)

h5py==2.10.0<br/>
joblib==0.17.0<br/>
jsonschema==3.2.0<br/>
jupyter-client==6.1.7<br/>
jupyter-core==4.7.0<br/>
jupyterlab-pygments==0.1.2<br/>
Keras==2.4.3<br/>
Keras-Applications @ file:///tmp/build/80754af9/keras-applications_1594366238411/work<br/>
Keras-Preprocessing==1.1.2<br/>
matplotlib==3.3.3<br/>
notebook==6.1.5<br/>
numpy==1.18.5<br/>
oauthlib==3.1.0<br/>
opencv-python==4.4.0.46<br/>
pandas==1.1.4<br/>
scikit-learn==0.23.2<br/>
scipy==1.4.1<br/>
seaborn==0.11.0<br/>
sklearn==0.0<br/>
tensorboard==2.2.2<br/>
tensorboard-plugin-wit==1.7.0<br/>
tensorflow==2.2.0<br/>
tensorflow-estimator==2.2.0<br/>
tensorflow-gpu==2.3.1<br/>
tensorflow-gpu-estimator==2.3.0<br/>

### Contributors:
- Ideated by: Jishi P P
- Mentor(s): Akhil Verma
- Team: Jishi P P, Anitha Ch
