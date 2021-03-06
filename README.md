# 추천 시스템 평가 요소
## 1. MAE
## 2. MSE
## 3. RMSE
## 4. HR(Hit Rate) : 적중률
![image](https://user-images.githubusercontent.com/76590396/159428851-2f51f9d4-03a5-481d-8f1e-bc76a0aeb857.png)
## 5. ARHR(Average Reciprocal Hit Rate)
![image](https://user-images.githubusercontent.com/76590396/159427860-b72bccc8-c141-4124-ac1d-6d91a9df9806.png)

## 6. cHR(cumulative Hit Rate)
## 7. rHR(ratin Hit Rate) : 평점 적중률
## 8. RMSC
## 9, Coverage(제공률)
## 10. Diversity(다양성)
## 11. Novelty(참신성)

## 12. Churn(이탈)
## 13. Responsiveness(민감성)

# 추천 시스템 교차 검증
## 1. K-Fold Cross-Vaildation
## 2. Leave-One-Out Cross-Validation

# 추천시스템 이슈
## Long tail 법칙 : 매출의 80%는 전체 제품의 20%에서 나온다는 것으로, 파레토 법칙과 반대되는 개념
### - 매출 상위 20% 제품들은 많은 사람들에게 알려진 대중적이고 신뢰성이 있는 제품군, 매출 하위 80% 제품들은 많은 사람들에게 익숙치 않은 유니크하고 새로운 제품군
### 추천 시스템은 참신성(새로운 제품을 추천해주는 요소 - 새로운 상품)과 신뢰성(많은 소비자들에게 인정을 받았던 제품을 추천해주는 요소 - 익숙한 상품)의 균형점을 찾아 적절하게 소비자들에게 추천해줄 수 있어야 함.
## Surrogate Problem(대리문제) : 평가를 정확하게 측정했음에도 불구하고, 추천이 좋지 못한 경우를 말함(ex. 유튜브 추천 알고리즘의 정확도는 높았으나, 실제 생황에선 추천 해준 영상을 시청자들이 시청하지 않는 현상)
# A/B Test

# Perceived Quality(지각 품질 측정) : 고객들에게 제공해준 특정 추천 목록이 긍정적이었는지를 직접적으로 확인하는 방법 (ex. 평점을 받거나 긍정 혹은 부정으로 평가)
## - 장점 : metric보다 실 사용 고객들의 응답이기 때문에 실질적으로 이용하기에 더 좋은 평가 지표라고 볼 수 있음.
## - 단점 : 추천 리스트를 평가하는데 주관적인 요소가 많아 해석하는데 오래걸릴 수 있으며, 고객들 또한 평가 측정 방식에 혼동이올 수 있음. 뿐만 아니라, 명시적으로 받아내는 평가 요소이기 때문에 많은 데이터 셋 구축에 어려움이 있음.
