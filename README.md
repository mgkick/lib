# lib
핵심만 깔끔하게 뽑아낸 실전형 React 상태관리 솔루션

# 🚀 RisonMe - Lightweight React State Management Library

RisonMe는 실전에서 바로 사용할 수 있도록 설계된 경량화된 React 상태관리 라이브러리입니다.  
Redux, Zustand, Recoil의 핵심 아이디어를 통합하면서도 심플하고 확장 가능한 구조를 제공합니다.

---

## ✨ 주요 특징 (Key Features)

### ✅ 자체 Store 엔진
- Redux와 달리 외부 의존성 없이, 순수 자바스크립트로 구현된 자체 Store 엔진 사용.
- 가볍고 빠른 상태관리 구조 제공.

### ✅ Fine-grained selector (미세한 구독 최적화)
- 상태 변경 시 **필요한 부분만 구독**하여 렌더링.
- 불필요한 전체 렌더링 최소화 → 성능 최적화.
- Zustand/Recoil과 유사한 미세 상태 추적 구조.

### ✅ Middleware Chain
- 상태 변경 전후를 가로채어 **로깅, 권한 체크, 비동기 처리 등**을 삽입 가능.
- Redux의 middleware 개념을 직관적이고 간결하게 적용.

### ✅ DevTool 상태추적
- 상태 변경 이력을 자동 기록 및 출력.
- 개발 중 상태 흐름을 쉽게 추적하여 디버깅 편의성 제공.
- 추후 Time Travel Debugging 기반도 확장 가능.

### ✅ 깔끔한 패키징 구조
- npm 패키지처럼 쉽게 프로젝트에 설치 가능.
- 모듈화된 폴더구조로 확장성 확보 (Persistence, Async 등 쉽게 추가 가능).

### ✅ 실전 사용성
- 복잡한 러닝커브 없이 즉시 실전 프로젝트에 적용 가능.
- CRUD, Admin, SaaS, Dashboard 등에 최적화된 경량 아키텍처.

---
📌 RisonMe (React 상태관리 라이브러리) 장점 정리
RisonMe는 실전 프로젝트에서도 바로 활용할 수 있도록 설계된 경량화된 React 상태관리 라이브러리입니다. 기존 Redux, Zustand, Recoil의 핵심 아이디어를 통합하면서도 심플한 구조를 유지한 것이 가장 큰 장점입니다.

✅ 1. 자체 Store 엔진
기존의 Redux처럼 외부 의존성 없이 자체적으로 Store 엔진을 직접 구현.
React와 독립적으로 동작 가능하여 훨씬 가벼운 아키텍처 제공.
전역 상태 관리의 핵심 로직을 명확하고 쉽게 제어할 수 있음.

✅ 2. Fine-grained selector (미세한 구독 최적화)
React 컴포넌트가 필요한 부분 상태만 구독하도록 설계되어 불필요한 렌더링 최소화.
상태 변경이 발생해도 관심 있는 부분만 렌더링되어 성능상 매우 유리.
Zustand, Recoil 등 최신 상태관리 패턴과 유사한 최적화 적용.

✅ 3. Middleware Chain
상태 변경 전후를 미들웨어 체인으로 가로채어 제어 가능.
로깅, 권한 체크, API 호출 등 다양한 공통 로직을 쉽게 삽입 가능.
Redux의 미들웨어 개념을 훨씬 단순하고 직관적으로 구현.

✅ 4. DevTool 상태추적
상태 변경 이력을 자동으로 기록 및 출력.
개발 중 상태 변화 흐름을 손쉽게 추적하고 디버깅 가능.
상태 히스토리 스택이 쌓여 Time-Travel Debugging 의 기반도 제공.

✅ 5. 패키징 구조
라이브러리로 깔끔하게 패키징되어 프로젝트에 npm 패키지처럼 쉽게 설치 가능.
별도의 복잡한 설정 없이 바로 적용 가능.
폴더 구조가 명확하여 확장성 확보 (ex: persistence, snapshot, async 등 확장 준비 가능).

✅ 6. 실전 사용 가능
복잡한 러닝커브 없이 실제 프로젝트에서 바로 사용할 수 있도록 설계.
기본적인 CRUD, Dashboard, SaaS, Admin 패널 등에 매우 적합.
경량화된 구조 덕분에 초급부터 고급까지 모두 커버 가능한 실전 친화형 라이브러리

## 🔧 설치 방법

```bash
npm install risonme
