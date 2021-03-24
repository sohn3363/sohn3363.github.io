---
layout: default
title: Mathematics
nav_order: 4
---

# Mathematics
- 2021.03.24 Updated
- source from: (<https://brunch.co.kr/@chris-song/69>)

---
## 1. Different Distances

### 1) Kullback-Leibler Divergence
- KL Divergence는 두 확률 분포를 비교하기 위해 사용된다.  
- Bayesian Inference에서의 KL-Divergence의 의미로 **q**는 사전확률분포, **p**는 사후확률분포이다. 이때, **KL(p∥q)** 는 사전확률에서 사후확률로 변할때 얻은 정보의 양으로 해석할 수 있다.  
- **p**와 **q**의 일반적인 의미로 **p**는 참 분포(True Distribution) 즉, 실제 관찰 데이터(Observation)을 의미한다. **q**는 주로 가설(Theory), 모델(Model), **p**의 근사(Approximation)로 사용된다.  
- **q**를 **p**에 가깝게 만드려면 KL Divergence를 최소화하도록 학습시키면 된다. KL Divergence의 공식은 아래와 같다.

<p align="center"><img src='/figure/formula/KLD.PNG' height="45%" width="45%"></p>  
  
- KL-Divergence 은 3가지 수학적 성질을 갖는다.

> 1. KL Divergence는 항상 0 이상의 값을 갖는다.
> 2. KL Divergence는 비대칭함수이다.
> 3. KL Divergence는 두 확률 분포가 동일할 때 0이 된다.  

- KL Divergence를 엔트로피와 크로스 엔트로피의 합의 공식으로 표현하여 두 분포의 차이를 나타낸다. 
- **H(p)** 는 고정된 상수값이기 때문에 결과적으로 **H(p,q)** 를 **H(p)** 에 근사(최소화)하는 것이 KL-Divergence를 minimize하는 것과 의미는 동일하다.  
- p에서 q 사이의 거리와 q에서 p사이의 거리가 같다면 두 확률분포 는 거리 개념으로 이해할 수 있지만, KL Divergence는 비대칭 성질이 존재하여 거리 개념처럼 사용 할 수 없다.  

<p align="center"><img src='/figure/formula/KLD_divide2.PNG' height="70%" width="70%"></p> 


### 2) Jensen-Shanon Divergence
- Jensen Shanon은 KL Divergence를 Distance Metric으로 해석할 수 있는 방법이다.
- 이는 p와 q의 평균값과 각각 KL Divergence하여 대칭 성질을 획득함으로써 Distance를 통한 척도로 활용한다.

<p align="center"><img src='/figure/formula/JSD.PNG' height="65%" width="65%"></p>  

- Jensen-Shanon 은 3가지 수학적 성질을 갖는다.  

> 1. KL Divergence는 항상 0 이상의 값을 갖는다.
> 2. KL Divergence는 **대칭함수**이다.
> 3. KL Divergence는 두 확률 분포가 동일할 때 0이 된다.  

<p align="center"><img src='/figure/formula/KL_JS_symmetric.PNG' height="25%" width="25%"></p>  

### 3) Total Variation

### 4) Earth Mover Distance
