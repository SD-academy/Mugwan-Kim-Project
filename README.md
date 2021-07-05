# Mugwan-Kim-Project

## ▶주제 
 - 선거여론조사(전화조사)에서 지지후보(핵심문항)에 대해서 응답자들은 보통 80-85%정도는 응답하지만, 10-15%정도는 '없음/모름'으로 응답을 하지 않아, 새로운 파이썬 머신러닝을 활용해서 80-85% 응답을 가지고 학습 시켜서 10-15% 무응답을 예측해 보고자 한다


## ▶데이터
![image](https://user-images.githubusercontent.com/83946378/124430988-cc7f3680-ddaa-11eb-9a50-00cbd69d3195.png)


## ▶분석방법 : 파이썬, 오렌지 프로그램


## ▶검증 방법
 - 19대 대통령선거 개표결과 VS 무응답 보정된 여론조사데이터 비교 (무응답 예측데이터 반영후 spss프로그램 비율테이블 돌려서 비교)
 - 오렌지 프로그램 예측데이터 VS 파이썬 머신러닝 예측데이터 비교 (각각의 무응답 예측데이터 엑셀 정리후 비교)


## ▶인사이트
 - 파이썬 머신러닝을 활용해서 무응답 예측을 함으로써, 선거여론조사(다른 전화여론조사 포함) 예측 정확도를 좀 더 높여 보고자 한다
![image](https://user-images.githubusercontent.com/83946378/124427663-a3f53d80-dda6-11eb-9266-1053ca65da28.png)


==========================================================================================


## ▶프로젝트 진행상황
### 기간 : 1주차, 6월 21일~ 6월 27일
 - 목표 : 데이터 특징 파악

 - 진행상황 : 
  - 후보별(지지후보문항)로 문항별 요약테이블(막대그래프,원그래프) 작업.
  - 후보별 응답데이터 특징 파악
  - 추가변수 생성작업(성별*연령대 생성변수( ex) 남자-30대, 여자-40대), 이념성향 리코드 변수, 직업재분류 변수)


### 기간 : 2주차,6월 28일 ~ 7월 4일
 - 목표 : 머신러닝 알고리즘(모델)을 선택해서 전체적인 작업 프로세스를 구현(우선 돌려보고, 정확도 높이는 것은 나중 문제)

 - 진행상황
  - 파이썬 머신러닝 XGBoost 모델을 선택해서 전체적인 작업(무응답 예측) 구현
  - 오렌지 프로그램을 사용해서 무응답예측 구현


### 기간 : 3주차, 7월 5일 ~ 7월 11일
 - 목표 : Xgboost 모델 성능(예측 정확도) 높이는 작업
         머신러닝 모델선택시, 여러가지 모델(알고리즘)을 한꺼번에 작동시켜 성능 좋은 모델 쉽게 선택할 수 있도록 함수 구현
         오렌지 프로그램 성능(예측 정확도) 높이는 작업
