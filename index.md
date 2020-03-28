# 자기소개

안녕하세요, 저는 현재 서버 개발을 하고 있습니다.

`기능의 변경에 유연한 코드`를 만들고 싶습니다.

현재 어떤 테스트가 `좋은 테스트`인가에 대해 관심이 많습니다.

# 경력

### 우아한형제들 (2020.1.1 ~ )
- 상품시스템팀에서 근무
- 상품 데이터를 제공하는 api 유지 및 보수
- 상품 데이터를 보정하는 batch 개발

# 프로젝트

### 인스타그램 프로젝트 (2019.8.1 ~ 8.31)

- [https://github.com/wooteco-datastructure/miniprojects-2019](https://github.com/wooteco-datastructure/miniprojects-2019)
- 인스타그램을 만드는 프로젝트
- 기술 스택: spring, jpa, java, mysql
- 맡은 역할
    1. user profile image 관련된 기능 구현
        - user profile image를 저장하는 기능 구현
        - user profile image를 클라이언트로 보내는 기능 구현
        - 기능을 구현하면서 만난 문제:
            - user profile image 테이블과 article image 테이블로 나눌 이유가 있을까?
            - user profile image table과 article image table을 합치는 과정 수행
    2. 빌드 및 테스트 자동화
        - 기존에는 빌드 및 테스트를 수동으로 수행
        - 개발자가 깜빡하여 빌드 및 테스트 하지 않은 채 pull request를 날리는 문제 발생
        - jenkins를 사용해 빌드 및 테스트를 자동화
        - 문제 해결
    3. 무한 스크롤링 구현
        - 메인 페이지에서 무한 스크롤링을 통해 게시글들을 보여주고자 함
        - 무한 스크롤링을 위해 데이터를 가져오는 방식을 바꿈
        - jpa의 page 사용하여 가져오는 방식 사용

# 교육

### 우아한테크코스 (2019.5월 ~ 현재)

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

# 오픈소스
### spring batch
- 주석을 고침
- https://github.com/spring-projects/spring-batch/pull/3679
