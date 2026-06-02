# 🗂️ Projects — jaywapp

> **Junyoung Park (jaywapp)** 의 프로젝트 허브입니다.
> 최근에는 **C#/.NET 엔지니어링 역량을 기반으로 AI·에이전트 엔지니어링**으로 무게중심을 옮기고 있습니다.
> Claude / LLM 기반 자동화·에이전트 시스템, 풀스택 웹/앱, .NET 라이브러리·도구를 만듭니다.

📌 GitHub: [@jaywapp](https://github.com/jaywapp) · 📝 Blog: [jaywapp.tistory.com](https://jaywapp.tistory.com/) · 🧑‍💻 이력서: [RESUME.md](./RESUME.md)

<br/>

## 🧰 Core Stack

![Claude](https://img.shields.io/badge/Claude_AI-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Anthropic SDK](https://img.shields.io/badge/Anthropic_SDK-191919?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=flat-square&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_8-5C2D91?style=flat-square&logo=.net&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-0078D7?style=flat-square&logo=windows&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

<br/>

---

## 🤖 AI · Agentic Engineering

> LLM(Claude)과 에이전트를 실제 제품·워크플로우에 결합한 프로젝트. 현재 가장 집중하는 영역입니다.

### [AssetManagement](https://github.com/jaywapp/AssetManagement) — *Family Asset Management*
> Claude SDK로 자산 데이터를 분석·해설하는 **가족 자산관리 AI 대시보드**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Anthropic SDK](https://img.shields.io/badge/Anthropic_SDK-191919?style=flat-square&logo=anthropic&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![Neon](https://img.shields.io/badge/Neon_Postgres-00E599?style=flat-square&logo=postgresql&logoColor=white)

- `@anthropic-ai/sdk` 기반 자산 분석·리포트 자동 생성
- Next.js App Router + NextAuth 인증, Drizzle ORM + Neon(Serverless Postgres)
- `yahoo-finance2` 시세 연동, Recharts 시각화 / Vercel 배포
- 🗓️ 최근 업데이트: 2026-06

---

### [claude-buffett](https://github.com/jaywapp/claude-buffett) ⭐ — *AI 투자 분석*
> Claude AI 기반 **주식 투자 분석 자동화 시스템** — 종목 분석·일간/주간 시장 리포트 자동 작성

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_AI-D97757?style=flat-square&logo=anthropic&logoColor=white)

- 요청·일간·주간 리포트를 마크다운으로 자동 생성하는 파이프라인
- GitHub Pages 웹뷰어로 모바일·PC 어디서나 열람 → **[리포트 뷰어](https://jaywapp.github.io/claude-buffett/)**
- 🗓️ 최근 업데이트: 2026-06

---

### [ai-marketplace](https://github.com/jaywapp/ai-marketplace) — *AI 플러그인 마켓플레이스*
> Claude Code 플러그인 · MCP 서버 · Codex · Cursor 확장을 등록·공유하는 **통합 마켓플레이스**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

- 플러그인 공통 메타데이터 스키마 + 멀티 런타임(`.claude-plugin` / `.codex-plugin` / `.cursor-plugin`)
- `validate-plugin` 스키마 검증 + `build-registry`로 `registry.json` 자동 빌드
- 🗓️ 최근 업데이트: 2026-05

---

### [claude-plugin-qa](https://github.com/jaywapp/claude-plugin-qa) — *QA 워크플로우 자동화*
> Claude for Chrome QA 리포트를 받아 **리포트 저장 → 태스크 분리 → 서브에이전트 실행 → GitHub PR 생성**까지 자동화하는 Claude Code 플러그인

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

- `/qa` 슬래시 커맨드 한 번으로 QA 결과를 코드 수정 PR까지 연결
- 우선순위 분류(🔴 버그 / 🟡 UI / 🟢 기타) 후 서브에이전트 기반 자동 수정
- 🗓️ 최근 업데이트: 2026-04

---

### [claude-skills](https://github.com/jaywapp/claude-skills) — *개인 Claude 스킬 모음*
> 반복 작업을 표준화한 개인용 **Claude Code 스킬** 라이브러리

![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

- 각 스킬은 독립 `SKILL.md` 본체로 구성, `~/.claude/skills/`에 복사해 사용
- 🗓️ 최근 업데이트: 2026-04

---

### [AIInstaller](https://github.com/jaywapp/AIInstaller) — *AI CLI 부트스트래퍼*
> Windows에서 **Claude Code / Codex CLI 설치·로그인·규칙 파일 생성**을 한 번에 처리하는 WPF 마법사

![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=flat-square&logo=c-sharp&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-5C2D91?style=flat-square&logo=.net&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-0078D7?style=flat-square&logo=windows&logoColor=white)
![Prism](https://img.shields.io/badge/Prism-orange?style=flat-square)

- 설치 상태 확인 → 자동 설치 → 로그인 연결 → `RULE.md` / `CLAUDE.md` / `AGENTS.md` 생성
- CLIAdapters 구조로 Claude·Codex별 감지·설치 로직 분리
- 🗓️ 최근 업데이트: 2026-03

---

### [AICodeReviewRequester](https://github.com/jaywapp/AICodeReviewRequester) — *AI 코드 리뷰 자동화*
> AI 코드 리뷰 요청을 자동화하는 C# 도구

![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=flat-square&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-5C2D91?style=flat-square&logo=.net&logoColor=white)

<br/>

---

## 🌐 Web · Full-stack 제품

### [Crewith](https://github.com/jaywapp/Crewith) — *크루/팀 운영 웹·앱 솔루션*
> 관리자 웹 · 회원 앱 · 운영진 앱으로 구성된 풀스택 솔루션 ([관리자 데모](https://crewith-admin.vercel.app))

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

- 기획(브리프·요구사항·MVP·로드맵)부터 설계(데이터 모델·API·UI·Firebase 보안 규칙), QA 체크리스트까지 **전 산출물 문서화**
- 🗓️ 최근 업데이트: 2026-05

---

### [squad-maker](https://github.com/jaywapp/squad-maker) — *축구 스쿼드 메이커*
> 라인업을 짜고 공격 패턴을 **GIF로 만들어 공유**하는 웹앱 ([라이브 데모](https://jaywapp.github.io/squad-maker/))

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

- 5~11인제 포메이션 프리셋·드래그 배치·PNG 내보내기
- 공격 패턴 경로 그리기 → ease-in-out 애니메이션 → 단일/연속 GIF 저장
- 🗓️ 최근 업데이트: 2026-06

---

### GyungChung (경청) — *다중 레포 풀스택 웹 서비스*

| Repository | 역할 | 스택 |
|-----------|------|------|
| [GyungChung.Core](https://github.com/jaywapp/GyungChung.Core) | 공통 도메인 · 비즈니스 로직 | C# / .NET |
| [GyungChung.API](https://github.com/jaywapp/GyungChung.API) | REST API 서버 | C# / .NET |
| [Gyungchung.Web](https://github.com/jaywapp/Gyungchung.Web) | 웹 프론트엔드 | JavaScript |

---

### 위치 기반 React 서비스

| Repository | 설명 | 데모 |
|-----------|------|------|
| [proto-shop-finder](https://github.com/jaywapp/proto-shop-finder) | 현재 위치 기반 스포츠토토 판매점 검색 (React + Kakao Map) | [🔗 Site](https://jaywapp.github.io/proto-shop-finder/) |
| [sijang-2-manchan](https://github.com/jaywapp/sijang-2-manchan) | 전국 전통 시장 맛집 정보 서비스 (React + Kakao Map) | [🔗 Site](https://jaywapp.github.io/sijang-2-manchan/) |

<br/>

---

## 📱 Mobile · Cross-platform (Flutter / Dart)

### [BabyRecorder](https://github.com/jaywapp/BabyRecorder) ⭐
> Google Nest Hub **음성 명령**으로 아기 육아 기록을 Google 스프레드시트에 자동 저장하는 스마트 육아 도우미

![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white)

| Repository | 설명 |
|-----------|------|
| [be-my-colleague](https://github.com/jaywapp/be-my-colleague) | Flutter 기반 동료 매칭 서비스 |
| [jaywapp-dart-google-sheet](https://github.com/jaywapp/jaywapp-dart-google-sheet) | Dart용 Google Sheets 연동 패키지 |

<br/>

---

## 🖥️ Desktop Applications (C# / .NET / WPF)

### [UnrealEditorBridge](https://github.com/jaywapp/UnrealEditorBridge)
> UE5 Editor ↔ .NET/WPF 도구 간 **실시간 IPC 브리지**

![C#](https://img.shields.io/badge/C%23-%23239120.svg?style=flat-square&logo=c-sharp&logoColor=white)
![.NET 8](https://img.shields.io/badge/.NET_8-5C2D91?style=flat-square&logo=.net&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/UE5-0E1128?style=flat-square&logo=unrealengine&logoColor=white)

- Memory-Mapped File(MMF) 기반 단방향 IPC — 에셋 스냅샷(최대 4MB), Ring Buffer 이벤트 스트림(6,144 슬롯), Heartbeat 모니터링
- Protocol / Adapter / WPF 3계층 분리

| Repository | 설명 | 스택 |
|-----------|------|------|
| [TeamCityMayor](https://github.com/jaywapp/TeamCityMayor) | TeamCity CI/CD 파이프라인 관리 도구 | C# / WPF |
| [FMRookieScouter](https://github.com/jaywapp/FMRookieScouter) | Football Manager 유망주 정보 조회 | C# / WPF |
| [Jaywapp.Toasket](https://github.com/jaywapp/Jaywapp.Toasket) | 프로토/토토 구매 내역 관리·통계 (Selenium 수집) | C# / WPF |

<br/>

---

## 📦 .NET Libraries & Packages

| Repository | 설명 | 스택 | NuGet |
|-----------|------|------|-------|
| [Jaywapp.Infrastructure](https://github.com/jaywapp/Jaywapp.Infrastructure) | 필터링·헬퍼·확장 메서드 공통 라이브러리 | C# / netstandard2.0 | – |
| [Jaywapp.Slack](https://github.com/jaywapp/Jaywapp.Slack) | Slack Web API (Block Kit) .NET 래퍼 | C# / netstandard2.1 | ✅ |
| [Jaywapp.Wpf](https://github.com/jaywapp/Jaywapp.Wpf) | WPF Converter · Helper 공통 패키지 | C# / WPF | ✅ |
| [Jaywapp.UI](https://github.com/jaywapp/Jaywapp.UI) ⭐ | 커스텀 WPF UI 컴포넌트 | C# / WPF | – |
| [Jaywapp.Graphic.Geometry](https://github.com/jaywapp/Jaywapp.Graphic.Geometry) | 2D 그래픽 지오메트리 유틸리티 | C# | – |
| [Jaywapp.Algorithm](https://github.com/jaywapp/Jaywapp.Algorithm) | 알고리즘 구현 라이브러리 | C# | – |

<br/>

---

## 🔧 Utilities & Tools

| Repository | 설명 | 스택 |
|-----------|------|------|
| [Jaywapp.AppendableFilter](https://github.com/jaywapp/Jaywapp.AppendableFilter) | 키워드 입력에 따라 후보를 줄여가는 목록 필터 컴포넌트 | C# |
| [Jaywapp.Utility.BuilderWizard](https://github.com/jaywapp/Jaywapp.Utility.BuilderWizard) | Builder 패턴 객체 생성을 돕는 Wizard 다이얼로그 | C# / WPF |
| [ExcelToResxConverter](https://github.com/jaywapp/ExcelToResxConverter) | Excel → .resx 리소스 파일 변환기 | C# |

<br/>

---

## 📚 Study & Reference

| Repository | 설명 |
|-----------|------|
| [csharp_tip](https://github.com/jaywapp/csharp_tip) | C# 개발 팁 모음집 |
| [Jaywapp.Algorithm.KMP](https://github.com/jaywapp/Jaywapp.Algorithm.KMP) | KMP 문자열 검색 알고리즘 예제 |
| [Tutorials](https://github.com/jaywapp/Tutorials) | 튜토리얼 실습 코드 |
| [wiki](https://github.com/jaywapp/wiki) | 개인 위키 |

<br/>

---

<div align="center">
  <a href="https://github.com/jaywapp">
    <img src="https://github-readme-stats.vercel.app/api?username=jaywapp&show_icons=true&theme=default&hide_border=true" />
  </a>
</div>

<sub>📅 마지막 동기화: 2026-06-03 · 본 목록은 공개 레포 중 대표 프로젝트를 큐레이션한 것입니다.</sub>
