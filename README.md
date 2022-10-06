# Resume
Resume for Gee Hyun Kwon

# Introduction


# Work Experience

## Qualtrics (퀄트릭스)
### Machine Learning Engineer
- *Implemented the Affect-X text analysis service API that supports language-agnostic sentiment, emotion and
actionability analysis of freeform text*
- 댓글, 설문조사, 제품 리뷰에서 사람 기분을 읽어내는 인공지능 서비스 개발 [링크](https://www.qualtrics.com/support/survey-platform/data-and-analysis-module/text-iq/sentiment-analysis/)
- 앞서 말한 서비스에서 더 세부화된 감정, 그리고 피드백 실행 가능성을 알려주는 V2 서비스 개발 [링크](https://www.qualtrics.com/iq/text-iq/)
- *Designed the V2 API for Model Management Service, allowing sharing of ML models inside the company and
consistent reuse of inference endpoints*
- *Added support for asynchronous inference endpoints through Model Management Service, providing a balanced
option for users to optimize for throughput and latency*
- 회사 내부에서 엔지니어가 아닌 분들도 쉽게 ML 모델을 학습시키고 deploy, 그리고 사용할 수 있게 만들어주는 ML Platform 서비스 개발 [시애틀 뉴스 링크](https://www.builtinseattle.com/2021/03/18/qualtrics-machine-learning-trends)
- 회사 팀 간 모델 쉐어 기능, 그리고 모델 버젼 기능이 있는 V2 버전 서비스 디자인함
- *Optimized and migrated the logging pipeline for various services in CoreML team to Splunk, separating latency from
gateway side, AWS side and application side*
- 내부 로깅 파이프라인을 Splunk 와 연동해서 사용 로그, 그리고 사용자 지표를 통해 인공지능 서비스를 보완 할 수 있는 피드백 수집
- *Automated CI/CD pipelines for ML services to follow standardized format in Jenkins, enabling automatic generation of
instance size/parameters per datacenter level*
- Jenkins 를 이용한 인공지능 서비스를 위한 CI/CD 파이프라인 구축, 기계학습 모델 학습/디플로이 자동화

## Morgan Stanley (모건스탠리)
### Technical Associate
- *Developed an NLP based Call Center AI agent that automatically answers financial and internal questions and reduced
call center volume by 30% using Gensim, PyTorch and Flask*
- 어려운 금융/사업 관련 질문들을 검색해주는 AI 서비스 개발
- 이 서비스 활용 이후 콜센터로 오는 전화량이 30% 감소
- *Prevented system outages for MSOnline, Morgan Stanley’s flagship application used by clients, by time-series analysis and log monitoring/extracting error terms from failure logs in Python*
- 로그 분석을 통해 서비스 장애 감지
- *Identified potential conflict of interests among financial advisors for internal risk team*
- 내부자 거래 예방을 위한 펀드매니저 간의 이해관계 충돌 분석
- *Detected potentially vulnerable clients as well as internal fraud risks by using k-means clustering and isolation forest*
- 금융사기에 취약한 고객층을 k-means clustering 과 isolation forest를 통해 분석
- *Supported firm wide usage of Dataiku, reconciling databases and simplifying data analysis pipeline of WM Tech*
- Dataiku 를 사용해 비 프로그래머 애널리스트들도 데이터 분석을 할 수 있게 도움
- *Organized data flow to reroute hardware access data for cybersecurity team to identify potential data breach*
- 사내 보안 유지를 위한 회사 내부 통신망 사용 데이터 분석

## Charles River Development
### Software Engineering Intern
- *Built automated regression testing framework in C# for post-trading team to test their end-of-day operations*
- C#로 금융거래 장부 정리와 장 마감시 처리되는 업무 테스팅을 자동화
- *Implemented functionality to support account conflict resolution and stock transactions of Excel Autointerpreter in C#*
- 계좌 업데이트와 주식거래 장부 업데이트를 위한 Excel parsing 
- *Provided consistent management of position data for Wells Fargo clients by improving existing UI Framework*
- Wells Fargo 은행 고객들을 위해 positions UI 개편

# Technical Skills
Languages: Python, Java, Javascript, SQL Frameworks: FastAPI, PyTorch, Flask, OpenCV, FastText, scikit-learn, gensim
AWS Services: Sagemaker, S3, IAM Policies, EC2 Databases / Big Data: PostgreSQL, Greenplum, Impala, Hive, Spark,
Hadoop

# 기타
한국어, 영어 - 네이티브
스페인어, 일본어, 중국어 - 중급
-> 텍스트 처리 프로세스 앎, annotation audit 한 적 있고 프로세스 짜본 적 있음