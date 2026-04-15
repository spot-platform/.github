# 🔵 Spot - 취미 공유 강사 플랫폼
### 취미로 연결되는 사람들
프로 강사가 아닌 **또래가 호스트**가 되어 취미를 나누는 마켓플레이스입니다.
<br>
"수원 화서동 기타 같이 쳐볼 분, 1:1 5천원, 저희 집 거실에서 해요" 같은 **소규모 모임**을 만들고 참여할 수 있습니다.
<br>
**합성 콘텐츠 파이프라인**이 가상에서 시뮬레이션하여, 참여를 유도합니다.

## FE Stacks
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
<br>
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)
![Kakao Map](https://img.shields.io/badge/Kakao_Map_API-FFCD00?style=flat-square&logo=kakao&logoColor=black)

## BE Stacks
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

## Context Builder Stacks
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja-B41717?style=flat-square&logo=jinja&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

## Agents

[🏗️ infra-architect](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/infra-architect.md) — Docker Compose + FastAPI + Celery 뼈대 세우는 사람
[🗄️ schema-designer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/schema-designer.md) — 테이블 9개의 DDL·모델·마이그레이션 장인
[🔍 collector-engineer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/collector-engineer.md) — 카카오 API를 때려서 장소 데이터를 긁어오는 사람
[⚙️ processor-engineer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/processor-engineer.md) — 정규화부터 페르소나 가중치까지 데이터를 끝까지 끌고 가는 사람
[🧪 integration-qa](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/integration-qa.md) — admin API 라우팅 + 경계면 교차 검증으로 틈새를 잡는 사람

[🧱 sim-infra-architect](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/sim-infra-architect.md) — 시뮬레이터 디렉토리 스캐폴딩 담당
[📦 sim-model-designer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/sim-model-designer.md) — AgentState·Spot·EventLog 데이터 모델 + 감쇠 함수
[💡 sim-engine-engineer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/sim-engine-engineer.md) — tick 루프·행동 결정·lifecycle·정산, 시뮬레이터의 심장
[🔌 sim-data-integrator](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/sim-data-integrator.md) — local-context-builder 산출물을 시뮬레이터에 먹이는 브리지
[📊 sim-analyst-qa](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/sim-analyst-qa.md) — Phase 게이트키퍼, 로그 분포가 이상하면 다음 Phase 차단

[🏭 pipeline-infra-architect](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/pipeline-infra-architect.md) — 파이프라인 뼈대 + DB 6테이블 + 10개 job 진입점
[🌉 codex-bridge-engineer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/codex-bridge-engineer.md) — LLM 호출의 유일한 문, codex exec CLI subprocess 전담
[✏️ content-generator-engineer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/content-generator-engineer.md) — 5종 콘텐츠를 후보 2개씩 생성하는 프롬프트 장인
[🛡️ validator-engineer](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/validator-engineer.md) — 6-Layer 검증 + 생성→검증→재시도 루프 조립
[🔬 pipeline-qa](https://github.com/spot-platform/contextBuilder/blob/master/.claude/agents/pipeline-qa.md) — golden 샘플로 end-to-end 돌리고 §14 지표 달성 여부 판정

## Team
<table>
  <tr>
    <td align="center"><a href="https://github.com/username"><img src="https://github.com/username.png?size=100" width="100"/></a></td>
    <td align="center"><a href="https://github.com/username"><img src="https://github.com/username.png?size=100" width="100"/></a></td>
    <td align="center"><a href="https://github.com/username"><img src="https://github.com/username.png?size=100" width="100"/></a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/username">이름</a></td>
    <td align="center"><a href="https://github.com/username">이름</a></td>
    <td align="center"><a href="https://github.com/username">이름</a></td>
  </tr>
</table>
