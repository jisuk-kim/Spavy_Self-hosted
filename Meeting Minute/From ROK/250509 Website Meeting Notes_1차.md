---
title: Untitled

---

디자인 고려사항
사용자는 제품의 랜딩 페이지 디자인에 대해 이야기하고 있어요. 중요한 부분은 첫 화면 훅과 신뢰 구축, 그리고 "왜 우리를 선택해야 하는가" 섹션으로의 흐름이에요. 그들은 많은 기능을 방해하지 않으면서도 동적 트리 내비게이션을 강조하려고 하고, Dropbox나 OneDrive와 같은 익숙한 브랜드를 참고해 신뢰성을 높이려 해요. 또한 트리리스트 뷰와 360도 뷰, 비디오 등을 활용한 특징을 강조할 계획이라네요.
구조적인 요약
사용자는 랜딩 페이지 디자인을 위한 간결성을 원하며, 스크롤을 최소화하려고 해요. 우리는 이를 바탕으로 전체적인 구조를 만들 계획이에요. 랜딩 페이지의 목적과 구조의 고수준 개요부터 시작하여, 트리 구조로 각 섹션의 내용을 요약하고, 테이블로 각 섹션의 목표와 요소들을 정리할 거예요. 마지막으로, 키워드, 행동 항목, 우려 사항, 질문 등을 추출할 거예요.
37초 동안 생각함
⚡️ 하이-레벨 개요
목표: 방문자가 1 초 이내 / 첫 스크롤 구간(히어로 섹션)에서 “끌림 + 신뢰”를 느끼게 하고, 최소한 Feature → Why-Choose-Us 섹션까지 자연스럽게 스크롤하도록 유도
핵심 메시지: “우리는 공간정보에 특화된 Dropbox/OneDrive입니다 — 그러나 동적 트리·리스트·뷰로 기존 스태틱 폴더 한계를 넘어섭니다”
콘텐츠 흐름:
Hero(후킹 + 신뢰) ⭢
Feature 3종(차별화) ⭢
Why-Choose-Us(셀프 호스팅·가성비·검증) ⭢
FAQ(의구심 해소)
스크롤 길이를 최대한 짧게 유지하여 “어, 벌써 끝?” 느낌
🌲 트리 구조 요약
Landing-Page
├─ 1. Hero ❶ Hook & Trust
│   ├─ Rotating tagline: “Dropbox → Box → OneDrive… for spatial data”
│   │   └─ 애니메이션: 노란 하이라이트, 볼드, 0.5 s 간격 플립
│   ├─ Sub-copy: “Self-host your files & 3D scenes in minutes”
│   ├─ Primary CTA: “무료 체험” / Secondary CTA: “데모 영상”
│   └─ Visual: 심플 로고 + 미니 드론/포인트클라우드 일러스트
│
├─ 2. Feature Section (3 Highlights)
│   ├─ F1. Tree-List View (Dynamic Graph Navigation)
│   │   ├─ 차별점: 사용자 맞춤형 동적 트리 vs. 기존 스태틱 폴더
│   │   └─ 비유: “폴더 구조를 개인화 가능한 그래프 지도로 바꿨습니다”
│   ├─ F2. List / Package Sharing
│   │   ├─ 파일·폴더 묶어 전송 → “Web-hard / Dropbox Transfer” 경험
│   │   └─ 동기화 외에도 개별 파일 첨부 지원
│   └─ F3. Spatial View (Busan Scene Demo)
│       ├─ 좌: 노드된 파일리스트가 순차적으로 로드되는 영상
│       ├─ 우상단: 드론 4K 영상 (부산 영화의전당) 자동 재생
│       └─ 우하단: 360° 파노라마 뷰어 인터랙션 클립
│
├─ 3. Why-Choose-Us
│   ├─ Self-Hosted & Secure (온-프레미스 배포 가능)
│   ├─ 4 년간 검증된 대용량/고성능 엔진
│   └─ Pricing = 동시접속자 수 기반 · 예측가능한 총소유비용
│
├─ 4. FAQ
│   ├─ “Dropbox랑 뭐가 다르죠?”  
│   ├─ “설치는 어렵지 않나요? (5분 도커 배포)”  
│   ├─ “GIS·BIM 포맷도 지원하나요?”  
│   └─ “온프레미스 보안 감사 기준은?”  
└─ 5. Footer (간략 팀 소개·연락처·GitHub 링크)
📋 섹션별 상세 테이블
섹션	UX 목표	주요 요소	콘텐츠 톤
Hero	1 초 내 이해·신뢰	로고, 회전 태그라인, CTA 2개	심플·대담·친숙
Feature 3종	차별화 포인트 각인	트리-리스트, 패키지 전송, 부산 3-뷰 씬	제품 데모 중심
Why-Choose-Us	구매 고려 트리거	셀프 호스팅, 성능, 가격	신뢰·데이터·명료
FAQ	의구심 해소·SEO	6–8개 핵심 질문	친근·간결
🔑 키워드 & 키프레이즈
동적 트리 내비게이션 · 퍼스널라이즈드 그래프
패키지 리스트 / Web-hard / Dropbox Transfer
공간정보 전용 드랍박스
셀프 호스팅 · 온-프레미스 보안
부산 드론 영상 + 360 뷰
4 년간 개발 · 대용량 고성능
동접자 기반 가격 모델
✅ 액션 아이템
Hero 카피 확정 및 하이라이트 애니메이션 스펙 - 0.5 s 플립, 노란 배경
부산 씬 자료 확보: 드론 4K, 360 파노라마, 포인트클라우드
F1-F3 데모 영상 3-분할 합성 or 순차 로딩 방식 결정
Why-Choose-Us 섹션: Self-host 설명 · 가격표(동접자 기준) 문안 작성
FAQ 8문항 초안 → 기술·영업팀 검토
전체 스크롤 길이❬<2.5-viewport❭ 유지 테스트
⚠️ 우려 사항
부산 씬이 문서/테이블 뷰 기능을 가리지 않도록 균형 필요
사용자 리뷰 부재 → 대체 신뢰 요소(언론 로고, 파트너사) 준비
라이선스/저작권: 드론·360 영상 상업적 사용 가능 여부 확인
페이지 로딩 성능: 고화질 영상 및 포인트클라우드 지연 위험
❓ 남은 질문
부산 씬 확정인가요? 아니면 필바라(광산) 대안도 비교하시겠습니까?
Feature 3종 외에 테이블·문서 뷰를 최소 노출이라도 넣을지?
가격 공개 범위: 랜딩에 즉시 노출 vs. 컨택 유도 중 어떤 방향?
FAQ 우선순위나 추가 문의 항목이 더 있을까요?
 
