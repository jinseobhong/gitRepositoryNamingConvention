# Git 저장소 이름 규칙(Git repository naming convention)

일관적이고, 색인이 간편한 Git 저장소 명명 규칙을 정합니다. 프로젝트를 생성하거나 기존에 작성된 프로젝트를 참고하고자 할 떄, 일관되지 않은 규칙으로 작성된 저장소 이름으로 인해 어려움을 겪는 것을 방지하고자 함에 목적이 있습니다.

## 기본적인 명명 규칙(Default naming convention)

1. Git 저장소 이름에 사용되는 Keyword는 의미론(Sementic)적으로 작성합니다.
2. Git 저장소 이름에 사용되는 Keyword의 표기는 카멜(Camel) 표기법을 사용합니다.
3. Git 저장소 이름에 사용되는 Keyword 간의 구분은 '하이픈(-)'을 사용합니다.
3. Git 저장소 이름 규칙(Naming convention)은 Proejct name-Project development enviroment-Project purpose 의 형태로 제안합니다.
4. Git 저장소 이름 규칙은 git repository라는 것을 나타내기 위해 .git으로 마무리합니다.

### 이름(Name)

이 Keyword는 프로젝트의 이름을 나타내는 Keyword입니다.

- 웹 사이트의 경우 특별히 명명한 프로젝트 명이 없을 경우 도메인(Domaion) 자체가 프로젝트 명이 될 수 있습니다. 
  - http://domain.com ➔ domain.com
  - http://sub.domain.com ➔ sub.domain.com

### 개발 환경(development enviroment)

이 Keyword는 프로젝트의 개발 환경을 나타내는 Keyword입니다.
- 개발 환경은 언어, 사용된 개발 도구, 운영 체제 등을 포함합니다.
- 특정 개발 환경에서만 프로젝트가 작동되는 경우 그 Keyword를 우선적으로 작성합니다.

[gitRepositoryNamingConvention](https://docs.google.com/spreadsheets/d/1hV5yFamunIxl8XgX0xQXBUziWIqdRslpjSdJql-uBlg/edit?usp=sharing)
| 개발 환경(development enviroment) | 설명(description)   |
| --- | --- |
| nodejs | nodejs 어플리케이션 |
| angular | Angular 어플리케이션 |
| dotnet | dotnet 어플리케이션 |
| javascript | javascript 어플리케이션 |
| cpp | c++ 어플리케이션 |
| java | java 어플리케이션 |
| windows | 윈도우에서 동작 |
| linux-arm | linux ARM 버전에서 동작 |
| jetson-tx-1 | tx-1 보드 위에서 동작 |
| ...|그 외 개발 환경을 잘 설명하는 단어|

### 용도(Purpose)

이 Keyword는 프로젝트가 어떠한 용도로 사용되는 지를 나타내는 Keyword입니다.

| 용도(Purpose) | 설명(description)   |
| --- | --- |
| lib | 라이브러리 |
| server | 서버 |
| client | 클라이언트 |
| core | 핵심 기능 |
| extention | 확장 기능 |
| sdk | Software Development Kit |
| interface | interface |
| cli | command-line user interface |
| gui | graphical user interface |
| util | 도구들 |
| tools | 도구들 |
| samples | 샘플 코드 |
| documents | 문서 |
| ...|그 외 용도를 잘 설명하는 단어|
