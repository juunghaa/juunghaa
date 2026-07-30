<h1 align="center">Hi, I'm Jungha Kim (김정하)</h1>
<p align="center">
디지털미디어에서 UI/UX와 웹 개발을 시작해, 지금은 소프트웨어학과에서 프론트엔드부터 백엔드·AI·IoT까지 직접 만들어보며 확장해가고 있습니다.<br/>
기획한 것이 실제로 동작하는 순간을 가장 좋아합니다.
</p>

<p align="center">
  <a href="mailto:YOUR_EMAIL@example.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://your-blog-url.com"><img src="https://img.shields.io/badge/Blog-000000?style=flat-square&logo=tistory&logoColor=white"/></a>
  <a href="https://github.com/juunghaa"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>
</p>

---

## About Me

- 디지털미디어학과 → 소프트웨어학과 전과. 프론트엔드로 시작해 백엔드·AI·IoT까지 직접 경험하며 성장 중
- 기획 → 개발 → 배포까지 전 과정을 스스로 진행하는 것을 좋아함 (AjouOrder, 팜므파탈 등)
- Node.js + Supabase 기반 백엔드, MQTT를 활용한 IoT 연동 서비스에 관심을 두고 있음
- 팀 프로젝트에서 일정 관리·갈등 조율 등 협업 경험 다수 보유

<br/>

## Tech Stack

**Backend**
<br/>
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Frontend**
<br/>
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**AI / ML**
<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

**IoT**
<br/>
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino/ESP32-00979D?style=flat-square&logo=arduino&logoColor=white)

