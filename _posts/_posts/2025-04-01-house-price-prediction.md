---
title: "🏡 주택 가격 예측 앱"
date: 2025-04-01
categories: [머신러닝, 실습, Streamlit]
tags: [Python, Streamlit, LinearRegression]
---

Streamlit으로 만든 간단한 주택 가격 예측기입니다.  
학생들이 면적과 방 개수를 입력하면, 훈련된 선형 회귀 모델이 집값을 예측해줍니다.

👉 [앱 실행하러 가기](https://dryoon.shinyapps.io/ml_app)

해당 모델은 `area`, `bedrooms` 두 개의 특성을 기반으로 가격을 예측하며, Scikit-learn의 `LinearRegression`을 사용했습니다.
