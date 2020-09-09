# AWSKRUG 기계학습 스터디 모임 - 8/3/2020

<br>

<br>

## 1. Hands-On ML Chapter 5 - 서포트 벡터 머신

> 발표자:  김두진님

<br>

### 1-1. [발표 자료](https://drive.google.com/file/d/1-rOQAEM9Dc0odgxNBz80MQA1o-s5i7pI/view?usp=sharing)

<br>

### 1-2. 발표를 들으며 새롭게 알게 된 점

#### 서포트 벡터 머신 (SVM)

- 서포트 벡터 머신 (SVM)은 매우 강력하고 선형이나 비선형 분류, 회귀, 이상치 탐색에도 사용할 수 있는 다목적 머신러닝 모델
- 머신러닝에서 가장 인기 있는 모델에 속하고 머신러닝에 관심있는 사람이라면 반드시 알고 있어야 하는 모델
- SVM은 특히 **복잡한 분류 문제**에 잘 들어 맞으며, **작거나 중간 크기의 데이터셋**에 적합하다!

<br>

#### Polynomial Kernal

```bash
SVC(kernel="poly", degree=3, coef0=1, C=5)
SVC(kernel="poly", degree=10, coef0=100, C=5)
```

- `coef0` 
  - Independent term in kernel function. It is only significant in ‘poly’ and ‘sigmoid’
    - 모델이 높은 차수와 낮은 차수에 얼마나 영향을 받을지 조절한다!

<br>

#### SVM 회귀

- SVM 알고리즘은 선형, 비선형 분류뿐만 아니라 선형, 비선형 회귀에도 사용할 수 있다

- SVM을 회귀에 적용하는 방법은 분류 목표와 반대로 하는 것!

  - **SVM 회귀 목표** :

    - `분류` : 일정한 마진 오류 안에서 두 클래스 간의 도로 폭이 가능한 한 최대가 되도록 한다

      `회귀` : 회귀는 제한된 마진 오류 안에서 도로 안에 가능한 한 많은 샘플이 들어가도록 학습한다

<br>

<br>

## 2. AWS 머신러닝 스페셜 SA 김대근님의 데이터 과학 경험담 & 삽질기

> 발표자: 김대근님 (AWS)

<br>

개인적인 사항 / 회사 내부 자료여서 발표자료를 공유 받지는 못했지만 정말 유익한 시간이었다! 

<br>

#### [대근님 Notion](https://www.notion.so/About-me-9fee9a6ea86f4afbb054fe3a8c57a9ec)

