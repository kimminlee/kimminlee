# Front-end Developer (React / TypeScript)

UI/UX 디자인 및 퍼블리싱 경험을 기반으로 **실무 표준과 유지보수성**을 최우선으로 고려하는 프론트엔드 개발자입니다.
감보다는 논리에 기반한 코드 작성, 명확한 아키텍처 설계를 지향합니다.

---

### 🛠 Tech Stack

| Category | Stacks |
| --- | --- |
| **Core** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) |
| **Design & Styling** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) (BEM Methodology, CSS Variables) |
| **Backend & Tools** | ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) |

---

### 🚀 Key Project

#### **BEMS 3D Dashboard (건물 에너지 관리 시스템)**
> *Supabase 기반의 데이터 연동 및 One-Page 대시보드 구축*

**1. One-Page Dashboard Architecture (`vmin` Layout)**
* **문제:** 스크롤 없이 **단일 화면(One-Page)**에 모든 에너지 흐름 데이터를 표출해야 했으나, 모니터 비율(4:3, 16:9, 와이드)에 따라 레이아웃이 깨지거나 잘리는 문제 발생.
* **해결:** Viewport Unit(`vmin`)을 기반으로 한 **Fluid Layout** 시스템을 설계하여, 단순 크기 조절이 아닌 **화면 비율에 따른 완벽한 스케일링** 구현.
* **성과:** 대형 관제 모니터부터 노트북까지, 모든 해상도에서 **정보 밀도(Density)와 가독성**이 유지되는 UI 구축.

**2. Data Integration & Logic (Supabase + CSV)**
* **Supabase 활용:** Supabase를 도입하여 관계형 테이블을 설계하고, 클라이언트와 실시간 데이터 연동 환경 구축.
* **데이터 정합성 확보:** DB 스키마와 현장 엑셀(CSV) 양식이 다른 문제를 해결하기 위해, 업로드 시 **클라이언트 단에서 데이터를 파싱(Parsing) 및 전처리**하여 DB 구조에 맞게 매핑하는 미들웨어 로직 구현.

**3. UX Engineering & State Handling**
* **디자인/개발 통합 역량:** UI/UX 디자인 경험을 살려 단순히 "동작하는 화면"이 아닌, 사용자의 모든 시나리오를 고려한 인터페이스 설계.
* **상태별 UI(State UI) 대응:** Happy Path뿐만 아니라 `Loading`, `Error`, `Empty`, `Partial Data` 등 다양한 엣지 케이스에 대한 대응 UI를 시스템화하여 사용자 경험(UX) 완성도 제고.
* **가독성 개선:** 데이터 대시보드의 핵심인 '숫자 가독성'을 위해 시스템 폰트를 Noto Sans에서 **Pretendard**로 마이그레이션하고 타이포그래피 계층 구조 재정립.

---

### 🎯 Current Focus
* **상태 관리 패턴 정립:** 단순 UI State와 서버 데이터(Server State)의 효율적인 분리 및 관리.
* **Clean Code:** 선언적 프로그래밍을 통한 가독성 높은 코드 작성 및 컴포넌트 재사용성 극대화.

---

### 📞 Contact
* **Email:** [qqazs98@gmail.com]
