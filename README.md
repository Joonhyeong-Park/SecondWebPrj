# SecondWebPrj
서강대 멋쟁이사자처럼 알럼나이 페이지였던것... 리크루팅 이후 내림, 첫 클래스뷰 구현

![113018622-b1a19280-91bb-11eb-85bf-ac638aca0df0](https://user-images.githubusercontent.com/55684184/139702463-d3f240cb-98dc-4d1a-827c-740c608fa8b9.png)




# **서비스 개요**
 - 개발기간 : 2021.02 ~ 2021.03(배포)
 - 기술스택 : Front(HTML,CSS,JavaScript), Back(Django, AWS RDS)
 
# **서비스 기능**
 - 소셜 회원가입/로그인 기능 + 추가정보 커스터마이징
 - 한참 유행했던 심리테스트 비슷한 BFtest(백 프론트 테스트) 기능
 - 면접 진행 시간 선택 및 결과 확인 기능(구현하다가 중단)
 - 멋쟁이 사자처럼 9기 모집일정, 커리큘럼 정보 제공
 - 멋쟁이 사자처럼 8기(9기 운영진) 정보 제공
 
# **구현 내용**
 - BaseUserManager, AbstractBaseUser 상속을 통한 커스터마이징 User 모델 사용
 - AWS RDS를 사용한 PSQL 데이터베이스 생성 및 연결
 - AWS EC2 
