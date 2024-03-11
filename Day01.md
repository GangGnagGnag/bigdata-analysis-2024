## 1일차 학습
    - 빅데이터 학습

### 빅데이터 학습

#### 빅데이터 개요
- 정의
    - 디지털환경에서 발생하는 대량의 모든 데이터
    - 대량의 데이터를 수집, 저장, 관리, 분석하는 HW/SW 유통, 활용까지 포함
- 특징
    - https://velog.io/@garam/DE-%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%9D%98-%ED%8A%B9%EC%A7%953V-5V-7V

- 기술
    - 순서적으로 데이터 생성 -> 수집 -> 저장 -> 분석(EDA, 머신러닝, 딥러닝) -> 표현(시각화)
    - 생성: IOT, 빅데이터 플랫폼
    - 수집: 빅데이터 플랫폼(하둡(Hadoop), kafka ..., 데이터마이닝)
    - 저장: 빅데이터 플랫폼(kafka ..., 데이터마이닝, NoSQL)
    - 분석: 통계, 머신러닝, 딥러닝, 자연어처리, 패턴인식, 이미지 프로세싱 (Spark, Power BI, Tableau, ...)
    - 표현: Visualization(Power BI, Tableau, ...) 

#### 학습교재
직장인을 위한 데이터 분석 실무 파이썬, 위키북스

- 실습자료: https://github.com/Play-with-data/datasalon

#### 파이썬 리뷰
이전에 파이썬 기초 학습 종료

#### 데이터 분석 기초
데이터 분석을 위한 라이브러리(모듈) 학습부터 시작
- Pandas : 데이터 처리 라이브러리
- Numopy : 수치해석, 계산용 라인브러리
- openpyxl: 엑셀, CSV, JSON 문서 데이터 로드, 저장 라이브러리
- Matplot.lib : 차트 표현 라이브러리
- Seaborn : 시각화 라이브러리

- Selenium : 웹 크롤링 자동화 라이브러리
- BeautifulSoup : 웹 데이터를 정제 라이브러리

- Folium : 지도 시각화 라이브러리
- TensorFlow : 머신러닝 라이브러닝
- PyTorch : 머신러닝, 딥러닝 라이브러리
- ...

추가내용 , [kaggle.com] (https://www.kaggle.com/)

##### Pandas 학습
데이터 분석(로딩, 처리..) 라이브러리

![자료구조](https://raw.githubusercontent.com/GangGnagGnag/bigdata-analysis-2024/main/images/ba001.png)

1. Pandas 자료구조
    - 시리즈, 데이터프레임
    - [데이터프레임 사용법] (https://github.com/GangGnagGnag/bigdata-analysis-2024/blob/main/day01/da01_pandas_basic.ipynb)
    - 데이터 통합
    

##### VS Code 문제확인 
1. Jupyter Notebook 실행 속도 느려지는 문제 - Pylance 충돌
    - Ctrl + ,(설정) > Jupyter > Logging: Level -> off or Verbose로 변경(debug 기본값)
2. Intellisense로 느려짐
    - Ctrl + ,(설정) > TypeScript, Editor > Suggest 모두 해제
    - 필요한 것만 체크해서 사용