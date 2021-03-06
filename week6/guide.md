# Guide - 분석 가이드와 코딩 시나리오

## 숫자 손글씨 인식하기

### 분석 가이드

1. **문제를** **이해합니다.**  이미지의 각 픽셀을 특징 데이터로 취급하여 어떤 숫자인지 인식하는 문제입니다.
2. **EDA** **및** **Feature Engineering을** **실시합니다.**  어떤 식으로 이미지의 픽셀을 특징 데이터로 구성하였는지 파악합니다.
3. **가설** **검증** **계획을** **수립합니다.**  classfication을 다루는 머신러닝 모델링
4. **데이터셋을** **구성합니다.**  상황과 목적에 따라 적절한 train set, \(validation set\), test set을 구성합니다.
5. **모델링하고** **학습합니다.**  DecisionTreeClassifier, RandomForestClassifier, …
6. **모델을** **평가하고** **검증합니다.**
7. **최종** **결론을** **도출합니다.**  000모델을 통해 000의 정확도로 숫자 손글씨를 OCR할 수 있다.

### 코딩 시나리오

1. **데이터를** **불러옵니다.**
2. **EDA** **및** **Feature Engineering을** **실시합니다.**
3. **데이터셋을** **구성합니다.**
4. **모델링하고** **학습합니다.**
5. **모델을** **평가하고** **검증합니다.**
6. **최종** **결론을** **도출합니다.**

## 와인 품질 측정하기

### 분석 가이드

1. **문제를** **이해합니다.**  와인의 각종 화학데이터를 기반으로 실제 와인 품질을 추정하는 문제입니다.
2. **EDA** **및** **Feature Engineering을** **실시합니다.**  주요 특징과 중요성이 떨어지는 특징을 구분하고 각종 시각화를 진행하여 데이터 구조를 이해합니다.
3. **가설** **검증** **계획을** **수립합니다.**  regression을 다루는 머신러닝 모델링
4. **데이터셋을** **구성합니다.**  상황과 목적에 따라 적절한 train set, \(validation set\), test set을 구성합니다.
5. **모델링하고** **학습합니다.**  DecisionTreeRegressor, RandomForestRegressor, LinearRegression, Ridge, PolynomialFeatures, …
6. **모델을** **평가하고** **검증합니다.**  더 좋은 평가 방식이 있는지 고민합니다.
7. **최종** **결론을** **도출합니다.**  000모델을 통해 000의 정확도로\(혹은 다른 평가지표\) 와인의 품질을 추정할 수 있다.

### 코딩 시나리오

1. **데이터를** **불러옵니다.**
2. **EDA** **및** **Feature Engineering을** **실시합니다.**
3. **데이터셋을** **구성합니다.**
4. **모델링하고** **학습합니다.**
5. **모델을** **평가하고** **검증합니다.**
6. **최종** **결론을** **도출합니다.**

