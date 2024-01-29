### 이미지를 통한 감정 분석 모델
-------------------
사용자가 자신이 원하는 표정의 얼굴 사진이나 표정이 포함된 이미지 사진을 
텐서플로우를 활용하여 API를 적용시켜 사진에 대한 감정을 7가지
[화남,우울함,두려움,행복,슬픔,놀람,중림] 으로 분석하여 줌.   
-->감정에 따른 영화 추천 서비스

-- 예측 모델: 얼굴 감정 분석 알고리즘의 구현된 부분으로 얼굴의 7가지 감정으로 분류 된다.   
-- 데이터 분석: 감정결과와 가지고 있는 movie.csv 를 바탕으로 같은 감정을 찾아 새로운 CSV 로 저장이 되는 부분

##### Feeling.ipynb 
Keras 와 TensorFlow 를 사용하여 딥러닝 모델 구축 및 훈련
##### test.py 
훈련된 모델 적용시킨 후 파라미터 적용

##### 서비스 화면

![image](https://github.com/Choiyounsou/EmotionAnalysisFrom-Picture/assets/131225182/9193e80e-09e3-4d20-b8fb-55fd1019a409)
웹 페이지 게시판 처럼 내용 불러오는 페이지 완

![image](https://github.com/Choiyounsou/EmotionAnalysisFrom-Picture/assets/131225182/5c4423a3-57d8-41ef-826f-42ed859666de)
사진 분석결과 와 movies.csv 의 feeling 결과를 토대로 랜덤한 값 7개를 추출하는 csv 완성
웹 사이트에 DB연동
