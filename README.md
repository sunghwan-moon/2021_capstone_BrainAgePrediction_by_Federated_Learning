### BrainAgePrediction_by_Federated_Learning

이번 프로젝트에서는 연합학습을 활용한 뇌연령예측 모델을 만드는 것을 목표로 하였다.
하지만 아쉽게도 Colab의 개발 환경 특성상 사용할 수 있는 리소스가 제한되어져 있었고
이로 인해 3D Brain MRI를 활용한 예측 모델을 다량의 데이터로 분석하는 것은 불가능했다.

*7월부터 9월까지 새로 서버와 장비를 할당받아 발전할 계획

#### 뇌연령 예측 모델은 다음과 같다.

1. 3D Brain MRI를 활용한 ResNet 모델
   - Client 수: 5
   - Client 별 데이터 수 : 3
2. 뇌구조학적 데이터를 활용한 Simple MLP 모델
   - Client 수 : 4
   - Client 별 데이터 수 : 100
