# Git 저장소 이름 규칙(Git repository naming convention)

일관적이고, 색인이 간편한 Git 저장소 명명 규칙을 정합니다. 프로젝트를 생성하거나 기존에 작성된 프로젝트를 참고하고자 할 떄, 일관되지 않은 규칙으로 작성된 저장소 이름으로 인해 어려움을 겪는 것을 방지하고자 함에 목적이 있습니다.

---

## 원칙

1. 저장소 이름 규칙은 카멜(Camel) 표기법을 사용합니다.
2. 저장소의 Keyword 간의 구분 표시는 **하이픈(-)** 을 사용합니다.
3. 저장소의 Naming convention은 Project progress-Proejct name-Project role-Development environment의 형태로 제안합니다.

---

## 프로젝트 진행 상태(Project progress)

프로젝트가 개발 진행 상 어떠한 상태에 있는 지를 나타내는 Keyword입니다. 

- 'doing' : 이 프로젝트가 진행 중임을 나타냅니다.
- 'review' : 이 프로젝트가 검토 중임을 나타냅니다.
- 'achive' : 이 프로젝트가 보관 중임을 나타냅니다.

## 프로젝트 명(Proejct name)

이 프로젝트의 이름을 나타내는 Keyword입니다.

## 프로젝트 역할(Project role)

이 곳에는 저장소가 프로젝트나 서비스에서 기여하는 역할 대해서 적어주세요. 하나의 프로젝트에서 생성된 저장소가 여러 개 일 때, 이 단어만 보고 어떤 기능이 들어 있을 지 예상할 수 있도록 이름을 선택하세요. 굳이 1단어가 아니어도 됩니다

예시 :

| 역할(Role) | 설명(description)   |
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
| ...|그 외 역할을 잘 설명하는 단어|

## 개발환경

이 곳에는 해당 프로젝트나 서비스가 동작하는 플랫폼 혹은 개발의 사용되는 언어를 넣어주세요. 가장 중요하거나 강조되어야 할 플랫폼을 적어줌으로써 읽는 사람이 헷갈리지 않도록 도와줄 수 있습니다.

nodejs, javascript 중에 고민한다면 nodejs를 선택하세요. nodejs 플랫폼을 적어줌으로써 사용되는 언어가 javascript 인지 자연스럽게 추론 할 수 있습니다. 이와 같이 자연스럽게 언어가 추론되는 플랫폼은 플랫폼 명을 적어주세요. 플랫폼이 OS에 제한되는 경우에도 굳이 OS를 적을 필요는 없습니다. 단, 특정 환경에서 동작하는 것을 강조하고 싶다면 적어주세요. 예를 들어 linux-ARM 환경에서만 동작한다면 강조해서 적어주세요. 

예시 :

| Platform | description   |
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
