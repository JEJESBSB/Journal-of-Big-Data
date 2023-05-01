## Journal of Bigdata 

### Title : Multi Combination Pattern Labeling by using Deep Learning for Chameleon Rotary Machine Environment
> Rotary machine sensor dataset for state diagnosis system
- Raw Dataset : [데이터 분야 - AI 데이터찾기 - AI-Hub (aihub.or.kr)](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=238)


### Directory & Files 

#### FFT

- FFT and Making F.P.MCPL dataset from raw vibration data  
  - download :  [데이터 분야 - AI 데이터찾기 - AI-Hub (aihub.or.kr)](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=238)
```bash
└─ FFT&F.P.MCPL.ipynb
```


#### F.P.MCPL_DNN

- F.P.MCPL dataset for DNN validation 
  -  download: [BDJ_Data - Google Drive](https://drive.google.com/drive/u/0/folders/1owu28-2OI5lYaXNVlojj4PJskCdk8mDZ) , file name : new_data.zip
  - This dataset was constructed from the raw vibration data in the above-mentioned.

```bash
│  Journal of Bigdata_DNN_Model1.ipynb
│  Journal of Bigdata_DNN_Model2.ipynb
│  Journal of Bigdata_DNN_Model3.ipynb
|
└─ Models
      |  dnn_model1.h
      |  dnn_model2.h
      └─dnn_model3.h
```


#### Spectrogram 

- Making Spectrogram images and S.P.MCPL dataset from raw vibration data -   download :  [데이터 분야 - AI 데이터찾기 - AI-Hub (aihub.or.kr)](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=238)

```bash
 |  Journal of Bigdata_Spectrogram_S.P.MCPL_Testset.ipynb
 └─ Journal of Bigdata_Spectrogram_S.P.MCPL_TrainSet.ipynb
 ```



#### S.P.MCPL_CNN

- S.P.MCPL Spectrogram images based dataset for CNN validation -  download: [BDJ_Data - Google Drive](https://drive.google.com/drive/u/0/folders/1owu28-2OI5lYaXNVlojj4PJskCdk8mDZ), file name: sp1.zip
  - These spectrogram images were constructed from the raw vibration data in the above-mentioned.

```bash
│  Axis_Belt_ConfusionMatrix.ipynb
│  Journal of Bigdata_Review_CNN1_TrainSet.ipynb
│  Journal of Bigdata_Review_CNN1_Validation of NewTestSet.ipynb
│  Journal of Bigdata_Review_CNN2_TrainSet.ipynb
│  Journal of Bigdata_Review_CNN2_Validation of NewTestSet.ipynb
│  Journal of Bigdata_Review_CNN3_TrainSet.ipynb
│  Journal of Bigdata_Review_CNN3_Validation of NewTestSet.ipynb
│  S.P.MCPL.md
│
└─ Models
      |cnn_saved_models_h5
      | history2.h5
      | history6.h5
      └─ history9.h5
```
























