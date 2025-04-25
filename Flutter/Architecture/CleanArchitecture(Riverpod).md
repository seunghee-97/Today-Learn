# Clean Architecture (Riverpod)

Flutter에서 Riverpod 기반의 Clean Architecture 설계에 대하여 학습한 내용 입니다.

<br />

## 아키텍처 설계의 중요성

앱의 규모가 점점 커지고 복잡성이 늘어날 수록 올바른 앱 아키텍처를 선택하는 것이 중요합니다.

올바른 아키텍처 설계는 의존성을 최대한 줄여 복잡성을 처리하는데 도움이 되어야 합니다.

`UI 코드`, `비즈니스 로직`, `데이터 액세스 로직` 간의 분리를 통해 아래와 같은 효과를 얻을 수 있습니다.

- 최소한의 보일러플레이트 코드로 데이터를 쉽게 가져오고 캐시할 수 있습니다.
- UI 상태(로딩, 데이터, 오류)를 예측 가능한 방식으로 처리할 수 있습니다.
- 테스트 가능한 코드를 작성하고 종속성을 쉽게 mocking 할 수 있습니다.

<br />

## 앱 아키텍처 설계 + Riverpod

4개의 계층(data, domain, application, presentation)으로 구성됩니다.

각 계층은 고유한 책임이 있고, 경계를 넘나드는 통신이 어떻게 이루어지는지에 대한 명확한 규칙이 있습니다.

<img src ="https://codewithandrea.com/articles/flutter-app-architecture-riverpod-introduction/images/flutter-app-architecture.webp" width = "200" />

<br />

## Presentation Layer























