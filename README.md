# DevOps
# 뉴비를 위한 JAVA 개발환경 부터 배포까지 
 - 부제 : 백앤드 개발 

: 옛날부터 상상만 하던 일을 이제 실행에 옮겨보려고 합니다. 
하고 싶은 일은 제목 그대로 JAVA 개발자에게 
운영 레벨 수준의  "개발 -> 테스트 ->  배포"  단계까지 
방법 및 툴 사용 가이드 문서를 만들어서 널리 알리는 일입니다.  
 (너무 범위가 넓은거 같아서... 벌써부터 까마득하기만 합니다. ㅠㅠ  , 이번생에 마칠수 있겠죠? 도와주세요~~ .) 

 진행 방식은 일주일이 1번 정도 모여서 
단계마다 JAVA 개발 관련으로 현재 사용하고 있거나 좋다고 생각되는 tool 혹은 프로세스에 대해 
실습을 통해 공유하고 github 같은 모두가 볼 수 있는 곳에 문서로 남기는 방식을 고려하고 있습니다.  
(문서는 글을 최소화하고 최대한 스크린샷 위주의 따라하기 식의 방식을 취하려고 합니다) 

현재 생각중인 흐름은 다음과 같습니다. 

개요 : Rest-API 제공하는 Spring-boot 로 작성된 어플리케이션 제작과정에 필요한 A~Z까지 

* 개발 단계 
 - 개발도구 : 
    - [설치 방법 : JDK , 환경변수 , 인코딩 설정](https://cubenuri.tistory.com/133)
    - [유용한 플러그인](https://cubenuri.tistory.com/134)
      - exerd
      - CheckStyle
      - spotbugs
      - pmd
      - mybatipse 
      - Lombok
                     
 - 협업도구 : 
   - [Gitlab](https://cubenuri.tistory.com/265) : git , 이슈, 디플로이  
   - [Nexus](https://cubenuri.tistory.com/281) : 공용 아키타입, 라이브러리 , Docker Registry          
   - [RedMine](https://cubenuri.tistory.com/349) : 이슈 트래킹 시스, gitlab , Mylyn 연동
   - Gerrit : 코드 리뷰 시스템 
    
 -  개발 :
    - [Spring 프로젝트 생성방법](https://cubenuri.tistory.com/257)
    - JUnit , Mockito 작성 방법
    - Code Coverage 활용


* 테스트 단계
   - 통합 테스트 : Selenium 활용
   - 성능 테스트 : Stress 툴 활용 
    
- 배포 단계 
   - [gitlab-ci : Docker : Docker Hub 연동 & 배포](https://cubenuri.tistory.com/340)
   - Kubernetes 활용 : 배포 전략 
   - 로깅 & 모니터링 도구 : 미정
