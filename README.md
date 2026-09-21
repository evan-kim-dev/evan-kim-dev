# 👋 Hi, I'm Evan (kh.kim)

강원대학교 **정보통신공학과** · **스마트수소에너지 융합전공**  
웹·AI 서비스를 만들고, API·데이터·배포까지 이어서 붙입니다.

[![GitHub](https://img.shields.io/badge/GitHub-evan--kim--dev-181717?logo=github&logoColor=white)](https://github.com/evan-kim-dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)](https://aws.amazon.com/)
[![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)](https://flutter.dev/)

---

## 🛠️ Tech Stack

**Web / App**  
`TypeScript` · `Next.js` · `React` · `Flutter` · `Vite` · `Tailwind` · `Capacitor`

**Backend**  
`FastAPI` · `Next.js Route Handlers` · `Python` · `Prisma` · `Supabase` · `Convex`

**AI**  
`Gemini` · `OpenAI / OpenRouter` · `AWS Bedrock` (Converse · Guardrails · KB · Agent) · `LangChain` · `Chroma` · `RAG`

**Data / Cloud**  
`DynamoDB` · `SQLite` · `S3` · `EventBridge` · `ECS/ALB` · `TourAPI` · `Hotelbeds` · `Yahoo Finance`

**Deploy**  
`Vercel` · `Render` · `AWS` · `GitHub Actions` · `GitHub Pages`

---

## 🚀 Projects

### 🏥 Beddy — 장기입원 청소년 AI 정서 동반 + 보호자 요약 돌봄
[![Repo](https://img.shields.io/badge/GitHub-beddy-181717?logo=github)](https://github.com/evan-kim-dev/2026-aws-healthcare-ai-prompthon-beddy)
`Next.js` · `AWS Bedrock` · `Guardrails` · `RAG` · `Agent` · `DynamoDB` · `EventBridge` · `ECS`

2026 AWS 헬스케어 AI 프롬프톤 출품작. 병원·장기입원 청소년이 쓰는 정서 동반 AI와, 보호자에게는 **원문 없이 요약만** 보여주는 돌봄 서비스입니다.

- **Child**: 페르소나·SSE 채팅·가드레일·위기 UI, 감정정원·소원나무·모험·일기  
- **Dawn Mission Agent**: tool-use로 일과·미션 처리, Bridge로 보호자용 요약 KB 적재  
- **Guardian**: 연동·공감/Q&A RAG·편지(원문 비공개), 퇴원 스토리북·Polly 나레이션  
- **Infra**: DynamoDB·S3·EventBridge 일일 크론·ECS Fargate·ALB·관측/배포 스크립트  

🔗 [Repository](https://github.com/evan-kim-dev/2026-aws-healthcare-ai-prompthon-beddy)

---

### ✈️ Met U — 예산 기반 AI 여행 플래너 (Web)
[![Repo](https://img.shields.io/badge/GitHub-MetU-181717?logo=github)](https://github.com/evan-kim-dev/MetU)
[![Demo](https://img.shields.io/badge/Demo-Vercel-000000?logo=vercel)](https://met-u.vercel.app)
`Next.js` · `FastAPI` · `Supabase` · `OpenRouter/OpenAI` · `Hotelbeds` · `TourAPI`

예산·인원·일정·스타일 4단 온보딩 후 AI가 예산을 배분하고, 항공·숙소·환율·딜 추천 API로 실제 상품을 붙이는 풀스택 여행 서비스입니다.

- 여행 CRUD · 공유 토큰 · 체크리스트  
- board / 파티챗 / DM / 친구 · 알림 · 카카오 로그인 · PWA  
- FastAPI BFF + Supabase Auth/DB/Realtime  
- 배포: Vercel (+ Render)  

🔗 [Repository](https://github.com/evan-kim-dev/MetU) · [Live Demo](https://met-u.vercel.app)

#### 📱 Met-U — 동일 제품 Flutter 클라이언트
[![Repo](https://img.shields.io/badge/GitHub-Met--U-181717?logo=github)](https://github.com/evan-kim-dev/Met-U)
`Flutter` · `Provider` · `Dio` · `OAuth`

같은 Met U의 모바일 클라. 온보딩→AI 요약/배분, 항공·숙소·맛집 검색, 서류/비자 체크리스트, 커뮤니티·채팅, 예산 관리, API/AI 키 설정 화면까지 포함합니다.

🔗 [Repository](https://github.com/evan-kim-dev/Met-U)

---

### 🗺️ potato — 강원 로컬 AI 관광 큐레이션 (강원 온도 / ON道)
[![Repo](https://img.shields.io/badge/GitHub-potato-181717?logo=github)](https://github.com/evan-kim-dev/potato)
[![Demo](https://img.shields.io/badge/Demo-Vercel-000000?logo=vercel)](https://potato-peach.vercel.app)
`Next.js` · `TourAPI` · `Gemini` · `Kakao/Leaflet` · `Python` sync

인구감소·내륙 권역을 염두에 둔 로컬 관광 앱. 지도·혼잡 배너·QuietGems, Gemini 스팟 챗·코스 플랜, 날씨/해수욕장/예보, 축제·지역화폐·패스포트 보드를 제공합니다. TourAPI·KOMSCO JSON을 SSOT로 두고 GitHub Actions로 동기화합니다.

🔗 [Repository](https://github.com/evan-kim-dev/potato) · [Live Demo](https://potato-peach.vercel.app)

---

### ⚖️ AI Ethics Evaluation — 생성형 AI 윤리 위험도 비교 연구 MVP
[![Repo](https://img.shields.io/badge/GitHub-ai--ethics--evaluation-181717?logo=github)](https://github.com/evan-kim-dev/ai-ethics-evaluation)
`FastAPI` · `React/Vite` · `SQLite` · `Gemini/OpenAI` · LLM-as-Judge

동일 질문에 **baseline / AI윤리 / 윤리+불교** 3조건으로 답을 만든 뒤, E1–N2·B1–B3 루브릭으로 S/R 점수를 내고 사람 평가(HITL)·대시보드·CSV까지 돌리는 실험 도구입니다. 실험 설계·한국 AI윤리원칙·루브릭 문서가 docs에 있습니다.

🔗 [Repository](https://github.com/evan-kim-dev/ai-ethics-evaluation)

---

### 🛡️ senior_safe_portal — 시니어 디지털 보안관
[![Repo](https://img.shields.io/badge/GitHub-senior--safe--portal-181717?logo=github)](https://github.com/evan-kim-dev/senior_safe_portal)
[![Demo](https://img.shields.io/badge/Demo-GitHub%20Pages-222222?logo=githubpages)](https://rlarlgns-evan.github.io/senior_safe_portal/)
`HTML/CSS/JS` · `Supabase Auth + Edge Functions` · `Gemini`

의심 링크/검색어를 Edge Function으로 분석해 안전·위험을 판별하고, 챗봇 **단디**·유튜브/뉴스/복지 콘텐츠·자유게시판·날씨까지 묶은 시니어용 포털입니다. CSP·sanitize 등 보안 유틸과 GitHub Actions 피드 갱신이 있습니다.

🔗 [Repository](https://github.com/evan-kim-dev/senior_safe_portal) · [Live Demo](https://rlarlgns-evan.github.io/senior_safe_portal/)

---

### 🪷 Kleshas — 불교 번뇌 테마 멘탈케어
[![Repo](https://img.shields.io/badge/GitHub-Kleshas-181717?logo=github)](https://github.com/evan-kim-dev/Kleshas)
`Next.js` · `Prisma/SQLite` · `FastAPI` · `LangChain` · `Chroma` · `Capacitor`

경전 RAG 기반 ‘사이버 스님’ 챗, 일일 괘시/KarmaCard, 목탁 수행, 카르마·마인드풀니스 아카이브 차트, 연꽃 성장·앰비언트 오디오가 있는 멘탈케어 MVP입니다. Capacitor로 앱 패키징까지 되어 있습니다.

🔗 [Repository](https://github.com/evan-kim-dev/Kleshas)

---

### 📈 market-news — 한·미 시장 브리핑 대시보드
[![Repo](https://img.shields.io/badge/GitHub-market--news-181717?logo=github)](https://github.com/evan-kim-dev/market-news)
`Next.js` · `Convex` · `Gemini` · `yahoo-finance2` · RSS · TradingView

S&P / NASDAQ / Dow / KOSPI / KOSDAQ 지표와 Google News RSS를 모아 Gemini로 일일 브리핑·takeaways를 만들고, 그 위에서 애널리스트 챗을 돌립니다. TradingView 차트·캘린더·히트맵, cron 자동 수집이 있습니다.

🔗 [Repository](https://github.com/evan-kim-dev/market-news)

---

### 🧳 travel — Met U 축소/초기 버전
[![Repo](https://img.shields.io/badge/GitHub-travel-181717?logo=github)](https://github.com/evan-kim-dev/travel)
[![Demo](https://img.shields.io/badge/Demo-Vercel-000000?logo=vercel)](https://travel-evan-s.vercel.app)
`Next.js` · `Supabase` · `FastAPI` · `Hotelbeds` · `TourAPI`

Met U와 같은 예산 AI 여행 웹의 축소·초기 변형입니다. 온보딩 4스텝·trips/checklist/budget·항공/숙소/FX/딜 API·카카오 로그인은 있으나, board·친구·알림·지도 등 Met U의 소셜 레이어는 빠져 있습니다.

🔗 [Repository](https://github.com/evan-kim-dev/travel) · [Live Demo](https://travel-evan-s.vercel.app)

---

## 📫 Contact

- GitHub: [@evan-kim-dev](https://github.com/evan-kim-dev)

---

<sub>포트폴리오 우선순위(코드 기준): Beddy → Met U → potato → AI Ethics → senior_safe_portal</sub>
