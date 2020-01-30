# <br/> Breast Cancer Detection
## '고객 데이터 분석 시스템 구축을 위한 빅데이터 전문가 양성과정' 2차 PROJECT : 
  
## 1. '고객 데이터 분석 시스템 구축을 위한 빅데이터 전문가 양성과정'

서울산업진흥원(SBA)과 한국능률협회가 공동으로 진행한 교육인 '고객 데이터 분석 시스템 구축을 위한 빅데이터 전문가 양성과정'는 8월 말부터 11월 중순까지 진행되었으며, 파이썬과 머신러닝, 딥러닝 뿐만 아니라 R과 리눅스, SQL 등에 대해 다양한 교육을 진행하였습니다.

*관련기사*
- [SBA-능률협회, '빅데이터 전문가 양성과정' 절찬 진행중](https://m.etnews.com/20191115000103?obj=Tzo4OiJzdGRDbGFzcyI6Mjp7czo3OiJyZWZlcmVyIjtOO3M6NzoiZm9yd2FyZCI7czoxMzoid2ViIHRvIG1vYmlsZSI7fQ%3D%3D)
- [SBA-능률협회, 빅데이터 신사업 기획자 양성](https://www.dailygrid.net/news/articleView.html?idxno=306146)

## 2. Breast Cancer Detection

두번째 프로젝트로 유방암과 관련된 머신러닝(ML), 딥러닝(DL_CNN), 크롤링(Webscraping) , 텍스트 처리(Text Analysis)을 수행하였습니다. 

- `00. Visualization of Breast Cancer Patient Counts (2010 ~ 2017)` : Lineplot with patients_counts(2011 ~ 2017)
- `01. Visualization By Regions(map) - Breast Cancer Patient Counts in Korea` : Show patients_counts by map (using Folium)
- `02. Web Crawling - News Articles (Naver.com) Related to 'Breast Cancer' ` : 'Naver.com' articles scraping with keyword 'Breast Cancer'
- `03. Text Analysis of Articles (Breast Cancer)` : Text analysis using scraped articles' texts.
- `04. Breast_Cancer_EDA_ML ` : Machine Learning Detection Model using wisconsin BC data.
- `05. Breast_Cancer_DL(CNN) ` : Modeling CNN Detection Model using Histopathologic Images of BC.

## 3. Dataset

Kaggle의 Breast Cancer 관련 Data를 통해 진행하였습니다. ML의 Data로는 Wisconsin_Data를 사용하였고, DL의 Data로는 Histopathologic Cancer Image Data를 사용하였습니다.
  
- [breast-cancer-wisconsin-data](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)
- [Histopathologic Cancer Detection Data](https://www.kaggle.com/c/histopathologic-cancer-detection/data)

환자 수 지도 시각화의 경우 [공공데이터포털](http://data.go.kr)의 json 파일을 이용하였습니다.
