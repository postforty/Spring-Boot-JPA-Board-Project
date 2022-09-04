## Spring Boot 웹 프로젝트 - JPA 게시판

+ 기술 스택
  + Framework: Spring Boot
    + Type: Gradle
    + Packaging: War(Web application Archive)
    + Java Version: 8
    + Language: Java
    + Dependencies
      + DevTools
      + MySQL
      + ***JPA***
      + Thymeleaf
      + Web
      + Lombok
      + Logback
  + DB: MySQL 
  
+ 개발 내용
  + 게시글 목록 조회
  + 게시글 등록
  + 게시글 상세 화면
  + 게시글 수정
  + 게시글 삭제
  + 파일 첨부 및 다운로드
  
+ 성과
  + ***스프링 데이터 JPA 적용 데이터베이스 연동***
  + Jsr310JpaConverters 적용 Java 8의 날짜 API 설정(Java 8의 날짜와 시간 관련 클래스를 그대로 사용할 경우 MySQL의 버전에 따라서 문제가 발생할 수 있음)
  + CrudRepository 인터페이스 상속한 CRUD 
  + Query Methods와 @Query의 용법
  
+ 참고 자료
  + 김인우. (2019). 스프링 부트 시작하기. 프로그래밍인사이트
