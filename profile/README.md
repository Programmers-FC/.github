# 🎮 Programmers FC - 게임 데이터 분석 대시보드

## 우수 프로젝트 !

<img width="756" alt="image" src="https://github.com/user-attachments/assets/d2ac5758-7e0e-4d47-9f63-af90d4aca548" />
<img width="463" alt="스크린샷 2025-03-27 오후 9 09 52" src="https://github.com/user-attachments/assets/301fd3dd-7b45-4c82-8f06-df2ed698be81" />


## 📌 프로젝트 개요

게임 API와 커뮤니티 데이터를 활용하여 인게임 현황을 시각적으로 제공하는 웹사이트 및 데이터 분석 대시보드를 구축하는 프로젝트입니다. 주된 예시로는 넥슨 FC온라인 API를 활용하여 포지션별 인기 선수 순위, 선수 리뷰 감정 분석, 매치 데이터 분석 등을 진행하며, 추후 예측 및 추천 시스템 개발까지 확장할 수 있습니다.

---
## 👥 팀 구성
<img width="756" alt="image" src="https://github.com/user-attachments/assets/968cf58b-424b-424d-adf6-acf8119310ca" />

## 🛠 기술 스택
- **데이터 엔지니어링:** Airflow, Spark
- **Deploy & Infra**: Docker, GitHub, GitHub Actions
- **프론트엔드:** Streamlit, React, Django 중 선정 예정 -> Streamlit 선정
- **데이터 웨어하우스:** Redshift
- **감정 분석 모델:** SparkML

## 📆개발 기간
- **2025. 02. 18 ~ 2025. 03. 19 (5주)**
       
## 🚩 프로젝트 진행 계획 (총 5주)
| 단계 | 주요 작업 | 기간 |
|------|-----------|-------|
| 1단계 | 데이터 수집 및 조사 (API 분석, 크롤링 테스트) | 1주 |
| 2단계 | 데이터 전처리 및 분석 (인기 선수, 감정 분석) | 2주 |
| 3단계 | 대시보드 개발 및 웹사이트 구현 | 3주 |
| 4단계 | 테스트, 디버깅 및 최종 발표 준비 | 4주 |
| 4단계 | 마지막 점검 및 최종 발표 | 5주 |
### 실제 진행 과정

<img width="774" alt="image" src="https://github.com/user-attachments/assets/3c2add23-0163-496d-a425-ad5b243cada2" />

![image (2)](https://github.com/user-attachments/assets/9da07b59-cd44-4666-8fa1-a028cb4547ef)

## ⚙️ 주요 기능

### ✅ 포지션별 인기 선수 순위
- 최근 매치 데이터를 분석하여 포지션별로 가장 많이 사용된 선수의 순위를 시각화합니다.

### ✅ 선수 리뷰 감정 분석
- 인벤 및 블로그에서 크롤링한 사용자 리뷰 데이터를 TF-IDF+LR 모델을 이용해 긍정/부정으로 분석하고 시각화를 제공합니다.

### ✅ 매치 데이터 분석
- 경기 승률, 인기 전술 및 선수 조합 등의 트렌드를 분석하여 사용자에게 제공합니다.

### ✅ 추천 시스템 (추후 논의)
- 머신러닝 모델을 활용하여 사용자 맞춤형 선수 또는 전술 추천 시스템 개발을 고려하고 있습니다.

### 시연 영상
#### 0~30초
![30초까지](https://github.com/user-attachments/assets/9d24657f-34d9-4360-a8b2-71d0114208fc)


#### 나머지 30초 42초
![나머지 42초](https://github.com/user-attachments/assets/359726d6-b3a8-46aa-abf3-f3f9786a68dd)

---



---

## 📊 데이터 출처

### API 데이터
- [넥슨 FC온라인 API](https://openapi.nexon.com/ko/game/fconline/?id=2)

### 크롤링 데이터
- [인벤 FIFA 온라인 4 선수 리뷰](https://fifaonline4.inven.co.kr/dataninfo/player/?code=216001088)
- [Top 10,000랭커 유저 크롤링](https://fconline.nexon.com/datacenter/rank)

---


## 🔥 확장 가능성
- 리그 오브 레전드(LOL), NBA 2K, FIFA 시리즈 등의 다른 게임 데이터를 활용한 분석으로 주제 확장 가능

---



