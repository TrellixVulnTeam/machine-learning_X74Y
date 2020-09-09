# AWSKRUG 기계학습 스터디 모임 - 9/9/2020

<br>

<br>

## 1. Hands-On ML Chapter 6 - 결정 트리

> 발표자: 11번가 이주경님

<br>

### 1-1. [발표 자료](./6장_결정트리.pdf)

<br>

### 1-2. 발표를 들으며 새롭게 알게 된 점

<br>

#### 결정 트리 학습과 시각화

- `Logistic regression`, `SVM (Support Vector Machine)` 은 **선형모델** 의 각 특징별 **가중치** 를 학습하는 방식
- **Tree** 를 만들기 위한 각 특징별 조건을 학습한다!

<br>

#### Decision Tree의 지니 불순도 (Gini Impurity) 란?

- 지니 불순도 측정 (Gini Impurity Measure) 은 분류문제에서 사용 가능한 결정 트리 (Decision Tree)의 분할 기분 (Split Criteria) 중 하나이다
- Decision Tree에서 사용되는 class의 개수에 따른 case들의 **불순한 정도** 를 나타내는 척도이다
- 지니 불순도는 class안에 분류가 잘 되어 있으면 0이 된다
  - 불순물없이 깨끗하게 분류가 되어있다는 뜻!
    - but, 섞이게 되면 0보다 큰 값을 갖게 된다 (최대값은 0.5)

<br>

#### 규제 매개변수

- 훈련 데이터에 대한 **과대 적합**을 피하기 위해 학습할 때 결정 트리의 **자유도** 를 제한할 필요가 있다
- **규제 매개변수** 는 사용하는 알고리즘에 따라 다르지만, 보통 적어도 decision tree의 최대 깊이는 제어할 수 있다
  - Scikit learn에서는 `max_depft` 매개변수로 조절한다
    - default는 제한이 없는 것을 의미하는 None
    - `max_depth` 를 줄이면 모델을 **규제**하게 되고, **과대 접합** 의 위험이 감소한다!

<br>

<br>

## 2. Introducing MLOps

> 발표자: superb Ai 차문수님

<br>

### 2-1. [발표자료](./Introducing_MLOps.pdf)

<br>

### 2-2. 발표를 들으며 새롭게 알게 된 점

- *Launching is easy, Operation is hard*
  - 서비스를 고도화하고 운영하는 것이 어렵다
- DevOps 처럼 나오게 된 MLOps
  - 실제로 서비스하는데까지 시간이 너무 오래걸리므로
  - `개발` - `운영` 을 같이 하기 위한 pipeline 의 필요성이 대두되어 등장!