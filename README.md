목차
이 책을 내며...
코드로 배우는 스프링 웹 프로젝트 v2.0

Part 1 스프링 개발 환경 구축
1장 개발을 위한 준비
1.1 개발환경 설정
1.2 스프링 프로젝트 생성
1.3 Tomcat을 이용한 프로젝트 실행 확인
1.4 Lombok 라이브러리 설치
1.5 Java Configuration을 하는 경우
2장 스프링의 특징과 의존성 주입
2.1 스프링 프레임워크의 간략한 역사
2.2 의존성 주입 테스트
2.3 스프링이 동작하면서 생기는 일
2.4 스프링 4.3 이후 단일 생성자의 묵시적 자동주입
3장 스프링과 Oracle Database 연동
3.1 오라클 설치
3.2 SQL Developer 설치
3.3 프로젝트의 JDBC 연결
3.4 커넥션 풀 설정
4장 MyBatis와 스프링 연동
4.1 MyBatis
4.2 스프링과의 연동 처리
4.3 log4jdbc-log4j2 설정

Part 2 스프링 MVC 설정
5장 스프링 MVC의 기본 구조
5.1 스프링 MVC 프로젝트의 내부 구조
5.2 예제 프로젝트의 로딩 구조
5.3 스프링 MVC의 기본 사상
5.4 모델2와 스프링 MVC
6장 스프링 MVC의 Controller
6.1 @Controller, @RequestMapping
6.2 @RequestMapping의 변화
6.3 Controller의 파라미터 수집
6.4 Model이라는 데이터 전달자
6.5 Controller의 리턴 타입
6.6 Controller의 Exception 처리

Part 3 기본적인 웹 게시물 관리
7장 스프링 MVC 프로젝트의 기본 구성
7.1 각 영역의 Naming Convention(명명규칙)
7.2 프로젝트를 위한 요구 사항
7.3 예제 프로젝트 구성
7.4 데이터베이스 관련 설정 및 테스트
7.5 Java 설정을 이용하는 경우의 프로젝트 구성
8장 영속/비즈니스 계층의 CRUD 구현
8.1 영속 계층의 구현 준비
8.2 영속 영역의 CRUD 구현
9장 비즈니스 계층
9.1 비지니스 계층의 설정
9.2 비즈니스 계층의 구현과 테스트
10장 프레젠테이션(웹) 계층의 CRUD 구현
10.1 Controller의 작성
10.2 BoardController의 작성
11장 화면 처리
11.1 목록 페이지 작업과 includes
11.2 목록 화면 처리
11.3 등록 입력 페이지와 등록 처리
11.4 조회 페이지와 이동
11.5 게시물의 수정/삭제 처리
12장 오라클 데이터베이스 페이징 처리
12.1 order by의 문제
12.2 order by 보다는 인덱스
12.3 인덱스를 이용하는 정렬
12.4 ROWNUM과 인라인뷰
13장 MyBatis와 스프링에서 페이징 처리
13.1 MyBatis 처리와 테스트
13.2 BoardController와 BoardService 수정
14장 페이징 화면 처리
14.1 페이징 처리할 때 필요한 정보들
14.2 페이징 처리를 위한 클래스 설계
14.3 JSP에서 페이지 번호 출력
14.4 조회 페이지로 이동
14.5 수정과 삭제 처리
14.6 MyBatis에서 전체 데이터의 개수 처리
15장 검색 처리
15.1 검색 기능과 SQL
15.2 MyBatis의 동적 SQL
15.3 검색 조건 처리를 위한 Criteria의 변화
15.4 화면에서 검색 조건 처리

Part 4 REST 방식과 Ajax를 이용하는 댓글 처리
16장 REST 방식으로 전환
16.1 @RestController
16.2 @RestController의 반환 타입
16.3 @RestController에서 파라미터
16.4 REST 전송 방식
16.5 다양한 전송 방식
17장 Ajax 댓글 처리
17.1 프로젝트의 구성
17.2 댓글 처리를 위한 영속 영역
17.3 서비스 영역과 Controller 처리
17.4 JavaScript 준비
17.5 이벤트 처리와 HTML 처리
17.6 댓글의 페이징 처리
17.7 댓글 페이지의 화면 처리

