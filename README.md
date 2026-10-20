<div align="center">

# Woo Sungmin / 우성민

### Frontend Developer & UI/UX Designer · Designing screens, shipping them as working apps

화면의 의도를 집요하게 묻고, 컴포넌트 단위로 정교하게 쪼개 **동작하는 화면**으로 증명합니다.

<a href="https://wwsm1230.notion.site"><img src="https://img.shields.io/badge/Portfolio-Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Notion Portfolio" /></a>

</div>

<br />

## About me

- 사용자가 기능을 헤매지 않도록 이동 규칙부터 정하고, 전 화면과 디자인 시스템을 직접 설계합니다.
- 설계한 화면을 React Native · React로 직접 구현해, 디자인과 코드가 어긋나지 않게 맞춥니다.
- 연타·재시도·네트워크 실패처럼 화면 뒤의 예외 상황까지 확인하며 완성도를 높입니다.

## Tech Stack

<div>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/styled--components-DB7093?style=flat-square&logo=styledcomponents&logoColor=white" alt="styled-components" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS" />
</div>
<br />
<div>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" alt="Notion" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
</div>

## What I focus on

| Area | Focus |
| --- | --- |
| UI/UX | 이동 규칙 설계, 온보딩부터 메인까지 전 화면 설계 |
| Design System | 타이포그래피 22종, 역할 기반 시맨틱 컬러 팔레트 |
| Client | React Native 앱, 다국어(8개 언어) · locale 정규화, 공통 API 헤더 |
| Reliability | 중복 요청 방지(idempotency key), 재시도 안전성, 캐시 재사용 |

## Pingdom — 핑덤

> **한국에서 갈 곳을 더 쉽게** · 방한 외국인의 헛걸음을 막고, 혜택 저장부터 예약·길찾기까지 한 번에 연결해 실제 매장으로 발길을 이끄는 위치 기반 오프라인 방문 전환 플랫폼

`2026.03 ~ 진행중` · 디자인 팀장(전 화면 설계 · 디자인 시스템) + 클라이언트 개발 · 총 7명(클라이언트 3 · 서버 3 · 네트워크 1)

<table>
<tr>
<td width="25%" valign="top">

**진입점 재설계**

버튼이 지도 위에 흩어진 구조를 하단 탭 바로 모으고, 지도는 첫 탭에 유지

`최상위 진입점 4개 → 1개`

</td>
<td width="25%" valign="top">

**중복 반영 방지**

연타·재시도에도 요청을 직렬 처리하고, 재시도 전 서버 상태를 다시 확인

`좋아요·댓글·쿠폰 발급 1회 반영`

</td>
<td width="25%" valign="top">

**집계 누락 · 중복 호출 차단**

`postId:placeId` 가드로 view 경유를 보장하고 장소 상세 캐시 재사용

`더블탭 → 정확히 1회`

</td>
<td width="25%" valign="top">

**출처 분리 모델링**

등록 장소(canonical ID)와 외부 장소(공급자 ID)의 선택 처리를 분기

`빈 화면 · 엉뚱한 상세 제거`

</td>
</tr>
</table>

## Team projects

Public collaboration repositories, ordered by my commit count.

1. [Pingdom App](https://github.com/Type-Nu11/pingdom-app) — React Native 사용자용 모바일 앱
2. [Pingdom Admin](https://github.com/Type-Nu11/pingdom-admin) — 서비스 운영 관리자 웹
3. [Pingdom Landing](https://github.com/Type-Nu11/pingdom-landing) — 서비스 소개 공식 랜딩페이지

## Other projects

- **슬릭** — 교내 기숙사 심야자습 관리 서비스 (React) · 디자인 팀장 겸 웹 개발 · 🏆 2025학년도 나르샤 프로젝트 3위
- [springboot26-2-3](https://github.com/wusm1230/springboot26-2-3) — Spring Boot learning project

## Awards

- 🥇 2025.07 · 교내 해커톤 금상 (1위)
- 🥉 2025.12 · 2025학년도 나르샤 프로젝트 3위
- 🗳️ 2026.06 ~ 2027.06 · 제 10기 전교학생회 당선
