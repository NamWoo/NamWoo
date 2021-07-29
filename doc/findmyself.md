# 일단 막 쓰기


우라늄 같은 !?


## 통계학습 - Statistical Learning

> 생체신호 계측기를 회로설계하고 제작해서 수집하고 정제해서 확률통계 모델 만들어서 유의미한 결과 만들어 내다가
* 의용전자공학 전공, 의료공학, 회로설계, 생체신호 분석, 시계열 분석, 의료전자시스템 개발
* 졸업논문, *심전도로 개인 식별하는 알고리즘 개발, Statistical learning, Clustering analysis, PCA, Matlab, C* 

|ECG 분석 , Pan–Tompkins algorithm|
|:---:|
|![qrs](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/SinusRhythmLabels.svg/330px-SinusRhythmLabels.svg.png)|
|![pan-tampkin](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/ECGrita.svg/1920px-ECGrita.svg.png)|


## 기계학습 - Machine Learning

> 수학적 분석인 통계분석에서 자연스럽게 컴퓨팅 파워를 이용한 머신러닝으로

* 주로 시계열 분석 느낌 살려서 
* 학습모델 만들고 코딩하고
* GCP 가져다 다화자 음성 분석 솔루션 등등등 만들어보고
* Kaggle 도 기웃거리다가


