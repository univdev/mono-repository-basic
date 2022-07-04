# Mono Repository

## 개요

Mono Repository는 여러개로 구성되어야 하는 Project를 하나의 Repository로 관리하는 방식입니다.

## 장점

프로젝트를 이렇게 구성하면 가져올 수 있는 이점이 있습니다.

- [ ] 개발자가 IDE 환경에서 여러 Project 폴더를 스위칭하면서 작업하지 않아도 됩니다.
- [ ] 다른 프로젝트에서 만들어진 에셋(패키지, 컴포넌트 등)을 다른 패키지에 유연하게 import 할 수 있습니다.

## 방식

본 예시에서는 Mono Repository를 관리할 수 있는 `lerna`를 사용하여 Mono Repository를 구성해보도록 하겠습니다.
