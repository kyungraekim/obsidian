계산
- 설명변수 하나를 Y, 나머지를 X로 두어 회귀분석
- VIF = 1 / (1 - R^2)
분석
- 10 이상인 설명변수는 다중공선성이 높다고 판단
해결
- 다중공선성이 있는 독립변수 제거
- 주성분 분석(PCA)으로 추출된 주성분으로 회귀 분석 수행
- Ridge regression으로 계수의 자동 조정을 통해 영향을 제어