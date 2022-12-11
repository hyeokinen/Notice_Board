## Spring Boot 게시판 구현
-------
### 기술 스택

개발언어: JAVA<br>
프레임워크: Spring Boot<br>
IDE: IntelliJ<br>
Data: MariaDB<br>
DB Management: MySQL Workbench<br>
View Template: Thymeleaf (page를 담당해주는 역할) <br>
DB access: Java persistence API, JPA<br>


개발 순서
1. 개발 환경 세팅
2. 프로젝트 생성
3. 게시물 작성
4. 게시물 리스팅
5. 게시물 삭제
6. 게시물 수정
7. 게시물 리스트 페이징


----------
# 개발 진행

### 12/9 개발 사항
1. IntelliJ 설치
2. MaraiDB 설치
> homebrew를 통한 maraidb 설치 과정에서 (Error: Cannot install on Intel processor in ARM default prefix (/opt/homebrew)!) 에러가 발생하였고.<br>
> PATH 설정을 병경하여 해결하였다. 
> 
> export PATH=/usr/local/bin:$PATH<br>
> 
> mysql -uroot -p 로 maridb 접속
3. MySQL Workbench 설치
>DB를 콘솔창에서 관리하면 힘드므로 GUI환경에서 관리하기 위함


### 12/11 개발 사항
1. start.Spring.io 에서 프로젝트 생성

