# 박준영 (Junyoung Park) — Software / AI Engineer

> **C#/.NET 기반의 견고한 엔지니어링 역량을 토대로, AI·에이전트 엔지니어링으로 무게중심을 옮기고 있는 개발자입니다.**
> 단순히 LLM을 호출하는 수준을 넘어 **에이전트 워크플로우 설계, 도구·플러그인 생태계 구축, AI를 제품에 녹여내는 실전 경험**을 쌓고 있습니다.

📍 Pangyo, Korea · 🏢 Smilegate RPG · 🐙 [github.com/jaywapp](https://github.com/jaywapp) · 📝 [jaywapp.tistory.com](https://jaywapp.tistory.com/)

> 📨 연락처(이메일/전화)와 아래 〔직접 입력〕 표시 항목은 제출 전 채워 주세요.

---

## 🎯 한 줄 소개 (Headline)

**10년 가까이 C#/.NET 데스크톱·백엔드를 만들어 온 엔지니어가, 이제 AI 에이전트로 개발 방식 자체를 바꾸고 있습니다.**

- ✅ **AI 응용 제품**: Claude SDK로 자산 분석·투자 리포트를 자동 생성하는 실사용 서비스 구축
- ✅ **에이전트 인프라**: Claude Code 플러그인·스킬·MCP 마켓플레이스 등 *AI를 만드는 도구* 직접 설계
- ✅ **탄탄한 기반기술**: WPF 데스크톱, .NET 백엔드, NuGet 라이브러리, CI/CD 도구까지 풀스택 엔지니어링 경험

---

## 🧠 핵심 역량

### 1. AI · Agentic Engineering *(현재 집중 영역)*
- **LLM 제품화**: `@anthropic-ai/sdk`를 활용해 도메인 데이터(자산·시세)를 분석·해설하는 기능을 실제 웹 제품에 통합
- **에이전트 워크플로우 자동화**: "QA 리포트 → 태스크 분해 → 서브에이전트 실행 → GitHub PR 생성"처럼 **사람의 반복 작업을 에이전트 파이프라인으로 대체**
- **AI 개발 생태계 구축**: Claude Code / Codex / Cursor / MCP를 아우르는 플러그인 마켓플레이스·스킬 라이브러리 설계 및 스키마 표준화
- **AI 온보딩 자동화**: AI CLI(Claude Code·Codex) 설치·로그인·규칙 파일 생성을 한 번에 처리하는 도구 제작

### 2. Backend & Desktop Engineering *(기반 역량)*
- **.NET 생태계 전반**: C#, .NET 8, netstandard, ASP.NET Core, WPF(MVVM)
- **아키텍처 설계**: Protocol/Adapter/UI 계층 분리, IPC(Memory-Mapped File), 라이브러리 모듈화 및 NuGet 배포
- **개발 생산성 도구**: CI/CD(TeamCity) 관리 도구, 코드 리뷰 자동화, 리소스 변환기 등 *팀의 생산성을 높이는 도구* 다수 제작

### 3. Full-stack & Cross-platform
- **웹**: TypeScript, Next.js(App Router), React, Drizzle ORM, PostgreSQL(Neon), Firebase, Vercel
- **모바일**: Flutter, Dart — Google Sheets/Nest Hub 연동 등 외부 서비스 통합 경험

---

## 🛠️ 기술 스택

| 구분 | 기술 |
|------|------|
| **AI / LLM** | Claude (Anthropic SDK), Claude Code 플러그인·스킬, MCP, Codex/Cursor 연동, 에이전트 워크플로우 설계 |
| **Languages** | C#, TypeScript, JavaScript, Python, Dart |
| **Backend / Desktop** | .NET 8 / netstandard, ASP.NET Core, WPF(MVVM, Prism), IPC(MMF) |
| **Web** | Next.js, React, NextAuth, Drizzle ORM, Recharts |
| **Mobile** | Flutter, Dart |
| **Data / Infra** | PostgreSQL(Neon), Firebase, MongoDB, Vercel, GitHub Actions |
| **Tooling** | Git, TeamCity, Selenium, NuGet 패키징 |

---

## 🚀 대표 프로젝트

### 1. AssetManagement — 가족 자산관리 AI 대시보드 `2026`
> Claude SDK가 자산 데이터를 분석·해설하는 실사용 웹 서비스

- **문제**: 흩어진 가족 자산·시세 데이터를 사람이 매번 해석해야 하는 번거로움
- **해결**: `@anthropic-ai/sdk`로 자산 현황을 분석·요약하는 AI 리포트 기능 구현, `yahoo-finance2` 시세 연동 + Recharts 시각화
- **스택**: Next.js(App Router) · TypeScript · NextAuth · Drizzle ORM · Neon Postgres · Vercel
- 🔗 https://github.com/jaywapp/AssetManagement

### 2. claude-buffett — AI 투자 분석 자동화 시스템 `2026` ⭐
> Claude 기반으로 종목 분석·일간/주간 시장 리포트를 자동 작성하는 파이프라인

- **성과**: 요청·일간·주간 리포트를 마크다운으로 자동 생성하고, GitHub Pages 웹뷰어로 어디서나 열람 가능하게 배포
- **포인트**: LLM을 *일회성 호출*이 아니라 *정기 리포트 생산 파이프라인*으로 운영
- 🔗 https://github.com/jaywapp/claude-buffett · [리포트 뷰어](https://jaywapp.github.io/claude-buffett/)

### 3. ai-marketplace — AI 플러그인 통합 마켓플레이스 `2026`
> Claude Code · MCP · Codex · Cursor 확장을 한 곳에서 등록·공유

- **설계**: 멀티 런타임(`.claude-plugin`/`.codex-plugin`/`.cursor-plugin`)을 아우르는 공통 메타데이터 스키마 정의
- **자동화**: 플러그인 스키마 검증 + `registry.json` 자동 빌드 스크립트 구축
- 🔗 https://github.com/jaywapp/ai-marketplace

### 4. claude-plugin-qa — QA 워크플로우 자동화 플러그인 `2026`
> QA 리포트를 받아 코드 수정 PR까지 자동으로 연결하는 Claude Code 플러그인

- **워크플로우**: 리포트 파싱·저장 → 우선순위 태스크 분해(🔴버그/🟡UI/🟢기타) → 서브에이전트 자동 실행 → GitHub PR 생성
- **의미**: *AI가 AI를 오케스트레이션*하는 에이전트 파이프라인을 직접 설계·구현
- 🔗 https://github.com/jaywapp/claude-plugin-qa

### 5. UnrealEditorBridge — UE5 ↔ .NET 실시간 IPC 브리지 `2026`
> 게임 엔진과 외부 도구를 잇는 고성능 시스템 엔지니어링 사례

- **설계**: Memory-Mapped File 기반 단방향 IPC — 에셋 스냅샷(≤4MB), Ring Buffer 이벤트 스트림(6,144 슬롯), Heartbeat 모니터링
- **구조**: Protocol / Adapter / WPF 3계층 분리로 재사용성·테스트 용이성 확보
- 🔗 https://github.com/jaywapp/UnrealEditorBridge

> 그 외 프로젝트 전체 목록은 **[Projects 허브 README](./README.md)** 참고.

---

## 💼 경력

### Smilegate RPG — Software Developer (C# / .NET)
〔직접 입력: 재직 기간 / 담당 조직 / 주요 업무·성과〕

- 예) 게임 클라이언트·툴 개발, 사내 생산성 도구 제작 등
- 예) 정량 성과(빌드 시간 단축, 자동화로 절감한 공수 등)

> 💡 위 GitHub 프로젝트들에서 드러나는 강점(WPF 도구 개발, CI/CD 자동화, AI 도구 도입)을 실제 업무 성과와 연결해 작성하면 설득력이 높아집니다.

---

## 🎓 학력 · 기타

- 〔직접 입력: 학력 / 전공〕
- 〔직접 입력: 자격증·수상·발표 등〕
- 📝 기술 블로그 운영: [jaywapp.tistory.com](https://jaywapp.tistory.com/)
- 🐙 GitHub 활동: 2016년부터 47개 공개 저장소 운영 ([@jaywapp](https://github.com/jaywapp))

---

## 🧭 지향점

> **"좋은 도구를 만드는 엔지니어"** 에서 **"AI로 일하는 방식을 재설계하는 엔지니어"** 로.
> 탄탄한 .NET 엔지니어링 경험 위에 AI·에이전트 역량을 더해, 제품과 팀의 생산성을 동시에 끌어올리는 일을 하고 싶습니다.

<sub>📅 최종 수정: 2026-06-03</sub>
