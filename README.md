## 이정성 · Lee JeongSeong

백엔드에서 출발해 웹·앱·인프라까지 혼자 끝까지 만드는 풀스택 개발자입니다.
B2B 자동차 부품 유통 플랫폼에서 NestJS·React 서비스와 LLM 기반 업무 자동화를 개발하고 운영하고 있습니다.

- 블로그: [ainais.tistory.com](https://ainais.tistory.com/)
- 위치: Seongnam, Korea

### 대표 프로젝트

| 프로젝트 | 소개 | 역할 · 스택 |
|---|---|---|
| [**boxing-commerce**](https://github.com/ainais/boxing-commerce) (진행 중) | 여러 쇼핑몰의 복싱용품 가격을 비교하고 판매처로 연결하는 정보 제공 플랫폼(복싱의모든것). 주문·결제를 직접 처리하지 않는 다나와 스타일입니다. 현재 웹 프로토타입(mock 데이터)과 상품 조회 API를 만드는 단계이고, 상품 수집 배치와 웹·API 연동은 예정입니다. | 1인 개발 · Spring Boot(Java 21) · Next.js · PostgreSQL · Flyway · 모노레포 |
| [**routineq**](https://github.com/ainais/routineq) (진행 예정) | 원하는 공부 주제를 프롬프트로 적으면 AI가 매일 문제를 만들어 주는 자기개발 루틴 앱. 이전 버전에서 회원가입·이메일 인증·루틴 CRUD를 구현하고 Google Play 내부 테스트까지 배포했으며, 모노레포(api · web · mobile)로 새로 개발할 예정입니다. | 1인 개발 · NestJS(Prisma) · React · React Native(Expo) · PostgreSQL · GitHub Actions self-hosted runner · Docker |

이 외에 [url-shortener](https://github.com/ainais/url-shortener) — Spring Boot · Redis 클릭 카운터 flush · Base62 단축 코드.
프로젝트별 설계 결정은 각 저장소 README에 정리하고 있습니다.

### 기술 스택

- **Backend** — TypeScript/NestJS, Java/Spring Boot, Python/FastAPI, PostgreSQL, Redis
- **Frontend · App** — React, React Native(Expo), Flutter
- **AI** — LangChain, RAG, ReAct Agent, OpenAI API, YOLO
- **Infra** — AWS(EKS·EC2·S3), Docker, Kubernetes, Jenkins, GitHub Actions, Cloudflare Tunnel

### 일하는 방식

- 현업이 실제로 쓰는 흐름을 먼저 확인하고 화면·API로 옮깁니다.
- 자동화는 잘못 돌아갈 때 비용이 크므로 재시도·제한·멈출 지점을 먼저 설계합니다.
- 설계 근거와 의존 관계는 문서로 남깁니다.