**Database**
<br/>
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Deployment**
<br/>
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**External API / Auth**
<br/>
![Toss](https://img.shields.io/badge/Toss%20Payments-0064FF?style=flat-square&logo=toss&logoColor=white)
![OAuth](https://img.shields.io/badge/Social%20Login-4285F4?style=flat-square&logo=googleauthenticator&logoColor=white)

**Collaboration**
<br/>
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![SourceTree](https://img.shields.io/badge/SourceTree-0052CC?style=flat-square&logo=sourcetree&logoColor=white)

<br/>

## Featured Projects

### 팜므파탈 — 스마트팜 관리 플랫폼 `2026.03 ~ 2026.07`
> 기획 · 백엔드 · AI 모델 전담 (사실상 1인 풀스택) · 26-1 미디어프로젝트

홈가드닝·소규모 노지 관리 초보자를 위한 스마트팜 플랫폼입니다.  
Node.js + Supabase + MQTT 기반으로 서버를 구축하고, 룰엔진 기반 자동 제어, AI 식물 질병 진단, AI 챗봇, 일일 리포트, 위치 기반 날씨 API 연동을 담당했습니다.

`Node.js` `Supabase` `FastAPI` `MQTT` `Classification Model` `소셜 로그인`

**기술적 도전 & 해결**
- MQTT 프로토콜로 Arduino/ESP32를 인증 토큰 기반으로 연결하는 구조를 설계하며, IoT 기기 인증 흐름을 처음부터 직접 구현 — 토큰 발급·검증 로직과 연결 유지 방식을 반복 실험하며 해결
- AI 모델 개발 시 로컬 컴퓨터 사양 한계로 학습 이미지 수가 부족해 정확도가 아쉬웠음 → 추가 라벨링 방향 검토 및 YOLO 전환 가능성 분석, FastAPI 서버로 모델을 분리해 백엔드와 독립적으로 운영하는 구조로 개선

- [Backend](https://github.com/juunghaa/node-smartfarm-backend)
- [AI Server](https://github.com/juunghaa/python-smartfarm-ai-server)

<br/>

### AjouOrder — 교내 카페 사이렌 오더 웹 `2025.09 ~ 2025.12`
> 기획부터 배포까지 전 과정 직접 진행 · 실전웹서비스개발 수업 프로젝트

교내 카페의 혼잡 문제를 해결하기 위해 기획한 주문 관리 웹 서비스입니다.  
Node.js + React + Supabase로 구현하고, Toss 결제 API 연동, 주문 상태 관리, 예상 대기시간 기능을 개발했으며 Render(백엔드) / Vercel(프론트) 배포까지 진행했습니다.

`Node.js` `React` `Supabase` `Toss API` `Render` `Vercel`

**기술적 도전 & 해결**
- 카페 영업자와 일반 사용자의 화면 구조가 완전히 달라 관리자 대시보드 설계에 많은 고민이 필요했음 → 주문 상태(제작 중 / 완료 / 미완료)를 탭 형식으로 분리하고, 주문량 기반 복잡도·예상 대기시간 계산 로직을 직접 설계해 관리자 UX를 구조화
- Toss 결제 API 연동 시 모의 결제 흐름을 직접 구현하며 결제 상태와 주문 상태 간 동기화 처리

- [Web](https://github.com/juunghaa/ajou-order-web)
- [Server](https://github.com/juunghaa/ajou-order-server)

<br/>

### Grove — 경력·활동 자산화 플랫폼 `2025.06 ~ 2026.01`
> 프론트엔드 리드 개발자 (웹 전체 담당) · 25-2 파란학기

주니어 대상 경력·활동 자산화 플랫폼으로, React 기반 프론트엔드 전체를 담당했습니다.

`React`

**기술적 도전 & 해결**
- 백엔드와 로그인 API 연동 시 CORS 및 토큰 처리 방식 불일치로 인증 오류 발생 → 백엔드 개발자와 밤새 디버깅하며 API 명세를 재정의하고 해결. 프론트-백엔드 간 명확한 사전 명세의 중요성을 체감
- 팀원의 R&D 지연으로 전체 일정이 밀리는 상황 발생 → 직접 대화로 상황 파악 후 단계별 데드라인을 명확히 공유하며 기한 내 완료

- [Repository](https://github.com/juunghaa/react-porters-grove)

<br/>

### 롤러 협착 사고 예방 AI `2026.03 ~ 2026.07`
> 데이터 라벨링 · 기획 문서 · 웹 UI · 26-1 기업제안 파란학기

롤러에 손이 접근하면 이를 감지해 경보를 출력하는 산재 예방 시스템입니다.  
MediaPipe와 3D 좌표 변환을 활용해 손의 위치를 실시간으로 추적했습니다.

`MediaPipe` `3D 좌표 변환` `Python`

**기술적 도전 & 해결**
- 위험 구역 라벨링 기준을 팀 내에서 직접 정의하고, 기준 문서를 작성해 라벨링 일관성을 확보
- 3D 좌표 변환으로 카메라 시점과 실제 공간 좌표 간 오차를 보정하는 방식 적용
- 웹 UI에서 실시간 경보 출력 및 감지 상태 시각화 구현

<br/>

### Other Projects

- **전기차 충전소 안내 시스템** — DB 수업 프로젝트 (SQL/DB 설계 및 웹 개발)
- **노인 돌봄 스마트홈 시스템** — AI 입문 수업, AI 기반 스마트홈 구축
- **스마트홈 튜토리얼 영상** — 오픈소스웨어 수업, Home Assistant + MQTT 활용 · [Repository](https://github.com/juunghaa/foss-2025-1-final)

<br/>

## Education & Certifications

**학력**
- 아주대학교 소프트웨어학과 (디지털미디어학과 복수전공)
- 디지털미디어학과 → 소프트웨어학과 전과 (4학년)

**활동**
- AJOU-ASU pwn.college Winter Security Workshop (2026.01, 미국 아리조나주립대)
- 제4회 CO-Week Academy 수료 (한국연구재단, 2025.07)
- AWS Security Engineering on AWS 수료 (AWS T&C, 2025.11)
- 25-2 파란학기 Grove / 26-1 파란학기 팜므파탈·롤러협착 AI
- 2024 동계 모각소 (아주대학교 SW융합교육원)

**자격증**
- SQLD — SQL 개발자 (한국데이터산업진흥원, 2025.04)
- Google 애널리틱스 인증 GA4 (Google, 2025.06)
- ACP — Adobe Certified Professional, Premiere Pro (Adobe, 2025.07)
