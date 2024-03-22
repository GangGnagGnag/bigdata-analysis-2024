## 10일차 학습
- 빅데이터 실습
    - OpenAPI 기반 크롤링 실습
    - 통계 분석 리뷰
    - 머신러닝 실습
    

### 빅데이터 실습
#### 통계 분석 리뷰
- 그래프를 사용한 기술 통계 분석
- 히트맵을 사용한 상관분석

##### [와인 품질 분석](https://github.com/GangGnagGnag/bigdata-analysis-2024/blob/main/day10/da21_%EC%99%80%EC%9D%B8%ED%92%88%EC%A7%88%EB%93%B1%EA%B8%89_%EB%B6%84%EC%84%9D.ipynb)
- [캘리포니아 오바인 대학 연구소](https://archive.ics.uci.edu/dataset/186/wine+quality)
- 기존에는 웹사이트 데이터 다운로드 방식에서 어바인 연구소에서 데이터 다운로드 모듈 개발(python import 형식)다운로드
- 가술통계, 기존방식의 분석 사용
- 회귀분석, 기존의 데이터만으로 선형회귀를 도출

    ![회귀분석](https://raw.githubusercontent.com/GangGnagGnag/bigdata-analysis-2024/main/images/ba012.png)

##### [타이타닉 생존자 분석](https://github.com/GangGnagGnag/bigdata-analysis-2024/blob/main/day10/da22_%ED%83%80%EC%9D%B4%ED%83%80%EB%8B%89%EC%83%9D%EC%86%90%EC%9E%90_%EC%83%81%EA%B4%80%EB%B6%84%EC%84%9D.ipynb)
- seaborn 모듈내 샘플데이터 셋
- 생존자 상관분석 : 두 변수간의 상관관계를 유추. 상관관계 있는 변수들로 더 자세한 분석할 지표
- 0.0 ~ 1.0 사이 상관계수 값
- 0.5 ~ 0.9 의 결과가 나오는 변수들 끼리 재분석
- 결측지 검색, 제거

    ![상관분석히트맵](https://raw.githubusercontent.com/GangGnagGnag/bigdata-analysis-2024/main/images/ba014.png)
