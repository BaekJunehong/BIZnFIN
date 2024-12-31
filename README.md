# DAT BIZ&amp;FIN 대파팀 스터디    

### 1. 프로젝트 진행하기에 앞서 4주간의 기간동안 관련 공부를 진행   

1-1. 코드 학습   
기업, 재무, 금융 관련 데이터 분석을 목표로 스터디를 진행    
- 데이콘의 신용카드 사용자 연체 예측 코드 분석    
- 캐글의 대만기업 부도예측 데이터 분석   

1-2. 선행연구 분석    
부실기업 및 부도기업에 대한 선행연구를 분석하고자 함  
선행연구로 관련 논문들을 분석함  

### 2. 이후 4주간의 기간동안 프로젝트를 진행

기업 부실화가 기업과 국가 경제에 미치는 부정적 영향을 고려하여,  
딥러닝 모델을 활용한 한계기업 예측의 성능을 분석  

이를 위해 2020년부터 2024년까지 KOSPI, KOSDAQ, KONEX 및 
외부감사 대상기업의 재무비율 데이터를 활용하였으며,  
데이터 전처리와 변수 선정 과정을 수행

분석에는 MLP, CNN, LSTM, GRU 모델을 적용하였으며,  
성능 평가는 정확도와 F1-Score를 기준으로 진행  

그 결과, 은닉층 2개(노드 64개)로 구성된 GRU 모델이  
가장 우수한 성능을 보였으며, 예측확률을 기준으로 기업을 안전(0.18 미만),  
위험(0.18 이상), 매우 위험(0.6 이상)으로 분류

아울러, 재무비율을 특성에 따라 군집화하고  
각 군집별 변수로 부실기업 위험도를 평가하여,  
단순한 부실여부 예측을 넘어 기업 부실에 영향을 미치는 주요 요인을 제시   

결과적으로 딥러닝 기반 예측 모델의 유용성을 입증함과 동시에  
기업 부실 예방을 위한 의사결정 지원 가능성을 제안


## homework      
DAT 학회활동동안 주 1회 총 5번의 과제를 해결    
- 데이터 분석(자유분석)    
- 파이썬 기본 문법(Pandas, Numpy, Matplotlib)      
- API를 활용한 데이터 불러오기 및 분석     
- 주가 데이터에 대한 시계열 예측 및 분석      
- 이미지 데이터 분석 및 클러스터링    
  
## papper        
프로젝트 관련 선행연구로 논문 조사        
  
## project  

| date | title | text  |    
|-----------|------------|------------|      
| 10/30 | 중간발표 | 프로젝트 중간점검 발표 |     
| 11/24 | 연합세미나 | 타 동아리(KUSEA)와의 발표 공유회 |     
| 12/5 | 최종발표 | 프로젝트 최종 마무리 발표  |       
   
## study         
| time line | text  |    
|-----------|------------|    
| 1 ~ 2주차 | 데이콘 코드 분석: 신용카드 사용자 연체 예측 코드 분석 |     
| 3 ~ 4주차 | 캐글 코드 분석: 대만 기업부도 데이터 코드 리딩 및 관련 개념 학습 |     
| 중간고사  | 시험기간 및 프로젝트 준비 |  
| 5 ~ 8주차 | 프로젝트 진행 |  

