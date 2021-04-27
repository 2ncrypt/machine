# **Machine Learning Start**

*TIP*
공부를 하면서 단어 정의를 확실하게 해놓으면 빅데이터 자격증 같은 시험을 볼때 도움이 됨

## **머신러닝이란?**

 정의를 생각해보기
##단순한게 정답이다

## **머신러닝** **분류**

- 지도 학습 : 분류, 회귀, 시각/음성 감지/인지

- 비지도 학습 : 군집화(클러스터링), 차원 축소

한가지 일만 잘 하는 개발자보단 여러가지를 다 할 수 있는 개발자가 필요. 예로 인공지능을 다룰줄 알면서도 BackEnd 개발도 가능한 개발인원

###### ![image-20210426161753615](/Users/hyunsul/Library/Application Support/typora-user-images/image-20210426161753615.png)



## **지도학습**

Linear : 사선으로 쭉 올라가는 그래프
Polynomial : 울퉁불퉁 다항식 그래프

의사결정 트리는 나무가 1개

랜덤 포레스트 :  최소 나무가 100개 정도(Default 값이 100개보다 크다.) , 약한 판독기들을 모아서 투표를 하는 개념



kNN : 가장 까까운 답들끼리 모아줌
Trees
Logistic Regression : 

지금은 교수님이 말씀하시는 것만 들었지만, 본인만의 정의를 세워야함. 단어, 기법이 어떠한 기법인지를 생각해야함

최대한 많은 코드들을 처리해보고, 자신만의 경험과 노하우를 쌓아야함.

===============================1일차===============================

## Estimator : 

- 학습 : fit()
- 예측 : predict()

**분류 구현 클래스(Classifier)**

- DecisonTreeClassifier
- RandomforestClassifier
- GradientBoostingClassifer
- GauussainNB
- SVC

**회귀 구현 클래스(Regressor)**

- Ridge : 1차원식에서 값이 큰걸 날림
- Lasso : 1차원식에서 값이 작은 걸 날림
- RandomForestRegressor : 
- GradientBoostingRegressor : 



### 사이킷런의 주요 모듈

![image-20210427100552577](/Users/hyunsul/Library/Application Support/typora-user-images/image-20210427100552577.png)

![image-20210427100609145](/Users/hyunsul/Library/Application Support/typora-user-images/image-20210427100609145.png)

각각의 분류와 대충 어떠한 일을 하는 모듈인지 인지해야함

### Data set의 key와 의미

- Data : 피쳐의 데이터셋
- Target : 분류시 레이블값, 숫가 결과값(예, 0,1)
- Target_names : 개별 레이블의 이름
- feature_names : 피쳐의 이름
- DESCR은 데이터 세트의 대한 설명과 피처의 설명

### 학습 데이터 세트 : 머신러닝 알고리즘의 학슴을 위해 사용, 데이터의 속성들과 결정값을 모두 가지고 있으며 학슴 데이터를 기반으로 머신러닝 알고리즘이 데이터 속성과 결정값의 패턴을 인지 및 학습

### 테스트 데이터 세트 : 테스트 데이터 세트에서 학습된 머신러닝 알고리즘을 테스트, 속성 데이터만 머신러닝 알고리즘에 제공하며, 알고맂ㅁ은 제공된 데이터를 기반으로 결정값 예층

**학습 데이터 세트 와 테스트 데이터 세트는 별도의 데이터 세트로 제공되어야함





