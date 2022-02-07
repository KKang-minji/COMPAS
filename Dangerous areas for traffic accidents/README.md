# 주제 : 교통사고 위험지역 100곳 도출
기간 : 2021년 03 월 ~ 2021년 05 월

결과
입상

폴더 구조

실행 환경
Jupyter notebook

필요 라이브러리
geopandas
pandas
numpy
folium
geoband.API
matplotlib.pyplot
통계적 방법론 라이브러리
corrplot
library(lmtest)
library(dplyr)
library(nortest)
library(sf)
library(tmap)
library(sp)
library(RANN)
library(spdep)
library(rgdal)
library(RColorBrewer)
library(leaflet)
library(maptools)
library(gvlma)
library(tidyr)
library(leaps)
library(ggplot2)
library(broom)
library(MASS)
library(rsq)
library(gridExtra)
library(spgwr)
library(spatialreg)
library(geojsonio)


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


분석 도구 : R, Pyhon, QGIS,  Google Maps
