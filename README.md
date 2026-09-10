# 유성민 | Java Backend Developer

요청이 몰리거나 외부 API가 실패해도 데이터가 틀어지지 않는 서비스를 만드는 데 관심이 있습니다.
Spring Boot 프로젝트를 직접 배포하며 동시성, 데이터 정합성, 장애 원인 분석과 운영 설정을 다뤘습니다.

<p>
  <img src="https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

## Featured Project

### [starrail-community](https://github.com/tms569111-wq/starrail-community) — 운영 환경까지 구축한 커뮤니티 서비스

붕괴: 스타레일 캐릭터를 버전·돌파 단계별로 평가하고 의견을 나누는 비공식 커뮤니티입니다. 기능 구현에 그치지 않고 외부 API 트래픽 보호, 동시 투표 정합성, 운영 배포와 장애 대응까지 검증했습니다.

- **Backend:** Java 21, Spring Boot 4.1, Spring Data JPA, Spring Security, Google OAuth 2.0
- **Data & Test:** MySQL 8.4, Flyway, Testcontainers, JUnit
- **Deploy:** Docker Compose, Caddy, AWS EC2·RDS
- 같은 UID 동시 요청 200개를 외부 API 호출 1회로 병합
- DB 유니크 제약과 MySQL upsert로 중복 투표 방지
- Enka timeout, MiHoMo fallback, MySQL 시간 정밀도 문제를 로그와 테스트로 추적
- GitHub Actions에서 전체 테스트, 운영 Compose·Caddy 검증, Docker 스모크 테스트 자동화

[서비스](https://37tiervote.com) · [문제 해결 기록](https://github.com/tms569111-wq/starrail-community/blob/master/docs/ENGINEERING_NOTES.md) · [CI](https://github.com/tms569111-wq/starrail-community/actions/workflows/ci.yml)

## Other Projects

- [news-fear-and-greed-index](https://github.com/tms569111-wq/news-fear-and-greed-index) — 한국어 금융 뉴스 감성과 주가 지표를 결합한 공포·탐욕지수 로컬 MVP
- [problem-solving-record](https://github.com/tms569111-wq/problem-solving-record) — Programmers·Baekjoon 알고리즘 풀이 기록

## Experience & Education

- **ADDD Co., Ltd. 인턴** · 데이터 전처리, API 기반 데이터 매핑 및 시각화 · 2023.12–2024.02
- **DGIST 컴퓨터공학 졸업** · 2026

## Certifications

정보처리기사 · 정보통신기사 · SQLD · ADsP · 한국사능력검정시험 1급 · TOEIC 865
