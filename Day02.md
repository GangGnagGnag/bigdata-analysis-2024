## 2일차 학습
    - 빅데이터 학습

### 빅데이터 학습 

#### 데이터 분석 기초(~ing)

##### Pandas 학습(~ing)

2. Pandas 내용 통합(merge, concat)

    ![concat결과](https://raw.githubusercontent.com/GangGnagGnag/bigdata-analysis-2024/main/images/ba002.png)

3. Pivot테이블


##### pandas 2.0 이상 문제 확인
- 두 데이터를 합치기 위한 append() 함수가 제거됨
    - https://pandas.pydata.org/docs/whatsnew/v2.0.0.html

- pd.concat() 함수로 대체

#### Numpy 학습
Numpy는 행렬처리 수치 계산을 손쉽게 할 수 있도록 도와주는 계산관련 라이브러리
Scipy는 과학쪽에 특화된 계산관련 라이브러리
- DF에서 수치적으로 처리할 게 있으면 numpy로 변경한 다음, 계산 처리한 뒤 다시 DF로 변경

#### Matoplot.lib / Seaborn
Matoplot.lib / Seaborn은 데이터 시각화 라이브러리
Matoplot.lib 기본, Seaborn은 Matoplot.lib 확장 버전

#### Selenium
- 웹브라우저 제어 라이브러리
- 크롬 드라이버 필수

    1. 현재 크롬 브라우저 버전 확인 
        ![크롬버전확인](https://raw.githubusercontent.com/GangGnagGnag/bigdata-analysis-2024/main/images/ba003.png)
    
    2. https://googlechromelabs.github.io/chrome-for-testing/ 에서 다운로드
    3. 시스템속성 > 환경변수 경로 등록 > 
    4. 셀레니움 연동, 실행

        ![크롬버전확인](https://raw.githubusercontent.com/GangGnagGnag/bigdata-analysis-2024/main/images/ba004.png)
