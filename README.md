# 박현준 (Hyunjun Park)

데이터로 문제를 정의하고, 결과를 검증 가능한 형태로 만드는 데 관심이 있습니다.
*"성능 높은 모델보다 검증 가능한 모델"* 을 기준으로 분석합니다.

- 📫 parkhyunjun35@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/%ED%98%84%EC%A4%80-%EB%B0%95-178756420/)

---

## Featured Projects

### 뉴스 가격정보 신뢰성 검증 · 이과대학 경진대회
뉴스가 보도한 농수산물 가격이 공공 유통데이터와 맞는지 검증한 연구 (4인 팀)

- **문제**: 뉴스 속 가격정보를 공공 데이터와 대조한 연구가 거의 없어, 오용 정도를 처음으로 정량화
- **내 역할**: AI 1차 적격 판정을 사람이 검수하고 4인 판정 취합(770건 중 적격 304건), 오용 후보를 기사 원문·aT 가격과 대조해 오류 여부 판정
- **결과(팀)**: 기사 133건 중 5% 기준 불일치 12건(9.0%, 95% CI 5.2~15.1%), 재코딩 일치도 κ = 0.93
- 🔗 [Repository](https://github.com/hyunjun216/2026-science-contest-news-price)

### 동네 돌봄 지도 · 제14회 빅콘테스트 (AI데이터활용)
통신 유동인구·인구·건물·복지시설 데이터로 고립 위험 동네(250m 격자)를 찾고 방문 우선순위를 제안하는 AI 에이전트 (4인 팀)

- **내 역할**: EDA와 분석 엔진 담당. 위험 후보 탐색·4유형 분류 엔진 구현, 정답 데이터가 없는 상황에서 무작위 비교·기준 민감도로 성능 평가
- **결과**: 춘천 7,393칸 → 긴급방문 55칸, 강남 698칸 → 13칸으로 방문 범위 압축. 6개월 내내 위축된 칸이 무작위 대비 7~10배
- 🔗 [Repository](https://github.com/hyunjun216/2026-bigcontest-care-map) · [팀 레포](https://github.com/Jinx921/26-2_BITAminB5)

### 스테이블코인 디페깅 조기경보 · BAF 학회 프로젝트
USDC·DAI의 다음 날 디페깅을 예측하는 불균형 분류 모델 (3인 팀 + 개인 후속 연구)

- **내 역할**: 뉴스 텍스트 변수를 제안·생성하고 포함 전후 F2 비교로 제외 판단. 팀 종료 후 시계열 검증이 빠진 점을 보완하려고 시간 단위로 재구축해 walk-forward·위기 구간 홀드아웃으로 검증
- **결과**: 팀 XGBoost F2 USDC 0.906 / DAI 0.878 · 후속 SVB 위기 홀드아웃 AUC-PRC 0.88, 평온한 3년 동안 오경보 2건
- 🔗 [Repository](https://github.com/hyunjun216/stablecoin-depegging-early-warning)

---

## Projects

| 프로젝트 | 내용 | 역할 | 결과 | 링크 |
|---|---|---|---|---|
| 지방소멸대응기금 성과검증 | DID 성과검증 + 배분 추천 AI 에이전트 | 5인 팀 · EDA → 에이전트 백엔드 | 시제품 배포 | [Repo](https://github.com/hyunjun216/2026-ict-local-fund-agent) |
| 통통랜드 QR 주문 | 학과 축제 주점용 QR 주문·결제 웹서비스 | 개인 기획·개발·운영 | 축제 당일 유료 주문 124건 운영 | [Repo](https://github.com/hyunjun216/2026-festival-qr-order) |
| BAF 학회 홈페이지 | 기존 홈페이지 개편 + 관리자 페이지 | 개편·관리자 페이지 구축, 운영 | [dgubaf.com](https://dgubaf.com) 운영 중 | |
| 하리노트 | 강원 관광지 안전 점수 + 대체 코스 추천 | 2인 팀 · 모델 설계·데이터 분석 | 고지·오지형 132곳 발견, 등급 유지율 95.5% | [Repo](https://github.com/hyunjun216/2026-tourism-data-harinote) |
| 가락몰 실내 길찾기 | 가락몰 QR 실내 내비게이션 | 팀원 · 실내지도·경로 탐색 | 농수산 공모전 제출 | [Repo](https://github.com/hyunjun216/2026-garak-indoor-navigation) |
| 온사이드 아웃 | 청년 정서 모바일 웹앱 (오픈소스SW 프로젝트) | 3인 팀 · 기능 담당 | 정식 배포·홍보 중 | [Repo](https://github.com/hyunjun216/2026-oss-onside-out) |

---

## Education

- 동국대학교 통계학과 · AI소프트웨어(SWAI) 연계전공 (2022 입학, 재학 중)

---

## Awards

- 🏆 제21회 이과대학 재학생 연구 프로젝트 경진대회 대상 (2026, 뉴스 가격정보 신뢰성 검증)
- 🏆 BITAmin(데이터분석 학회) Conference 최우수상 (2026, 지방소멸대응기금 AI 코파일럿)

---

## Experience

- 연구 과제 보조 (2026, 통계학과 연구실): 에너지총조사 표본설계 보고서 집필, 실내공기질 측정자료 분석
- 데이터분석및시각화 과목 조교 (2026-2)
- 동국대 산학협력단 근로장학생 (2026-1): 산학지원 사무 보조
- 국가데이터처 통계정보서비스 모니터단 (2025.04 ~ 11)

---

## Activities

- BITAmin 데이터분석 학회 교육부 운영진 (2026 ~)
- BAF(비어플) 데이터분석 학회: 학회원 (2025-2 ~ 2026-1) → 총무부 운영진 (2026-2 ~)
- 연합 Codex 해커톤 운영 TF (2026)
- 통계학과 학생회: 부원 → 복지국장 → 총무국장 (예산 관리, 약 80명 규모 MT 기획)

---

## Certifications

- SQLD (2024)
- ADsP (2024)

---

## Tech Stack

**Data / ML**: Python (pandas, scikit-learn, XGBoost, LightGBM, SHAP), R, SQL
**Web**: React, Next.js, Supabase, Firebase
**Tools**: Git, Vercel