Part 5 AOP와 트랜잭션
18장 AOP라는 패러다임
18.1 AOP 용어들
18.2 AOP 실습
18.3 AOP 설정
18.4 AOP 테스트
18.5 @Around와 ProceedingJoinPoint
19장 스프링에서 트랜잭션 관리
19.1 데이터베이스 설계와 트랜잭션
19.2 트랜잭션 설정 실습
20장 댓글과 댓글 수에 대한 처리
20.1 프로젝트수정

Part 6 파일 업로드 처리
21장 파일 업로드 방식
21.1 스프링의 첨부파일을 위한 설정
21.2 〈form〉 방식의 파일 업로드
21.3 Ajax를 이용하는 파일 업로드
22장 파일 업로드 상세 처리
22.1 파일의 확장자나 크기의 사전 처리
22.2 섬네일 이미지 생성
22.3 업로드된 파일의 데이터 반환
23장 브라우저에서 섬네일 처리
23.1 〈input type='file'〉의 초기화
23.2 업로드된 이미지 처리
24장 첨부파일의 다운로드 혹은 원본 보여주기
24.1 첨부파일의 다운로드
24.2 원본 이미지 보여주기
24.3 첨부파일 삭제
25장 프로젝트의 첨부파일 - 등록
25.1 첨부파일 정보를 위한 준비
25.2 등록을 위한 화면 처리
25.3 BoardController, BoardService의 처리
26장 게시물의 조회와 첨부파일
26.1 BoardService와 BoardController 수정
26.2 BoardController의 변경과 화면 처리
27장 게시물의 삭제와 첨부파일
27.1 첨부파일 삭제 처리
28장 게시물의 수정과 첨부파일
28.1 화면에서 첨부파일 수정
28.2 서버측 게시물 수정과 첨부파일
29장 잘못 업로드된 파일 삭제
29.1 잘못 업로드된 파일의 정리
29.2 Quartz 라이브러리 설정
29.3 BoardAttachMapper 수정
29.4 cron 설정과 삭제 처리

Part 7 Spring Web Security를 이용한 로그인 처리
30장 Spring Web Security 소개
30.1 Spring Web Security의 설정
30.2 시큐리티가 필요한 URI 설계
30.3 인증(Authentication)과 권한부여(Authorization -인가)
31장 로그인과 로그아웃 처리
31.1 접근 제한 설정
31.2 단순 로그인 처리
31.3 커스텀 로그인 페이지
31.4 CSRF(Cross-site request forgery) 공격과 토큰
31.5 로그인 성공과 AuthenticationSuccessHandler
31.6 로그아웃의 처리와 LogoutSuccessHandler
32장 JDBC를 이용하는 간편 인증/권한 처리
32.1 JDBC를 이용하기 위한 테이블 설정
32.2 기존의 테이블을 이용하는 경우
33장 커스텀 UserDetailsService 활용
33.1 회원 도메인, 회원 Mapper 설계
33.2 CustomUserDetailsService 구성
34장 스프링 시큐리티를 JSP에서 사용하기
34.1 JSP에서 로그인한 사용자 정보 보여주기
34.2 표현식을 이용하는 동적 화면 구성
35장 자동 로그인(remember-me)
35.1 데이터베이스를 이용하는 자동 로그인
36장 Java 설정을 이용하는 경우의 스프링 시큐리티 설정
36.1 Java 설정 추가 및 동작 확인
36.2 로그인 페이지 관련 설정
36.3 로그아웃 처리
36.4 PasswordEncoder 지정
36.5 JDBC를 이용하는 Java 설정
36.6 커스텀 UserDetailsService 설정
36.7 자동 로그인 설정(remember-me)
37장 어노테이션을 이용하는 스프링 시큐리티 설정
38장 기존 프로젝트에 스프링 시큐리티 접목하기
38.1 로그인 페이지 처리
38.2 게시물 작성 시 스프링 시큐리티 처리
38.3 게시물 조회와 로그인 처리
38.4 게시물의 수정/삭제
38.5 Ajax와 스프링 시큐리티 처리
39장 로그아웃 처리
39.1 로그아웃 페이지
39.2 로그인 후 '/board/list'로 이동하기

부록
A Intellij와 Gradle을 이용하는 스프링 환경
A.1 Intellij 버전과 다운로드
A.2 Gradle 설치
A.3 프로젝트 생성
A.4 스프링 프레임워크 추가
A.5 Lombok 플러그인 추가
A.6 Lombok 컴파일 환경
A.7 Log4j 추가
A.8 Tomcat 설정
A.9 스프링 MVC 추가와 XML 파일 생성
A.10 web.xml 생성과 실행 테스트
