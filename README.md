# INFREAN

<p align="center">  Infrean 김영한 스프링 입문 강의 </p>

스프링 프로젝트 준비

1.h2 데이터베이스 1.4.200 버전 다운로로드
2.자바 11 설치
3.Intellij 설치
4.https://start.spring.io/ (스프링부트)

스프링 웹 개발 기초

- 프로젝트생성

프로젝트 환경 설정을 위해 Intellij 에서 build.gradle을 열어준 뒤 설치가 완료 되면
src - main - java -hello.hellospring - HelloSpringApplication 으로 들어간 뒤
(예외로 Compact Middle Packages 선택이 안 된 경우 폴더 경로가 다르게 나올 수 있음)
```
public static void main(String[] args) {
   SpringApplication.run(HelloSpringApplication.class, args);
}
```
메인메소드를 실행시켜 프로젝트 환경 설치가 완료 됐는지 확인

- 라이브러리 살펴보기
