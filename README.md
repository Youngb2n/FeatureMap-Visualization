Featuremap_visualization in tensorflow 2.0
=========================
    
출력 결과
-----
>각 층별 16개의 layer 만 시각화   

<img src="/image/0.JPG" width="80%" height="80%" title="img1" alt="img1"></img>   
>각 층별 모든 layer 시각화   

<img src="/image/1.JPG" width="80%" height="80%" title="img1" alt="img1"></img>   
환경
------
#### Cat vs Dog dataset Download Site : <https://www.kaggle.com/c/dogs-vs-cats/data>
Cat and Dog Dataset 에서 accuracy 91.95%의 학습된 VGG16 Model를 기반으로 Colab 환경에서 제작.    
자세한 모델 구조는 Code 참고   


설명
------
tensorflow 2.0 으로 구현한 Convolution layer featuremap 시각화 코드입니다. 1줄에 16개의 featuremap을 출력하는 형태를 기반으로 제작 하였으며 실험 결과 대부분의 첫번째 Convolution layer 에서는 대상의 Edge를 검출 하려는 것으로 보입니다.    
"케라스 창시자에게 배우는 딥러닝"이라는 교재를 참고하여 제작하였습니다.   


