## 주제 : 교통사고 위험지역 100곳 도출
기간 : ```2021년 03 월 ~ 2021년 05 월```

### 수상🏆 : ```입상```

#### 실행 환경
```Jupyter notebook```
#### 분석 도구 : ```R```, ```Python```, ```QGIS```, ```Google Maps```

### 사용 데이터 
```compas 비공개 데이터```

### 🌼 주요 업무 🌼
```
- 데이터 전처리
- EDA 분석
- PPT 작성
```

### 📝 분석배경
```
대전시에서는 개인의 고통과 피해는 물론 사회적으로도 막대한 손실을 야기하는 교통사고 예방을 위해 다양한 교통안전정책을 꾸준히 추진하고 있으며 그 결과 교통사고 사망자 수는 지속적으로 감소하고 있습니다.
하지만 자동차의 증가와 전동 킥보드 등 새로운 운송수단의 등장 등으로 교통사고 발생건수는 감소하지 않고 있음에 따라 보다 효과적인 교통안전대책을 수립하기 위한 심도 있는 선행 분석이 필요합니다.
```
### 🚩 분석목적
```
본 과제는 유형별 교통사고 데이터와 교통안전시설물, 거주인구, 교통량 데이터 등을 활용, 대전시 내 교통사고 발생 위험지역을 도출하여 교통안전시설물 추가 설치 시 우선 검토 등 정책 기초자료로 활용하기 위한 분석 모델 도출을 목적으로 합니다.
```
### 분석 시 고려사항
```
- 위험지역 범위는 중심점으로부터 반경 50m를 기준으로 함(단, 분석결과에 따라 반경을 변경하여 제시 가능)
- 연령대별 교통사고 유형 및 사고유형(차대사람, 차대차 등)과 교통안전시설물간의 인과관계를 고려(분석)한 결과 제시
- 사용자가 자유롭게 필요 데이터를 발굴하여 사용 가능하나 최종 결과파일 제출 시 데이터 출처와 사용한 데이터도 함께 제출
- 외부 데이터는 법적인 제약이 없는 경우에만 허용되며 크롤링을 통해 데이터를 생산 한 경우 크롤링 코드도 함께 제출
```
### 🏃 Project 수행 흐름도
```
- 데이터 수집
  - COMPAS 제공 (데이터셋 33개)

- 데이터 전처리
  - 사용할 데이터 및 변수 선정
  - GID 기준 데이터셋 구성
  - 결측치 처리 및 스케일링

- 예측 모델링 + 모형 성능 평가
  - 일반 회귀 모형
  - 포아송 회귀 모형
  - 음이항 회귀 모형
  - 선형 회귀 모형
  - 회귀 나무 모형
  - 신경망 모형
  - 랜덤 포레스트 모형 + 잔차 분석을 통해 각 모형의 성능 평가

- 최적 모형 선정
  - 음이항 회귀모형

- 교통사고 위험지역 100곳 예측
  - PSI(잠재적 교통안전 개선 지수)
  - 위험도 점수 산정
```

### 👀 아쉬운 점 
```
1. 수미상관 (분석흐름도)시각적으로 제시

2. 정확도와 분포의 모양을 보여줬으면 한다.
	- 실체값과 예측 모형 비교
	- 결과부분 d_score 관련

3. 결론은 주관적인 해석들이 들어가야 좋다.
	- 집어서 클로즈업해서 주관적인 내용
```
