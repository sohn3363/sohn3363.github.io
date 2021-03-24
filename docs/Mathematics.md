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
- q를 p에 가깝게 만드려면 KL Divergence를 최소화하도록 학습시키면 된다. KL Divergence의 공식은 아래와 같다.

<p align="center"><img src='/figure/formula/KLD.PNG' height="45%" width="45%"></p>  
  
- KL Divergence 은 3가지 수학적 특징이 존재한다.

> 1. KL Divergence는 항상 0 이상의 값을 갖는다.
> 2. KL Divergence는 비대칭함수이다.
> 3. KL Divergence는 두 확률 분포가 동일할 때 0이 된다.  

- KL Divergence를 엔트로피와 크로스 엔트로피의 합의 공식으로 표현할 수 있으며 아래와 같다.  
- H(p)는 고정된 상수값이기 때문에 결과적으로 **H(p,q)** 를 minimize하는 것이 KL-Divergence를 minimize하는 것과 동일하다.  

<p align="center"><img src='/figure/formula/KLD_divide2.PNG' height="70%" width="70%"></p> 


### 2) Jensen-Shanon Divergence
a
### 3) Total Variation

### 4) Earth Mover Distance
