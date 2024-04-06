# 자기소개
안녕하세요, 저는 백엔드 개발자 한진욱입니다.   
자동화를 좋아하고, 문제를 해결하는 것을 좋아합니다.

# 경력

### 우아한형제들 (2020.01.01 ~ 2023.10.04)
- 광고시스템 유지 보수 및 광고 서버 개발


# 프로젝트
### 정률 쿠폰 적용 프로젝트(2023.9)
- 광고시스템에 정률 쿠폰 정보를 추가하는 작업을 했습니다.
- 광고시스템은 광고 rds와 광고노출 elasticsearch로 구분되어 있음
- 광고노출 elasticsearch에 쿠폰 데이터가 들어가는데, 정률 쿠폰 타입을 시스템에 녹이는 작업을 함.
- 기술 스택: elasticsearch 

### CPC 광고 반경 변경 프로젝트(2023.8)
- 광고시스템 CPC(Click Per Cost) 정보를 바꾸는 작업을 한다.
- CPC(Click Per Cost) 원장 데이터는 rds 데이터에 저장되어 있다.
- 노출 시스템이 rds 데이터를 임포팅하여, 저장되어 있는 CPC 반경에 따라 노출 반경을 조절한다.
- 구체적으로 다음 작업이 필요
  - 노출 반경 기본값을 바꾸는 배치 작성
    배치에서 노출 반경 기본값 수정 후 이벤트 발송
- 기술 스택: spring batch

### 배민1 신규 상품 시스템 적용(2022.3)

### 우리가게 NOW 프로젝트(2021.5)

기술 블로그에 작성되어 있습니다.
https://techblog.woowahan.com/8240/

# 스터디
###  java nio (2023.9 ~ 2023.12)
- java nio가 무엇인지 학습
- selector를 사용하여 채팅 서버를 만들며 실습

# 교육
### 우아한테크코스 (2019.5월 ~ 2019.12)

di framework 과제 (2019.10.29 ~ 11.11)
- [https://github.com/jinwookh/jwp-di/tree/step1](https://github.com/jinwookh/jwp-di/tree/step1)
- 특정 annotation이 붙은 객체를 bean으로 만듦
- bean을 만드는 과정에서 객체 간 의존성 확인
- di 개념 학습

웹 서버 과제 (2019.9.18 ~ 9.30)
- [https://github.com/jinwookh/jwp-was/tree/feat-step2](https://github.com/jinwookh/jwp-was/tree/feat-step2)
- request에 알맞는 response를 전달할 수 있도록 서버 구현
- 세션 및 로그인 기능 구현
- 쿠키, 세션, servlet 개념 학습

### 사회과학부, 컴퓨터공학 복수전공 (2012.2월 ~ 2020.2월 졸업예정)

운영체제 수업 (2017 2학기)
- [https://github.com/jinwookh/pintos](https://github.com/jinwookh/pintos)
- 운영체제 개념 실습