Summarizing website design for SPAVY
사용자는 SPAVY 제품에 대한 웹사이트 디자인 계획을 계속 논의하고 있습니다. 그들은 구조적이고 포괄적인 요약을 원하면서, FAQ 중심 접근법, 중첩 페이지 계획, 제품 페이지 구조, 사용 사례 등을 포함하고 있습니다. 우리는 그들의 콘텐츠를 분석하여 높은 수준의 개요와 세부 사항을 제공해야 합니다. 이 요약에는 중요 키워드, 동작 항목, 우려 사항 및 질문을 포함한 트리 구조 또는 테이블 형식으로 제공할 예정입니다. 이번에는 한국어로 일관되게 표현하겠습니다.
13초 동안 생각함
🏁 하이-레벨 개요
핵심 전략
랜딩 페이지(1 스크롤) → “초집중 후킹 + 최소 정보”
FAQ → 방문자가 궁금해 하는 모든 것을 스토리텔링으로 해소
Nested Pages → Product·Industry (Use-case)·Studio 등 세부 콘텐츠로 분기
이유
기능이 단순(트리·리스트·브라우저)하고 컴피규어러블 특성이 강하므로,

• 랜딩에서 복잡한 설명을 걷어내고

• FAQ·하위 페이지에서 깊이 + 신뢰를 동시에 전달
🌳 정보 구조(Tree Structure)
SPAVY-Site
├─ Landing Page (Hook & Trust)
│   ├─ Hero: “Self-hosted Dropbox for Spatial Data”
│   ├─ CTA: 무료 체험 / 데모 영상
│   └─ Quick-Jump Link → FAQ
│
├─ FAQ  (Story-Driven Answers)
│   ├─ 제품 목표·기원 / 왜 공간정보?
│   ├─ 대상 산업·사용처
│   ├─ File Interoperability 범위
│   ├─ 가격 & 동접자 산정 기준
│   ├─ Self-Hosted 이유·보안
│   └─ 투자·로드맵·기술 스택
│
├─ Product Pages
│   ├─ Tree-View
│   ├─ List / Package-Share
│   ├─ Browser (Scene·360·Video)
│   └─ Studio (Configurable Toolkit)
│
├─ Industry / Use-Case Pages
│   ├─ **SNAC**  (Survey·Nav·AEC·Construction)
│   ├─ **Inspection**
│   ├─ **Mission / Drone Ops**
│   └─ …추가 ① Mining ② Digital Twins 등
│
└─ Resources
    ├─ 블로그 / 릴리즈 노트
    ├─ 가격표 (동접자-Tier)
    └─ 문서·API 가이드
