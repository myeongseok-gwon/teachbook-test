# CATE & Policy

- 기본적으로 (Y, T, X)로 보자. 우리는 Y(T=1|X) - Y(T=0|X)이 궁금하다.
- 가장 간단한 형태의 CATE는 OLS에서도 가능하다.
- 비모수적인 다양한 모델을 살펴보자. 그리고 Ground-truth가 없는데, 어떻게 비교할 수 있는지, 그리고 Confidence Interval까지 잘 이해해보면 좋겠다.
- 마지막으로 Policy Learning. CATE를 추정하고, 비용보다 CATE가 크면 처치하는 게 가장 기초적인 policy이다. 하지만 만약 interpretability가 중요하다면 어떻게 해야 할까? 예산에 제약이 있다면 어떻게 해야할까? 그리고 Confidence Interval까지 잘 이해해보자.