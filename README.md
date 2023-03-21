# FastCampus 10개 프로젝트로 완성하는 백엔드 웹개발(Java/Spring) 초격차 패키지 Online
## Part1. 나만의 MVC 프레임워크 만들기
### Ch04. CGI 프로그램과 서블
#### 2. 계산기 서블릿 만들기
- servlet interface : servlet 생명주기와 관련된 메소드 및 기타 메소드 모두 구현해야 함
- GenericServlet abstract class : 생명주기와 관련된 init()과 destory() 메서드와 ServletConfig를 제공하기 때문에 service() 메서드만 구현하면 됨
- HttpServlet : 필요한 method를 찾아서 구현 (ex. doGet, doPost등)

<img width="402" alt="image" src="https://user-images.githubusercontent.com/106790381/226497165-d58ab1c7-c466-448f-83da-66cb4e663d0b.png">