|데이터 분석 관련 스터디, 모임, 행사란 행사는 다 가보기|
|:---:|
|![facebook-image](https://scontent-gmp1-1.xx.fbcdn.net/v/t1.6435-9/57277729_2635009589905563_8564848319384256512_n.jpg?_nc_cat=104&ccb=1-3&_nc_sid=b9115d&_nc_ohc=VicPmX8OjhAAX805-2V&_nc_ht=scontent-gmp1-1.xx&oh=459ea82e16ecd30c713412f75baeb100&oe=6126C2FE)|

* 출처
* [kaggle-korea](https://www.facebook.com/groups/KaggleKoreaOpenGroup/permalink/403069190425186/)
* [databreak](https://github.com/KaggleBreak/databreak/tree/master/2019/meetup)


> ML은 정확도가 올라가는 것에 비례해서 이유는 모르겠고 모르는 것은 더 많아지니

* 관심가는 국내 연구소, 대학, 오프라인 강의 싹 들어보고
* 온라인 강의 Udacity, Cousera 좋다는거 다 들어보고
* 2015-2018, Data Scientist, HPC(High Performance Computing), Machine Learning, Certification, 자격-수료, 한 50개 강의 듣고 땄나? 
* 네이버 데이터사이언스 경진대회, 결선 33인 진출 (네이버 커넥트원 입소, 2019, 네이버)
* [자격증 정리--](https://github.com/NamWoo/NamWoo/blob/master/doc/certification.md)


## Embedded Machine Learning, Autonomous, Self-Driving-Car

> 더 깊은 영역에서의 나만의 전문 영역을 구축하고 싶어 Embedded Machine Learning 을!

* 2019, NVIDIA 플랫폼 기반 자율주행차 구현을 위한 SW개발 및 실무프로젝트 과정 with 한컴MDS (2기, 6개월 정부지원, 기업지원 교육과정)
* 물류자동화 협동로봇 - 모노카메라로 비쥬얼 오도메트리 자율주행 프로젝트 (1등, 2019, 한컴MDS, EXIS)
* 자율주행 모형자동차 경진대회(2등, 2019, 현대자동차, 현대모비스)

||
|:---:|
|![KNW09544 ARW](https://user-images.githubusercontent.com/8021479/127513168-a5d95e4a-c527-4fee-8a54-c2f6cc2e3731.jpg)|
|군집제어|
|![KNW00409 ARW](https://user-images.githubusercontent.com/8021479/127513160-d538adfb-875d-408f-982c-7d70ead3a645.jpg)|
|자율주행 모형차|



***그리고 지금은, 소프트웨어 엔지니어로, 지금까지 해온 일들을 섞어서 이것 저것 하고 있는 나***



# 지금 내가 할 수 있는 일

중구난방이니 가지치기 해놓기


<!--

### Engineer


||강S|약W|
|:---:|:---:|:---:|
|능력|||
|흥미|||

||강S|약W|
|:---:|:---:|:---:|
|env|아날로그 회로설계|펌웨어|
|code|다양한 언어|coder|
-->

#### 아날로그 회로설계

* 대학교 졸업전까지는 주로 임베디드 하드웨어, 제어부분이 강점
* 코딩 보다 전자시스템, 히트싱크(발열), 의료기기 같이 특수성에 맞춘 전자시스템 설계
* 통계 분석 - 생체 정보
  * ECG 심전도, EEG 뇌전도, EMG 근전도, 등등..
  * 생체 활동을 통해 나타나는 데이터를 활용한
    * 모션센서, IMU, 폰의 가속센서를 통해 나타나는 행동패턴 등..

그나마 가장 기억남. 미분기, 적분기, 컨볼루션....
* 계측신호 증폭하고 정하는 회로를 설계하고 구성하고 땜질해서 MCU로 보내주고
* OpAmp, DSP, STM32, ATmega, Circuit

또 생체 3D 모델링을 만들어서 생체하중, 인장력, 수치 동력학 분석
* ProE, Ansys로 모델 그려서 구조, 인장력 수치 뽑아낼 수 있고


### ML 

정리는 나중에..


> MCU에서 받은 이러한 신호들를 상위 linux OS 단으로 보내면, linux에서 모으고 정제하고 정리(Sensor Fusion)해서
* Linux System, Shell programming
> Edge에서 스스로 판단하고 정의하고
* 확률통계 분석, Machine Learning, Deep Learning, Camera Vision, TinyML, ROS, SLAM, Mapping, Navigation, Multi-Robot Task Allocation
> 최적화, 병렬, 
* TensorRT, CUDA
> 결과를 클라우드로 보내게 하고 Edge들의 컨테이너를 오케스트레이션 운영.
* Docker, Kubernetes, DeepOps, MLOps, (AWS, Azure, GCP)

### Data Scientist
> 비정제 신호, 정제 신호로 바꾸기 (다년간에 쌓인...삽ㅈ)
> 모델짜는건 .... (xgboot 유행할 때까지 기억나는...)

***뭐가 난 가장 자신있을까 봤더니 1)검색, 그리고 2)남이 해놓은거 잘 가져다 쓰는 스킬.. 좋은말로 문제해결능력, 다른 말로 삽질***



## 직무 & 직책 & 지금 하고 있는 key words

선행연구를 위한 선행연구를 위한 선행연구를 해야하는..(=개발잡부)

*pilot study (선행연구)*

* Embedded Vision Machine Learning Engineer
* IoT System Engineer
* Edge Computing System Engineer
* Embedded System Engineer
* Linux System Management
* DeepOps, MLOps
* Data Preprocessing & Cleansing
* [PTC IoT Engineer](https://cse.snu.ac.kr/sites/default/files/node--notice/PTC_Fast%20Facts.pdf)


## Languages

### Tongues  
* 주 사용 언어 - `한국어`
* 배워놓고(=돈발라놓고) 안 쓰는 언어 - `중국어`(고등학교 유학2년), `독일어`(B2)
* 사용하는데도 안 느는 언어 - `영어`

### 회로설계
* 아날로그 신호처리
  * 회로, 소자 구성해서 OpAmp로 입력신호 튀겨서 보드로 넘기기
* 시스템 전력, heat sink 처리
* OrCAD
* PADS

### Board
* 대학교 때 많이 다룬 보드 Atmega128
* 발만 담궈본 보드 STM32F*
* 집에서 가지고 노는 보드 Raspberry Pi
* 6개월 짜리 정규 교육받은 보드 nvidia jetson 
* 자율주행 과정으로 교육받은 보드 Infineon  

### CS
* 당장에 A부터 Z까지 상용화 가능한 언어 python, shell
* 요즘 주 사용 언어 python, ros, c, c++, bazel, shell
* 자꾸 개발 중 겹치는 언어 cython, Javascript
* 배워보고픈 언어 cython, Go, Javascript
* 잘하고픈 언어 python, C, shell

## Platform
* 가장 많이 하는 일 jetson board
* 주 사용 스크립트 vscode, vim
* 주 사용 플렛폼 ROS, gstreamer, PTC ThingWorx
* 가끔씩 쓰는 플렛폼 Bazel, redis, node.js, flask, django, Unity 3D
* 곧 해야하는 플렛폼 Nvidia Omniverse

## Working on
* 로봇쪽 - 임베디드 GPU 보드에서 machine Learning, sensors fusion, slam, vision (10~15 Watt)
* 분석쪽 - 확률, 통계 그리고 정제해서 넘겨주기

## Interested in
* Multi-Robot Task Allocation

## 2021년 3월 기준, 최근 끝낸 toy projects
* 코세라 강의, CUDA 강의
* 라즈베리파이로 자동화 시스템 (feat.하다만)
* 코틀린으로 안드로이드 앱, DB(AWS RDS), server(AWS EC2) (feat.흉내)




# 다음 목표

* ⚡ [캐글 마스터 달고파](https://www.kaggle.com/rankings)
* 💬 제발 영어... 중국어랑 독일어는..?
* 🌱 [대학원](https://omscs.gatech.edu/specialization-computational-perception-robotics)

