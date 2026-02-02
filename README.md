# 👨‍💻 김민이(KIM MIN LEE) | Front-end Developer
### "데이터 기반 대시보드 설계와 실무 표준을 지향하는 프론트엔드 개발자"

퍼블리셔 및 UI/UX 디자이너 출신으로, **사용자 경험(UX)과 데이터 엔지니어링의 접점**을 이해하는 개발자입니다.
단순한 UI 구현을 넘어, 복잡한 데이터를 시각화하는 **대시보드 설계**와 유지보수 가능한 **아키텍처 구축**에 주력합니다.

---

### 🛠 Tech Stack

| Category | Stacks & Proficiency |
| :--- | :--- |
| **Core** | <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB"/> **Functional Components, Custom Hooks, Optimization**<br><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/> **Strict Mode 기반 타입 설계 및 안정성 확보** |
| **Styling** | <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white"/> **BEM Methodology, CSS Variables, Responsive Layout** |
| **Backend & Tools** | <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/> **Git Flow 준수, Issue/PR 관리** |

---

### 📂 Key Project: BEMS 3D Dashboard
> **건물 에너지 관리 시스템(BEMS) 실시간 관제 대시보드**
> *기술 스택: React, TypeScript, Supabase, CSS Variables(vmin)*

#### 1. Resolution-Independent Layout 설계 (`vmin`)
* **Problem:** 다양한 해상도(대형 관제 모니터, 태블릿 등) 환경에서 단일 화면(One-Page) 대시보드의 레이아웃이 틀어지는 문제.
* **Solution:** 픽셀(px) 기반이 아닌 Viewport Unit(`vmin`)을 활용한 **Fluid Layout System** 설계.
* **Result:** 주요 해상도(4:3, 16:9, Ultra-wide) 환경에서 **UI 깨짐 없는 레이아웃 안정성** 확보.

#### 2. Client-side Data Pre-processing Layer 구축
* **Problem:** 현장의 비표준화된 CSV 데이터와 DB 스키마 간의 불일치로 인한 데이터 로드 실패.
* **Solution:** 클라이언트 단에서 데이터 타입을 검증하고 DB 구조에 맞게 변환(Transform)하는 **전처리 레이어(Pre-processing Layer)** 구현.
* **Result:** 수동 가공 없이도 데이터 정합성을 유지하며, 업로드 성공률 및 업무 효율 개선.

#### 3. Scalable Component Architecture
* **Problem:** 반복되는 위젯과 카드 UI를 매번 새로 구현함에 따라 **코드 중복(Redundancy)**이 발생하고, 스타일 변경 시 수정 범위가 넓어지는 비효율 발생.
* **Solution:** 공통 UI 요소를 식별하여 **Props 기반의 재사용 가능한 컴포넌트**로 추상화하고, **TypeScript Interface**로 타입 안정성(Type Safety) 확보.
* **Result:** 신규 대시보드 화면 구성 시 **개발 생산성 향상** 및 일관된 디자인 시스템 적용으로 수정 대응력 강화.

---

### 🎯 Professional Focus & Growth
* **State Management:** Server State(데이터)와 Client State(UI)를 분리하여 불필요한 리렌더링 최소화 및 성능 최적화.
* **Scalable Architecture:** 컴포넌트 재사용성을 높이는 Atomic 패턴 연구 및 선언적 코드 작성 지향.
* **Clean Code:** 협업을 고려한 명확한 네이밍 컨벤션 준수와 코드 가독성 확보.

---

### 📞 Contact
* **Email:** [qqazs98@gmail.com]
