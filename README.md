<img width="1693" height="929" alt="항공 ai" src="https://github.com/user-attachments/assets/e546613c-f588-49c5-b36e-bc1b4fa200e4" />

# ✈️ AI 기반 항공 고객 만족도 예측 및 서비스 개선 분석

고객 설문 데이터를 기반으로 항공 서비스 만족도를 예측하고 서비스 개선 방향을 도출한 AI 데이터 분석 프로젝트입니다.
머신러닝 및 딥러닝 모델링을 통해 고객 만족도에 영향을 주는 핵심 요인을 분석하고, 추가 학습(Fine-tuning)과 전처리 파이프라인 구성을 수행했습니다.

---

## 📌 Project Overview

최근 고객 설문 데이터에서는 높은 만족도가 나타났지만, 실제 고객 불만은 지속적으로 발생하는 문제가 존재했습니다.

이를 해결하기 위해:

- 고객 만족도 예측 모델 구축
- 핵심 영향 변수 분석
- 서비스 개선 인사이트 도출

을 목표로 프로젝트를 진행했습니다.

---

## 🧠 Problem Statement

설문 결과와 실제 고객 경험 사이에는 차이가 존재했습니다.

예를 들어:

- 출발 지연 문제
- 온라인 체크인 불편
- 좌석 공간 불만
- 서비스 만족도와 실제 경험 간 괴리

등이 발생하고 있었습니다.

본 프로젝트에서는 데이터를 기반으로 이러한 문제를 분석하고 예측 모델을 구축했습니다.

---

## ⚙️ Tech Stack

### Language & Library
- Python
- Pandas
- NumPy

### Machine Learning / Deep Learning
- Scikit-learn
- TensorFlow / Keras

### Visualization
- Matplotlib
- Seaborn

### Environment
- Jupyter Notebook

---

## 📂 Dataset

- Airline Passenger Satisfaction Dataset
- Kaggle Dataset 활용

데이터 구성:
- 고객 정보
- 비행 정보
- 서비스 만족도 점수
- 지연 시간
- 최종 만족도(Satisfaction)

---

## 🔍 Main Tasks

### 1. 데이터 전처리
- 결측치 처리
- Label Encoding
- One-Hot Encoding
- 불필요 변수 제거
- 스케일링

### 2. 데이터 분석
- 변수별 고객 만족도 분석
- 연령대별 데이터 분석
- 서비스 품질 영향 요인 분석
- 변수 중요도 확인

### 3. 머신러닝 모델링
- 트리 기반 모델 학습
- 변수 중요도 분석
- 모델 성능 비교

### 4. 딥러닝 모델링
- 다양한 딥러닝 모델 실험
- 모델 성능 비교
- Fine-tuning 수행
- 모델 성능 개선

### 5. 전처리 파이프라인 구성
- 반복 작업 자동화
- 데이터 처리 일관성 유지
- 모델 입력 구조 통일

---

## 📈 Key Insights

- 단순 만족도 점수만으로 실제 고객 경험을 완전히 설명하기 어려웠음
- 출발 지연 및 온라인 서비스 품질이 고객 만족도에 큰 영향을 미침
- 데이터 분리 모델링을 통해 연령대별 중요 변수가 다르게 나타남
- 전처리 방식에 따라 모델 성능 차이가 크게 발생함

---

## 💡 What I Learned

- 데이터 기반 문제 해결 접근 방식
- 머신러닝/딥러닝 모델링 경험
- Fine-tuning 과정 이해
- 전처리 파이프라인 구성 경험
- 모델 성능 개선을 위한 실험 과정 경험

---

## 📁 Repository Structure

```bash
airline-customer-satisfaction-ai
│
├── notebooks/
│   └── customer_satisfaction_prediction.ipynb
│
├── images/
│   └── cover.png
│
└── README.md
```

---

## 🖼 Project Cover

고객 만족도 예측을 통한 서비스 개선

---

## 🚀 Future Improvements

- XGBoost 및 LightGBM 모델 추가 실험
- Explainable AI(XAI) 적용
- 실시간 고객 만족도 예측 시스템 확장
- Streamlit 기반 대시보드 구현

---

## 👩‍💻 Author

장현지  
AI Application Developer
