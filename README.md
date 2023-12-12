# Medical Location Bigdata Analysis 🏥
## Analysis of location selection for residential areas with weak medical services at Yong-in 
#### Member : 최대현(PM, Data Scientist), 두현영(Data Analysist)
#### Project execution period : 2023.09~2023.12
#### Project Hosting : [최대현](https://www.notion.so/Bigdata-Analysis-2f8eae0f741b4e8aac4d48a2a530024a?pvs=4)
-----------------------

## 0. Service description
### Final Visualization 
![image](https://github.com/dablro12/Potential-Hospital-Location-Variable-in-Yongin-si/assets/54443308/6c395273-d4de-48e5-ac39-3588f4824a14)


## Background & Purpose
#### Background
- 의료시설 부족: 모현 지역에서 의료시설 부족으로 환자들이 불편함을 겪고 있음.
- 의료 인력 유입 필요성 인식 : 의과대학 입학생 증가하나 인프라적 문제로 인한, 인력 유입 필요성.
- 최근 의료 정책 변화 대응: 최근 의료 정책 변화로 인한 의료 시설 간 경쟁 증가에 대응.
#### Purpose
- 용인시 인프라 및 인구 및 보건 의료 데이터를 사용하여
1. 각 읍면구 지역군으로 나누어, 지역에 따른 의료 서비스 필요 지역을 모색
2. 모현 및 다른 지역 정보 분석 및 병원 개설 요구 사항 결정:
- 해당 지역 의료 인력 소개 및 시설 위치 분석.
- 모현 지역 의료 서비스 향상과 인력 유입 촉진.

## Dataset 
![image](https://github.com/dablro12/Potential-Hospital-Location-Variable-in-Yongin-si/assets/54443308/635f6aa7-701e-45d5-8964-4742c8224390)


## Environment
> Python Version 3.8.18
> Linux Ubuntu


## Prerequisite

> import pandas as pd
>
> import numpy as np
>
> import seaborn as sns
>
> import matplotlib.pyplot as plt
>
> from pyproj import Proj, transform
>
> from sklearn.preprocessing import MinMaxScaler, StandardScaler
>
> from sklearn.ensemble import RandomForestRegressor
>
> from sklearn.cluster import KMeans
>
> from sklearn.model_selection import train_test_split
>
> from sklearn.linear_model import LinearRegression
>
> from sklearn.metrics import mean_squared_error
>
> import plotly.express as px
>
> import plotly.graph_objects as go
>
> from plotly.subplots import make_subplots
>
> import folium
>
> from folium.plugins import HeatMap
>

## Files & Foloder
`main.ipynb` 데이터 전처리 및 빅데이터 분석 코드

`Analysis_visualzation` 의료 입지 중요 변수 분석 및 시각화

`clustering` K-mean Clustering 군집 분석 결과 

`corr_analysis` 중요 칼럼 추출을 위한 상관계수 분석

`data` 데이터 전처리된 파일 

`Linear_model` 선형회귀모델을 이용한 의료입지에서의 비용이 건강보험료, 의료시설, 직장인프라 독립변수에 대한 선형회귀모델

`Visualization_Result` 최종 시각화 결과

## Visualization
###
![화면 기록 2023-12-12 오전 8 15 09 (1)](https://github.com/dablro12/Potential-Hospital-Location-Variable-in-Yongin-si/assets/54443308/0c8604cc-b450-460d-95e6-f4c9512a4637)

###
![newplot (3)](https://github.com/dablro12/Potential-Hospital-Location-Variable-in-Yongin-si/assets/54443308/71ceb9d4-0f4c-464e-a140-ec566740363f)

###
![newplot (5)](https://github.com/dablro12/Potential-Hospital-Location-Variable-in-Yongin-si/assets/54443308/f9ccc86f-5f90-4512-b8ac-d83ef7c19372)

## Usage 
`main.ipynb`
