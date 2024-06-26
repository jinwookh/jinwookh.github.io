# 자기소개
안녕하세요, 저는 백엔드 개발자 한진욱입니다.   
자동화를 좋아하고, 문제를 해결하는 것을 좋아합니다.

# 경력
### 우아한형제들 (2020.01.01 ~ 2023.10.04)
- 광고시스템 유지 보수 및 광고 서버 개발
- 팀 환경에 대한 기술블로그 글
  - [https://techblog.woowahan.com/2708/](https://techblog.woowahan.com/2708/) 

# 기술스택
aws, elasticsearch, spring web mvc, spring batch, mysql

# 프로젝트
### 정률 쿠폰 적용 프로젝트(2023.9)
- 광고시스템에 정률 쿠폰 정보를 추가하는 작업
- 광고시스템은 광고 rds와 광고노출 elasticsearch로 구분되어 있음
- 광고노출 elasticsearch에 쿠폰 데이터가 들어가는데, 정률 쿠폰 타입을 시스템에 녹이는 작업을 함.
- 기술 스택: elasticsearch 

### CPC 광고 반경 변경 프로젝트(2023.8)
- 광고시스템 CPC(Click Per Cost) 정보를 바꾸는 작업
- CPC(Click Per Cost) 원장 데이터는 rds 데이터에 저장되어 있음
- 노출 시스템이 rds 데이터를 임포팅하여, 저장되어 있는 CPC 반경에 따라 노출 반경을 조절
- 구체적으로 다음 작업이 필요
  - 노출 반경 기본값을 바꾸는 배치 작성
    배치에서 노출 반경 기본값 수정 후 이벤트 발송
- 기술 스택: spring batch

### 배민1 신규 상품 시스템 적용(2022.3)
- 광고시스템 rds와 광고노출 elasticsearch에 배민1 신규 상품을 적용
- 기술 스택: spring mvc, elasticsearch

### 우리가게 NOW 프로젝트(2021.5)
- 사장님 통계 api를 제공하는 프로젝트
- 사내 데이터 저장소 hive에서 sparksql로 데이터를 추출
- 추출한 데이터를 팀 내 rds에 저장
- 광고시스템 서버로 rds 데이터를 서빙
- 기술 블로그 작성
[https://techblog.woowahan.com/8240/](https://techblog.woowahan.com/8240/)

# 스터디
###  java nio (2023.9 ~ 2023.12)
- java nio가 무엇인지 학습
- selector를 사용하여 채팅 서버를 만들며 실습
- [https://github.com/jinwookh/java-network-study](https://github.com/jinwookh/java-network-study)

# 교육
### 우아한테크코스 (2019.5월 ~ 2019.12)
### 사회과학부, 컴퓨터공학 복수전공 (2012.2월 ~ 2020.2월 졸업예정)
운영체제 수업 (2017 2학기)
- [https://github.com/jinwookh/pintos](https://github.com/jinwookh/pintos)
- 운영체제 개념 실습
