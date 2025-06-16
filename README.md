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

## 🔧 설치 방법

```bash
npm install risonme
