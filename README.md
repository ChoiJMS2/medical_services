# Medical Service 
## Medical notification service for single-person households

[Streamlit 링크]() <br/><br/>
[발표 영상]() <br/><br/>
[데모 시연]() <br/><br/>
[포트 폴리오]() <br/><br/>
![screensh]()

## 1.프로젝트의 시작 (2023.05.22 ~ 2023.06.23)
- 1인 가구를 위한 의료기관 알림 서비스 
 
## 2. 프로젝트 목표 : 의료기관 검색 및 매칭 서비스 
- 공공 데이터 API 를 통한 실시간 데이터 수집
- GPS로 위치를 확인하여 인근의 병원과 약국의 위치 확인
- 인접 의료기관과 Matching을 할 수 있도록 서비스 제공
- 1인 가구 및 유아동 의료 서비스 접근성 확대
- 
## 3. 세부 수행 내용
- 건강보험심사평가원 API와 응급센터 찾기 OPEN API 및 병원, 의원, 증상에 관한 Data 수집
- 건강보험심사평가원, 응급센터 DB 로딩 및 전처리
- 병원(의원) 및 약국 데이터 분석, 시각화
- 이용자와 의료기관(병원, 의원, 응급센터, 약국) 매칭
- 이용자의 GPS를 이용하여 인접 위치에 대한 의료기관(병원, 의원, 응급센터, 약국)의 정보 제공
- 인접한 심장제세동기 위치 제공 및 응급신고 버튼 제공

## 4. 데이터
- 공공 데이터 API
  + 건강보험심사평가원
  + 공공 데이터 
  + 지도
   
## 5. ERD (개체 관계 모델)
![screensh]()

## 6. 팀 구성
- 사용언어 : Python : 3.9.13v
- 작업툴 : VS code
- 인원 : 1명
- 주요 업무 :
  + 공공데이터 API를 통한 데이터 수집
  + DB 로딩 및 전처리
  + 시각화, 공간 정보 분석을 통한 데이터 분석 및 시각화
  + Streamlit 대시보드 개발을 통한 웹 서비스
- 기간 : 2023.05.22 ~ 2023.06.23
***

## 7. 주요 기능
- Home
  + 
- Description
  + 
- Data
  +  
- EDA
  +   
  + 
  + 
  + 
- STAT
  + 
  + 
- DL
  + 
  + 
***

## 8. 설치 방법
### Windows
+ 버전 확인
    - vscode : 1.74.1
    - python : 3.9.13
    - 라이브러리 : pandas (1.5.3), numpy (1.23.5), plotly (5.14.1), matplotlib (3.7.1), streamlit (1.21.0), seaborn (0.12.2), pingouin (0.5.3), statsmodels (0.13.2), scikit-learn (1.2.2), xgboost (1.7.5), pandas-profiling (3.6.3), streamlit-option-menu (0.3.2), streamlit_pandas_profiling (0.1.3), scipy(1.9.1), 


- 프로젝트 파일을 다운로드 받습니다. 

```bash
git clone https://github.com/ChoiJMS2/medical_services.git
```

- 프로젝트 경로에서 가상환경 설치 후 접속합니다. (Windows 10 기준)
```bash
virtualenv venv
source venv/Scripts/activate
```

- 라이브러리를 설치합니다. 
```bash
pip install -r requirements.txt
```

- streamlit 명령어를 실행합니다. 
```bash
streamlit run app.py
```