# 👋 박현준 (Hyunjun Park)

**동국대학교 통계학과 · SWAI(인공지능) 연계전공**

데이터 분석과 머신러닝, 특히 *"성능 높은 모델보다 검증 가능한 모델"* 을 만드는 과정에 관심이 많습니다.

- 🎓 통계학 기반 · 데이터 분석 학회 활동 (BAF 26-1)
- 🔭 관심: 금융 데이터 · 불균형 분류 · 모델 해석(SHAP) · 시계열 검증
- ✍️ 기록: [velog @yusser123](https://velog.io/@yusser123)
- 📫 2022110461@dgu.ac.kr

---

## 📊 Featured Project

### ⭐ [Stablecoin Depegging Early Warning](https://github.com/hyunjun216/stablecoin-depegging-early-warning)
USDC·DAI 스테이블코인의 **디페깅 조기경보 모델** — BAF 26-1 팀 프로젝트

- **타깃 정의**: Typical Price + 2-of-3 필터로 일시적 노이즈를 걸러 지속적 디페깅만 라벨링
- **모델링**: 불균형 분류 문제로 접근, F2-score·Recall 중심 평가 → **USDC 0.906 / DAI 0.878**, 디페깅 포착률 100%
- **운영화**: 확률 예측을 정상·주의·경보 **3단계 조기경보**로 변환, SHAP으로 위험 요인 해석
- **담당**: 뉴스 텍스트 파생변수(키워드·LDA·FinBERT) 실험 및 기여도 검증 — 성능 미기여 변수를 제외하는 판단 경험
- 📝 [프로젝트 회고록 →](https://github.com/hyunjun216/stablecoin-depegging-early-warning/blob/main/docs/retrospective.md)

`Python` · `pandas` · `scikit-learn` · `XGBoost` · `LightGBM` · `SHAP` · `FinBERT`

---

## 🛠️ Other Work
> 비공개 저장소 (요청 시 공유 가능)

- **통통랜드 QR 주문 시스템** — 매장 테이블 QR 주문 · 주방 실시간 상태 동기화 웹앱 · `React` `Firestore`
- **개인 포털** — 일정·메모·대시보드 통합 개인 포털 · `Next.js` `Supabase` `Vercel`

---

## 🧰 Tech Stack

**Data / ML** — Python, pandas, NumPy, scikit-learn, XGBoost, LightGBM, SHAP, statsmodels
**Web** — TypeScript, React, Next.js, Supabase, Firestore
**Tools** — Git, Vercel
