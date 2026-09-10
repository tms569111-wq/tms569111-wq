# 유성민 | Java·Spring 백엔드 개발자

Java와 Spring Boot로 백엔드 서비스를 만들고 있습니다.
개인 프로젝트를 AWS에 배포해 운영하며 동시 요청, 데이터 정합성, 외부 API 장애를 직접 다뤘습니다.

<p>
  <img src="https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java 21" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

## 대표 프로젝트

### [starrail-community](https://github.com/tms569111-wq/starrail-community) — 붕스청문회

캐릭터 티어 투표와 의견 공유 기능을 제공하는 커뮤니티입니다. 기획, 개발, 테스트, 배포까지 혼자 진행했습니다.

`Java 21` · `Spring Boot 4.1` · `MySQL 8.4` · `Docker Compose` · `AWS EC2/RDS`

- 같은 UID 동시 요청 200건 → 외부 API 호출 1회
- 동시 투표 중복 문제 → DB 유니크 제약과 MySQL upsert
- 외부 API 장애 → fallback, circuit breaker, 요청 수 제한
- 배포 전 검증 → GitHub Actions와 Docker 스모크 테스트

[서비스](https://37tiervote.com) · [문제 해결 기록](https://github.com/tms569111-wq/starrail-community/blob/master/docs/ENGINEERING_NOTES.md) · [CI](https://github.com/tms569111-wq/starrail-community/actions/workflows/ci.yml)

## 다른 프로젝트

- [news-fear-and-greed-index](https://github.com/tms569111-wq/news-fear-and-greed-index) — 한국어 금융 뉴스 감성과 주가 지표를 결합한 공포·탐욕지수 로컬 MVP
- [problem-solving-record](https://github.com/tms569111-wq/problem-solving-record) — Programmers·Baekjoon 알고리즘 풀이 기록

## 경험 및 학력

- **ADDD Co., Ltd. 인턴** · 데이터 전처리, API 기반 데이터 매핑 및 시각화 · 2023.12–2024.02
- **DGIST 컴퓨터공학 졸업** · 2026

## 자격 및 어학

정보처리기사 · 정보통신기사 · SQLD · ADsP · 한국사능력검정시험 1급 · TOEIC 865
