# Susie Im · 임수지

**AX Engineer (AI Transformation Engineer)**

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=20&duration=2400&color=D6DEEB&vCenter=true&width=420&lines=Clear+purpose%2C+bold+methods.&repeat=false">
  <img alt="Clear purpose, bold methods." src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=20&duration=2400&color=2E4A7D&vCenter=true&width=420&lines=Clear+purpose%2C+bold+methods.&repeat=false">
</picture>

I'm an AX engineer who has worked as both planner and developer: I define the problem, write the spec, and build it with AI coding agents.
I start by defining why the work matters, try methods from outside my role, keep what fits and document it for the next person.
Most recently I built Ppang: 2 months of planning, then 1 day of AI-driven implementation.

[Email](mailto:susie.djqan@gmail.com) · [LinkedIn](https://www.linkedin.com/in/susie-im-8b9050270) · [Deck (PDF)](docs/Deck_SusieIm.pdf) · [Resume (EN)](docs/Resume_SusieIm_EN.pdf) · [이력서 (KR)](docs/Resume_SusieIm_KR.pdf)

<img src="https://skillicons.dev/icons?i=nodejs,ts,java,spring,py,supabase,aws,docker,githubactions,solidity&perline=10" alt="Node.js, TypeScript, Java, Spring, Python, Supabase, AWS, Docker, GitHub Actions, Solidity">

Also: Claude Code (rules, stop conditions, sub-agents) · Gemini CLI/API · Hugging Face · Hardhat (hackathon MVP stage) · Base Sepolia

**Public code to start with:** [ProofIN backend](https://github.com/ProofINer/proofin_backend) — idea, smart contracts, backend and deployment in one project.

## Now — Ppang

**Cross-border group settlement app** · Solo, planning & development · Aug 2026–present
Problem: groups with mixed nationalities and currencies struggle to split shared costs. Ppang lets them settle in USDC (a dollar-pegged stablecoin) by entering only the total and the recipient.

- Cut required input to two fields (total, recipient); kept the scope on settlement; moved to non-custodial (the app never holds user funds) after regulatory review
- Wrote the spec and handoff docs (35 decisions) myself; an AI coding agent built it in 1 day of run time → 282 automated tests passed, transfers verified on Base Sepolia testnet (test network, no real money)
- Set up a separate review agent that never saw the code; it found 2 pre-deployment violations (e.g. full wallet addresses in logs), fixed before deployment

`Private repo · in progress · code walkthrough on request via Email`

## How the method was built

Oldest first. Each project changed one thing about how I work.

- **[Fundit](https://github.com/errorinusermane/fundit-dapp)** · 2025 · Team · my part: smart contracts, backend, app
  No shared process; dev began before planning and the team's views of the service diverged → plan first, then build. Grand Prize, BNB Chain Ideathon.
- **[SyncMe](https://github.com/ECC-2025-SyncMe/syncme-backend)** · 2025 · Team · my part: sole planner, backend
  Intent wasn't shared and dev lagged → one shared context doc from then on.
- **ProofIN** ([backend](https://github.com/ProofINer/proofin_backend) · MVP as FairStay: [backend](https://github.com/FairStayer/fairstay_mvp_backend)) · 2025–2026 · Team · my part: idea, smart contracts, backend, deployment
  Reframed the problem as tenants' fear of losing deposits; re-aligned team goals, meetings 2–3 h → under 30 min. Excellence Award, RISE 2025.
- **Automation system** · 2026 · Personal · `Private · walkthrough on request via Email`
  A backtest look-ahead bug caused live losses → added a pre-deployment validation step, dry-run mode and OIDC deploys.

Ppang uses all four: plan first, one context doc, a reframed problem, validation before deployment.

<details>
<summary><b>한국어로 보기</b></summary>

<br>

**AX 엔지니어 · 목적은 분명하게, 방법은 과감하게.**

기획과 개발을 모두 맡아 본 AX 엔지니어 임수지입니다.
일을 왜 하는지 먼저 정하고, 내 직무가 아닌 방식까지 직접 써 본 뒤 맞는 것만 골라 문서로 남깁니다.
최근 정산 앱 Ppang을 2개월 기획한 뒤, 개발 AI로 하루 만에 구현해 테스트넷 송금까지 확인했습니다.

**기술** Node.js · TypeScript · Java Spring · Python · Supabase · AWS · Docker · GitHub Actions(OIDC) · Solidity·Hardhat(해커톤 MVP 단계) · Base Sepolia · Claude Code(규칙 파일·중단 조건·서브 에이전트 검수) · Gemini CLI/API · Hugging Face

**먼저 볼 코드:** [ProofIN 백엔드](https://github.com/ProofINer/proofin_backend) — 아이디어·컨트랙트·백엔드·배포를 한 프로젝트에서 맡음

### 지금 — Ppang

**다국적 그룹 정산 앱** · 기획·개발 1인 · 2026.08–현재
문제: 국적·통화가 다른 그룹은 함께 쓴 돈을 나누기 어려움. Ppang은 금액과 받는 사람만 입력해 USDC(달러 연동 스테이블코인)로 나눠 냄

- 필요한 입력을 '전체 금액·받는 사람' 2개로 축소, 정산 범위 유지, 규제 검토 후 수탁 → 비수탁 구조(앱이 사용자 돈을 맡지 않음)로 전환
- spec·개발 이관 문서(결정 기록 35건) 작성은 직접, 구현은 개발 AI 실행 1일 → 자동 테스트 282개 통과, Base Sepolia 테스트넷(실제 돈이 오가지 않는 시험망) 송금 검증
- 코드를 보지 않은 별도 검토 에이전트를 두어 로그 지갑 주소 노출 등 배포 전 위반 2건 발견, 배포 전 수정

`비공개 저장소 · 작업 중 · 코드는 이메일로 요청하면 화면으로 설명`

### 방식이 만들어진 과정

오래된 순서. 프로젝트마다 일하는 방식 하나를 바꿈.

- **[Fundit](https://github.com/errorinusermane/fundit-dapp)** · 2025 · 팀 · 담당: 스마트컨트랙트·백엔드·앱
  협업 체계 없이 기획 전 개발이 먼저 진행돼 팀의 서비스 이해가 갈림 → 기획 확정 후 개발로 순서 변경. BNB Chain 아이디어톤 대상
- **[SyncMe](https://github.com/ECC-2025-SyncMe/syncme-backend)** · 2025 · 팀 · 담당: 기획 단독·백엔드
  기획 의도 미공유로 개발 지연 → 이후 맥락을 담은 단일 문서로 공유
- **ProofIN** ([백엔드](https://github.com/ProofINer/proofin_backend) · MVP 이름 FairStay: [백엔드](https://github.com/FairStayer/fairstay_mvp_backend)) · 2025–2026 · 팀 · 담당: 아이디어·컨트랙트·백엔드·배포
  문제를 '보증금이 깎일까 봐 불안함'으로 재정의, 팀 목표 재정렬 후 회의 2~3시간 → 30분 이내. RISE 2025 우수상
- **자동화 시스템** · 2026 · 개인 · `비공개 · 이메일로 요청하면 화면으로 설명`
  백테스트 미래 데이터 참조로 실거래 손실 → 배포 전 검증 단계, 모의 실행(DRY_RUN), OIDC 배포 도입

Ppang에 네 가지 모두 적용: 기획 먼저, 단일 문서, 문제 재정의, 배포 전 검증.

</details>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/errorinusermane/errorinusermane/output/snake-dark.svg">
  <img alt="Contribution graph eaten by a snake" src="https://raw.githubusercontent.com/errorinusermane/errorinusermane/output/snake-light.svg">
</picture>
