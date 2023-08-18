# FrontEnd-Roadmap
My FrontEnd Roadmap

* * *

이미지 출처: <https://github.com/Han-Kyeol/developer-roadmap-kr->  
위 출처는 kamranahmedse의 developer-roadmap(https://github.com/kamranahmedse/developer-roadmap) 을 한국어로 번역한 저장소 입니다.

* * *  



# 0. 개요
![IntroImage](intro(kr).png "IntroImage")

* * *

# 1. FrontEnd
![FrontEndImage](frontend(kr).png "FrontEndImage")


## FrontEnd란? 
프론트엔드는 웹 개발의 중요한 부분이다. 사용자들이 웹 사이트나 앱과 상호작용하는 인터페이스를 개발하는 역할을 한다. 이는 웹 페이지에서 보이는 모든 시각적인 측면을 다루며, 레이아웃, 디자인, 기능 등을 포함한다.

프론트엔드 개발자가 하는 주된 업무는 다음과 같다:

- 웹 디자인: 웹 페이지의 디자인을 결정하고 사용자가 편하게 볼 수 있는 레이아웃을 구성한다. 색상, 폰트, 그래픽 디자인 등을 선택하여 웹 페이지의 시각적인 매력을 증진시킨다.
사용자 인터페이스(UI) 개발: 버튼, 입력 폼, 메뉴 등 사용자가 웹 페이지에서 상호작용할 수 있는 요소를 개발한다. 이를 통해 사용자들이 원하는 작업을 쉽게 수행할 수 있도록 도와준다.
- 반응형 웹 디자인: 다양한 디바이스와 화면 크기에서 웹 페이지가 잘 표시되도록 반응형 웹 디자인을 구현한다. 스마트폰, 태블릿, 데스크톱 등 다양한 환경에서도 웹 페이지가 적절하게 보이도록 조정한다.
- 웹 접근성: 장애가 있는 사용자들도 웹 페이지를 쉽게 이용할 수 있도록 웹 접근성을 고려하여 디자인과 개발을 한다. 스크린 리더 사용자 등 모든 사용자가 웹 페이지를 활용할 수 있어야 한다.
- 클라이언트 사이드 프로그래밍: 자바스크립트 등의 언어를 사용하여 웹 페이지 내에서 동적인 기능을 구현한다. 사용자의 상호작용에 따라 웹 페이지가 동적으로 변화하는 기능을 개발한다.
- 웹 성능 최적화: 웹 페이지의 로딩 속도와 성능을 개선하고 최적화하는 작업을 수행한다. 빠른 웹 페이지 로딩을 통해 사용자 경험을 향상시킨다.
- 웹 애니메이션: CSS나 자바스크립트를 활용하여 웹 페이지에 동적인 애니메이션 효과를 추가한다. 이로써 웹 페이지가 더 생동감있고 흥미로워진다.
- 웹 브라우저 호환성: 다양한 웹 브라우저에서 웹 페이지가 정상적으로 동작하도록 확인하고, 브라우저 호환성을 유지한다.
프론트엔드 개발자의 역할은 사용자들이 웹 페이지를 쉽게 이용하고 즐길 수 있도록 돕는 것이다. 모든 사용자가 웹 페이지를 이용할 때 무리 없이 사용할 수 있도록 디자인과 개발을 수행한다.


## 1.1. HTML이란? 
HTML(하이퍼텍스트 마크업 언어)은 웹 페이지의 구조와 내용을 정의하는 언어로, 웹 개발에서 중요한 역할을 한다. 웹 페이지의 텍스트, 이미지, 링크, 테이블 등을 구성하고 배치하는 데 사용된다. HTML은 웹 브라우저에게 어떻게 콘텐츠를 표시해야 하는지 알려주는 역할을 하며, 웹 페이지의 기본적인 뼈대를 형성한다.

HTML의 주요 특징은 다음과 같다:

```
- 마크업: HTML은 마크업 언어로, 일반 텍스트에 태그를 추가하여 문서의 구조와 의미를 나타낸다. 예를 들어, <h1> 태그는 제목을 나타내며, <p> 태그는 단락을 나타낸다.  
- 요소(Element): HTML 문서는 요소로 구성되며, 시작 태그(<tag>)와 종료 태그(</tag>)로 이루어진다. 요소는 컨텐츠를 감싸며, 이 컨텐츠는 웹 페이지에 표시된다.  
- 구조화: HTML을 사용하여 웹 페이지를 구조화할 수 있다. 헤더, 본문, 사이드바, 푸터 등과 같은 구획을 정의하고 배치할 수 있다.  
- 하이퍼링크: <a> 태그를 사용하여 다른 웹 페이지나 파일로 연결하는 하이퍼링크를 만들 수 있다. 이는 사용자가 클릭하여 다른 페이지로 이동하거나 파일을 다운로드할 수 있게 해준다.  
- 이미지: <img> 태그를 사용하여 이미지를 웹 페이지에 삽입할 수 있다. 이미지의 경로와 크기 등을 지정할 수 있다.  
- 목록: <ul>, <ol>, <li> 태그를 사용하여 순서 없는 목록과 순서 있는 목록을 생성할 수 있다.  
- 테이블: <table>, <tr>, <td> 등의 태그를 사용하여 표를 생성할 수 있다.  
- 양식(Form): <form> 태그를 사용하여 사용자 입력을 받는 양식을 만들 수 있다. 텍스트 입력, 라디오 버튼, 체크 박스 등의 양식 요소를 사용할 수 있다.  
- 멀티미디어: 오디오나 비디오 재생을 위한 태그들도 포함되어 있다.
```

HTML은 웹 페이지의 구조를 설계하고 기본 콘텐츠를 배치하는 기본적인 도구로, 웹 개발의 핵심 요소 중 하나이다.  



## 1.2. CSS란?
CSS(Cascading Style Sheets)는 웹 페이지의 디자인과 레이아웃을 꾸미는 언어로, HTML로 작성된 콘텐츠의 스타일을 정의하는 역할을 한다. HTML이 웹 페이지의 구조와 내용을 담당한다면, CSS는 이 콘텐츠를 어떻게 보여줄지를 제어한다. CSS를 사용하면 웹 페이지의 색상, 폰트, 간격, 배치 등을 조작하여 웹 페이지를 시각적으로 매력적으로 만들 수 있다.

CSS의 주요 특징은 다음과 같다:

```
스타일 적용: CSS는 HTML 요소의 스타일을 변경하는 데 사용된다. 이를 통해 글꼴, 색상, 배경, 여백 등을 조정하여 웹 페이지의 디자인을 제어할 수 있다.  
분리된 스타일: CSS는 HTML 문서와 별도로 작성되며, 분리된 스타일 시트 파일에 저장된다. 이로 인해 디자인 변경 시 HTML 파일을 건드리지 않고도 디자인을 수정할 수 있다.  
계단식 스타일(Cascading): "Cascading"이란 단어에서 유래한 것처럼, CSS는 여러 스타일 규칙을 적용하는 방식이다. 요소에 여러 개의 스타일이 적용되면, 우선순위에 따라 결정된다.  
클래스와 아이디: CSS는 클래스(class)와 아이디(id)를 통해 특정 요소에 스타일을 적용할 수 있다. 이를 통해 원하는 요소에 원하는 스타일을 선택적으로 적용할 수 있다.
상속: CSS로 적용한 스타일은 기본적으로 하위 요소로 상속된다. 예를 들어, 상위 요소에 글꼴 스타일을 지정하면 하위 요소에도 적용된다.  
미디어 쿼리: CSS는 미디어 쿼리를 사용하여 다양한 화면 크기나 장치에 따라 스타일을 다르게 적용할 수 있다. 이를 통해 반응형 디자인을 구현할 수 있다.  
```

CSS는 웹 페이지의 시각적인 부분을 다루는 중요한 언어로, 사용자 경험을 개선하고 웹 사이트를 더 흥미롭게 만드는 데에 큰 역할을 한다. HTML과 함께 사용되어 웹 개발자들이 웹 페이지를 디자인하고 개발하는데 필수적인 요소다.  



## 1.3. JavaScript란?
자바스크립트(JavaScript)는 웹 개발에서 사용되는 프로그래밍 언어로, 웹 페이지를 동적으로 만들고 상호작용할 수 있게 해준다. HTML과 CSS와 함께 웹 개발의 핵심 요소 중 하나이며, 사용자와 웹 페이지 간의 상호작용을 처리하고 다양한 기능을 추가하는 데 사용된다.
 

자바스크립트의 주요 특징은 다음과 같다:

- 클라이언트 사이드 스크립트: 자바스크립트는 웹 브라우저에서 실행되는 클라이언트 사이드 스크립트 언어이다. 웹 페이지를 불러온 사용자의 브라우저에서 실행되며, 서버와의 통신 없이도 사용자 경험을 개선할 수 있다.

- 동적인 기능 추가: 자바스크립트를 사용하여 웹 페이지에 동적인 기능을 추가할 수 있다. 예를 들어, 사용자가 버튼을 클릭하면 내용이 바뀌거나 팝업 창이 나타나는 등의 효과를 만들 수 있다.

- 이벤트 기반 프로그래밍: 자바스크립트는 이벤트 기반 프로그래밍을 지원한다. 사용자의 동작(클릭, 마우스 오버 등)에 반응하여 특정 동작을 수행하도록 코드를 작성할 수 있다.

- DOM 조작: 자바스크립트를 사용하여 문서 객체 모델(DOM)을 조작할 수 있다. 이를 통해 웹 페이지의 요소들을 동적으로 변경하거나 추가할 수 있다.

- API 활용: 자바스크립트는 다양한 웹 브라우저 API와 상호작용하여 웹 페이지의 기능을 확장할 수 있다. 예를 들어, 브라우저의 위치 정보를 얻거나, 외부 서비스의 데이터를 가져와 표시할 수 있다.

- 라이브러리와 프레임워크: 다양한 자바스크립트 라이브러리와 프레임워크가 존재하여 개발을 용이하게 해준다. jQuery, React, Angular, Vue 등은 웹 개발에 많이 활용되는 라이브러리와 프레임워크다.

- 데이터 처리: 자바스크립트를 사용하여 데이터를 처리하고 조작할 수 있다. 사용자 입력을 수집하거나 서버와의 통신을 통해 데이터를 업데이트할 수 있다.

자바스크립트는 웹 개발에서 매우 중요한 역할을 하며, 웹 페이지의 동적인 기능과 상호작용을 구현하기 위한 필수 도구이다. 브라우저 뿐만 아니라 서버 사이드에서도 사용되는 Node.js라는 플랫폼도 존재하여, 다양한 분야에서 활용된다.



### Java와 JavaScript의 차이점
자바스크립트(JavaScript)와 자바(Java)는 이름이 비슷하지만, 서로 다른 언어로서 목적과 특징이 크게 다르다. 아래는 둘의 주요 차이점을 설명한 것이다:  

용도와 환경:  
- 자바: 자바는 범용 프로그래밍 언어로, 주로 서버 사이드 개발, 안드로이드 앱 개발, 대규모 응용 프로그램 등 다양한 분야에서 사용된다.
- 자바스크립트: 자바스크립트는 클라이언트 사이드 웹 개발을 위해 설계된 스크립트 언어로, 주로 웹 페이지의 동적인 기능을 구현하거나 상호작용을 추가하는 데 사용된다.

프로그래밍 패러다임:  
- 자바: 자바는 객체 지향 프로그래밍을 강조하는 언어이다. 클래스와 객체 개념을 중심으로 설계되었으며, 다양한 객체 지향 개념을 활용하여 프로그램을 작성한다.
- 자바스크립트: 자바스크립트는 객체 기반 스크립트 언어로, 프로토타입 기반의 객체 지향 프로그래밍을 지원한다.


실행 환경:  
- 자바: 자바는 자바 가상 머신(JVM) 위에서 실행되며, 컴파일 과정을 거친 후 바이트 코드로 실행된다.
- 자바스크립트: 자바스크립트는 웹 브라우저에서 클라이언트 사이드로 실행되며, 웹 페이지의 HTML과 함께 포함되어 실행된다.

언어 특징:  
- 자바: 자바는 정적 타입 언어로, 변수의 데이터 타입을 선언하고 컴파일 시에 타입 검사가 이루어진다. 큰 규모의 프로젝트에서 안정성과 유지보수 측면에서 이점을 가진다.
- 자바스크립트: 자바스크립트는 동적 타입 언어로, 변수의 타입을 선언하지 않고 실행 시에 동적으로 결정된다. 유연한 프로그래밍을 가능하게 하지만, 때로는 버그가 발생할 수 있다.

프레임워크와 라이브러리:  
- 자바: 자바에는 다양한 프레임워크와 라이브러리가 존재한다. 예를 들어, Spring Framework는 자바로 웹 어플리케이션을 개발하는 데 사용되는 대표적인 프레임워크이다.
- 자바스크립트: 자바스크립트에도 많은 라이브러리와 프레임워크가 존재한다. jQuery, React, Angular, Vue 등은 웹 프론트엔드 개발을 위해 널리 사용되는 라이브러리 및 프레임워크이다.  

요약하자면, 자바스크립트와 자바는 이름과 일부 문법이 비슷하지만, 목적, 사용 환경, 특징, 프로그래밍 패러다임 등에서 큰 차이를 가지고 있다.



## 1.4. React란?
리액트(React)는 Facebook에서 개발한 사용자 인터페이스(UI) 라이브러리로, 웹 및 모바일 애플리케이션의 사용자 인터페이스를 구축하기 위해 사용되는 오픈 소스 라이브러리이다. 리액트는 단일 페이지 애플리케이션(SPA)이나 웹 애플리케이션의 일부분을 구성하는 데 주로 사용되며, 컴포넌트 기반 아키텍처를 기반으로 하고 있다.

리액트의 주요 특징과 장점은 다음과 같다:

- 가상 DOM(Virtual DOM): 리액트는 가상 DOM을 사용하여 실제 DOM과 비교하여 변화된 부분만 업데이트하는 방식을 채택한다. 이로써 성능을 향상시키고 빠른 UI 업데이트를 가능하게 한다.

- 컴포넌트 기반 아키텍처: 리액트는 UI를 재사용 가능한 작은 컴포넌트로 분리하여 개발하는 방식을 지원한다. 이를 통해 코드의 가독성을 높이고 유지보수를 용이하게 한다.

- 단방향 데이터 흐름: 리액트는 데이터의 흐름을 단방향으로 유지하는 방식을 지향한다. 이로써 애플리케이션의 상태 변화가 예측 가능하며 디버깅이 용이해진다.

- 재사용 가능한 컴포넌트: 컴포넌트 기반 아키텍처로 인해 재사용 가능한 UI 요소들을 개발하고 조합할 수 있다.

- JSX 문법: JSX는 자바스크립트의 확장 문법으로, UI 컴포넌트를 선언적으로 작성할 수 있게 해준다.

- 리액트 생태계: 리액트는 확장 가능한 생태계를 가지고 있어 다양한 라이브러리와 프레임워크와의 통합이 용이하다. Redux, GraphQL, Next.js 등과 함께 사용하여 웹 애플리케이션을 더 발전시킬 수 있다.

- 커뮤니티와 지원: 리액트는 널리 사용되며 큰 개발 커뮤니티와 풍부한 문서 및 튜토리얼을 제공한다.

리액트는 주로 웹 프론트엔드 개발에서 사용되며, 사용자 인터페이스를 구축하는 데 탁월한 도구로 평가받고 있다. 하지만 리액트 자체는 라이브러리이므로, 상태 관리와 라우팅 등의 추가 기능은 다른 라이브러리나 프레임워크와 함께 사용되어 완전한 애플리케이션을 개발할 수 있다.



## 1.5. Node.js란?
Node.js는 서버 사이드에서 JavaScript를 실행할 수 있는 오픈 소스 런타임 환경이다. 기본적으로는 브라우저에서 클라이언트 사이드에서 실행되는 JavaScript를 서버 사이드에서 실행할 수 있도록 하는 환경을 제공한다. Node.js는 이벤트 기반, 비동기식 프로그래밍 모델을 사용하여 빠르고 확장 가능한 네트워크 애플리케이션을 개발하는 데 적합한 플랫폼이다.

Node.js의 주요 특징과 장점은 다음과 같다:  

- 비동기식 프로그래밍: Node.js는 비동기식 이벤트 루프를 기반으로 동작한다. 이로써 입출력(IO) 작업 등의 블로킹이 발생하는 작업을 효율적으로 처리할 수 있으며, 여러 작업을 동시에 처리할 수 있다.

- 단일 스레드: Node.js는 단일 스레드 모델을 사용하지만, 비동기식 모델을 통해 여러 작업을 동시에 처리할 수 있다. 이로써 확장성을 높이면서도 시스템 리소스를 효율적으로 사용할 수 있다.

- 넌블로킹 I/O: 블로킹되는 I/O 작업 없이도 동시에 다른 작업을 처리할 수 있으므로 네트워크 애플리케이션과 데이터베이스 작업 등에 적합하다.

- 큰 커뮤니티와 패키지 생태계: Node.js는 큰 개발 커뮤니티와 다양한 패키지와 모듈을 포함한 생태계를 가지고 있다. npm(Node Package Manager)을 통해 패키지를 관리하고 공유할 수 있다.

- 웹 서버와 API 개발: Node.js를 사용하여 웹 서버를 만들거나 RESTful API를 개발할 수 있다. Express와 같은 프레임워크를 사용하면 개발을 더 용이하게 할 수 있다.

- 실시간 애플리케이션: WebSockets과 같은 실시간 통신을 지원하므로 실시간 알림, 채팅 애플리케이션 등을 개발할 수 있다.

- 자바스크립트 사용: Node.js는 JavaScript 언어를 사용하므로, 브라우저와 서버 간의 일관성 있는 개발이 가능하다.

Node.js는 주로 웹 애플리케이션 개발, API 서버 구축, 마이크로 서비스 아키텍처 등에서 활용되며, 특히 대규모 실시간 애플리케이션과 데이터 처리 작업에 적합한 플랫폼이다.


* * *

# 2. BackEnd
![BackEndImage](backend(kr).png "BackEndImage")

# BackEnd란?
백엔드(Backend)는 소프트웨어 애플리케이션의 뒷단, 즉 사용자에게 직접 보이지 않는 부분을 지칭한다. 애플리케이션의 백엔드는 데이터베이스, 서버, 애플리케이션의 로직, 보안 등을 포함한다. 사용자가 인터페이스를 통해 보는 프론트엔드와 달리, 백엔드는 이러한 프론트엔드 부분을 지원하고 제어하는 역할을 한다.

백엔드의 주요 역할과 기능은 다음과 같다:

- 데이터 관리: 백엔드는 데이터베이스를 관리하고 데이터를 저장, 수정, 삭제하며, 데이터의 무결성과 일관성을 유지한다.

- 로직 처리: 애플리케이션의 비즈니스 로직이나 작업을 처리하며, 데이터의 유효성을 검증하고 요청된 작업을 수행한다.

- API 제공: 백엔드는 프론트엔드와 통신하기 위한 API(Application Programming Interface)를 제공한다. 이를 통해 프론트엔드는 데이터를 요청하고 보내는 등의 상호작용을 할 수 있다.

- 보안: 사용자 데이터와 시스템의 보안을 관리하고 인증, 권한 부여, 데이터 암호화 등을 처리한다.

- 성능 최적화: 백엔드는 애플리케이션의 성능을 최적화하기 위한 작업을 수행하며, 서버의 부하 분산과 확장성을 관리한다.

- 서버 관리: 서버를 설정하고 관리하며, 서버의 운영체제, 네트워크, 데이터베이스 등을 관리한다.

- 데이터 통합: 다른 시스템과 데이터 소스와의 통합 작업을 처리하여 데이터의 일관성과 통합성을 유지한다.

백엔드 개발에는 다양한 프로그래밍 언어와 프레임워크가 사용되며, 서버 사이드 언어로는 Python, Java, Ruby, Node.js, PHP 등이 있다. 백엔드와 프론트엔드는 함께 협력하여 애플리케이션을 개발하며, 이를 통해 사용자에게 효과적이고 안전한 경험을 제공한다.



# 3. DevOps
![FrontEndImage](frontend(kr).png "FrontEndImage")

# DevOps란?
DevOps는 "Development"와 "Operations"의 합성어로, 소프트웨어 개발과 운영의 프로세스를 통합하고 개선하는 방법론 및 문화를 가리킨다. 개발팀과 운영팀 간의 협력을 강화하여 소프트웨어 제공 주기를 더욱 빠르고 안정적으로 만들고, 지속적인 통합과 배포를 지원한다.

DevOps의 핵심 목표는 다음과 같다:

- 지속적 통합(Continuous Integration): 개발된 코드를 빠르게 통합하고 빌드하여 버그를 빨리 찾아내고 해결한다.

- 지속적 배포(Continuous Deployment): 코드 변경 사항을 자동화된 프로세스로 실제 환경으로 배포하여 빠르게 새로운 기능을 사용자에게 제공한다.

- 자동화(Automation): 개발, 빌드, 테스트, 배포 등의 작업을 자동화하여 인간의 실수를 최소화하고 일관된 품질을 유지한다.

- 문화와 협업 강화: 개발팀과 운영팀 간의 협력을 강조하며, 정보 공유와 팀 간의 소통을 촉진한다.

- 모니터링과 로깅: 운영 중인 시스템을 모니터링하고 문제를 조기에 감지하며, 로깅을 통해 문제 해결을 용이하게 한다.

- 인프라스트럭처 코드(Infrastructure as Code): 인프라를 코드로 관리하여 확장성 있고 일관된 인프라 구축과 관리를 실현한다.

- 컨테이너와 오케스트레이션: 컨테이너 기술과 오케스트레이션 툴을 사용하여 애플리케이션 배포와 관리를 간편하게 한다.

DevOps는 애플리케이션의 개발, 배포, 운영 단계 간의 간극을 줄여 개발자와 운영팀 간의 협업을 강화하며, 더욱 빠르고 안정적인 소프트웨어 배포를 가능하게 한다. 이는 사용자 경험 향상과 개발 프로세스의 효율성을 높이는 데 기여한다.

