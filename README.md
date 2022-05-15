# 탈모 데이터
## 1. Convolutional Neural Networks
### 1) resnet50
### 2) efficientNet
### 3) inceptionV3

## 2. semi-supervised learning
### 1) efficirentB3 model -> 탈모 증상별 분류 문제 학습된 
#### Model: "sequential_15"
#### _________________________________________________________________
#### Layer (type)                 Output Shape              Param #   
#### =================================================================
#### efficientnetb3 (Functional)  (None, 1536)              10783535  
#### _________________________________________________________________
#### dense_14 (Dense)             (None, 3)                 4611      
#### =================================================================
#### Total params: 10,788,146
#### Trainable params: 4,611
#### Non-trainable params: 10,783,535
#### _________________________________________________________________
![스크린샷 2022-05-14 오후 3 19 55](https://user-images.githubusercontent.com/84977137/168413520-4be3e42c-37d4-4276-9724-c0ad2fee4b19.png)
##### [추가] 5/15일 : 탈모 경증데이터가 많고 예측 시 unlabel 데이터가 경증으로 치중되어 label이 경증이고 확률이 90%이상일 경우는 재학습에서 제외한다. 
