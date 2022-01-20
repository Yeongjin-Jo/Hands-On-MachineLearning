# Sigmoid 함수 
- 시그모이드 함수란 실수 정의역 범위에서 최댓값이 1이하이고 최솟값이 0이상인 미분가능한 단조증가함수
(단조증가함수 : 정의된 범위에서 감소하는 구간이 없는 함수) 
- 시그모이드 함수는 특정한 하나의 함수가 아니라 이런 조건을 만족하는 함수 집합 
- tanh x, arctan x, logistic function이 모두 시그모이드 함수이다. 
- 이 중, 로지스틱 함수를 사용하는 이유는 미분 계산이 쉽기 때문이다. 

# Logistic Function 
- logistic function 수식 
- ![image](https://user-images.githubusercontent.com/66348480/149303811-9b1ccf45-5d25-4012-970b-c87e455bdbb8.png)

- logistic function은 Odds 개념으로부터 시작 
- Odds는 어떤 사건이 일어날 확률 / 어떤 사건이 일어나지 않을 확률 
- Odds의 양변에 로그를 취하여 확률이 0.5를 기준으로 양 옆 증감폭이 같게 해줌 
- 이를 역함수를 취하면 로지스틱함수가 나옴 