📋 섹션별 요약 테이블
구역	메시지 포커스	콘텐츠 예시	목적
Hero	“왜 들어왔는지” 즉시 각인	로테이팅 슬로건·CTA	클릭·스크롤 유도
FAQ	제품·회사 ‘모든’ 질문 해소	8-12 문항, 스토리텔링식 답변	신뢰·SEO
Product	3 핵심 기능 = 트리·리스트·브라우저	GIF·Demo Clip 각 10-15 초	구체 가치 이해
Industry	실제 사용 시나리오	산업별 썸네일, 2-3 통계·결과	상황 공감·전환
Resource	깊이 정보	가격표, 보안 문서, API 링크	실 구매 단계 지원
🗝️ Keywords & Key Phrases
동적 트리·그래프 내비게이션 / 패키지 공유 / 공간정보 전용 / 셀프 호스팅 / 컴피규어러블 툴킷 / 동접자 기반 가격 / SNAC·Inspection·Mission use-case
✅ Action Items
FAQ 초안 작성 → 과거 전시·부스 Q&A 리뷰 반영
Industry taxonomy 확정: 명칭(Solution vs Use-Case vs Industry) 결정
Product 페이지 데모:
트리 → 폴더→그래프 스냅 GIF
리스트 → 패키지 URL 생성 GIF
브라우저 → 부산 씬 3-분할 영상 제작
Hero 애니메이션 스펙(로테이팅 키워드·색상·주기) 문서화
Naming 가이드: Sync / Studio / Connect 등 카테고리 라벨 검토
영상·이미지 라이선스 체크: 드론·360 소스 상업 사용 가능 여부
⚠️ Concerns & Risks
랜딩 정보 과소(“뭐 하는 제품?” 즉시 파악 실패) ↔ 과다(스크롤 피로) 균형
Industry 페이지 수 ↑ → 유지보수 비용·중복 리스크
고해상도 데모 자산 → 초기 로딩 지연 가능성
가격 공개 범위 결정(즉시 노출 vs 문의 유도) 미정
❓ Open Questions
Industry 분류명을 무엇으로 할까요? (Solution / Use-Case / Industry)
Hero 카피: “Dropbox for Spatial Data” 그대로 vs 국문 재해석?
가격표를 랜딩에 바로 공개할지, FAQ / Resources에서 분리할지?
Studio(고급 편집 도구) → 1차 공개범위·이름 확정 필요
🔍 핵심 요약 한 줄
“랜딩 = 후킹·신뢰, 나머지 깊이 = FAQ + Nested Pages” — 기능이 단순·컴피규어러블한 만큼 ‘적게 보여주고 궁금증은 FAQ·하위 페이지에서 해소’ 가 최적 동선입니다.
 
 
 