# OGAM TRIP GEO LAB 실험 기록

## Baseline — 2026-09-29

### 공개 URL

https://ogamtrip-geo-lab.vercel.app/

### 현재 목적

GPTers GEO·SEO 스터디에서 검색 및 AI 노출 변화를 직접 실험하기 위한 사이트.

### 현재 페이지

* 주제: 간사이공항에서 난바까지 가는 방법
* Title: 간사이공항에서 난바까지 가는 방법 | OGAM TRIP GEO LAB
* H1: 간사이공항에서 난바까지 어떻게 가나요?
* H2:
  * 빠르고 편하게 가려면
  * 비용을 아끼고 싶다면

### 현재 기술 구조

* HTML
* CSS
* GitHub
* Vercel

### Baseline 당시 아직 적용하지 않은 항목

* Search Console
* Analytics
* sitemap.xml
* robots.txt
* canonical
* structured data
* GEO 성과 측정

### 실험 원칙

한 번에 하나씩 수정하고,
수정 전후를 기록한 뒤 결과를 비교한다.

## Experiment 001 — Meta description 수정

### 날짜

2026-09-29

### 변경 전

간사이공항에서 난바까지 가는 간단한 방법을 소개하는 GEO·SEO 학습용 여행 정보 페이지입니다.

### 변경 후

간사이공항에서 난바까지 가는 방법을 라피트와 공항급행 기준으로 간단히 비교한 오사카 교통 정보입니다.

### 변경 이유

사이트의 실험 목적보다 실제 검색자가 찾는 페이지 내용을 설명하도록 수정.

### 상태

- index.html 로컬 수정 완료
- GitHub 반영 완료
- Vercel 배포 완료
- 공개 사이트 반영 확인 완료

## Experiment 002 — Canonical 추가

### 날짜

2026-09-29

### 변경 내용

`<link rel="canonical" href="https://ogamtrip-geo-lab.vercel.app/">`

### 변경 이유

Vercel에서 여러 주소로 같은 페이지에 접근할 수 있어도,
검색엔진에게 이 페이지의 대표 URL이
https://ogamtrip-geo-lab.vercel.app/
임을 알려주기 위해 추가.

### 상태

- index.html 로컬 수정 완료
- GitHub 반영 완료
- Vercel 배포 완료
- 공개 사이트 반영 확인 완료

## Study-ready baseline v1.0 — 2026-10-01

이번 변경은 한 요소씩 측정한 통제 실험이 아니라,
GPTers GEO·SEO 스터디 참여를 위한 사이트 기반 구축 작업이다.

### 추가/개선 항목

- 홈 구조 개편
- 독립 여행 정보 페이지 생성
- About 페이지 생성
- 내부 링크
- Open Graph
- 기본 구조화 데이터
- robots.txt
- sitemap.xml
- 모바일·접근성 개선
- 내부 기록 Vercel 배포 제외
