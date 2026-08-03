# 정희경 · Heegyeong Chung

**금융 정형·비정형 데이터 · 실서비스 AI 엔지니어링**
한양대학교 정보시스템학과(주전공) · 산업공학과(복수전공) · 4학년

측정되지 않던 것을 의사결정에 쓸 수 있는 수치로 바꾸는 일에 관심이 있습니다.
정형 데이터의 **설명가능성**과, 모델 성능이 실제 운영 판단으로 이어지는 조건을 주로 다룹니다.

`dipi1631@hanyang.ac.kr` · [LinkedIn](https://linkedin.com/in/hgchung04)

---

### 🔧 주요 저장소

**[SemanticCreditCard](https://github.com/hing9-9-9/SemanticCreditCard)** · `Python`
신용카드 거래 데이터 기반 이상거래 탐지 실험 파이프라인.
LR / RF / XGBoost / LightGBM을 시간 기반 분할로 비교하고, SHAP·LIME 기반 설명 안정성까지 산출합니다.
리샘플링 없이 PR-AUC · Precision@K · F2 임계 고정으로 극단적 클래스 불균형에 대응했습니다.

**[CHAI-Student/CRK-model-HG](https://github.com/CHAI-Student/CRK-model-HG)** · `Python` `FastAPI` `TensorRT`
무인 자판기의 취출 판정·정산 서비스 (산학과제, 주 저작 · 91커밋).
영상과 무게 센서만으로 결제 금액을 확정하는 온디바이스 시스템입니다.
레거시의 외부 계약을 보존한 채 판정 15전략 → 4경로로 재설계했고, 이중과금 불가 같은 불변식 17개를 타입으로 강제했습니다. pytest 406건 · CI 상시 운영.

**[yonggi-nael-kkang](https://github.com/hjo0225/yonggi-nael-kkang)** · `TypeScript` `React`
야구장 다회용기 인증 기반 친환경 직관 기록 플랫폼.
카카오임팩트 테크포임팩트 캠퍼스 **혁신기술상** 수상작입니다.

**[IS-NEW-WEB](https://github.com/hing9-9-9/IS-NEW-WEB)** · `TypeScript`
한양대학교 정보시스템학과 공식 홈페이지. 외주 시스템을 독자 재구축했습니다.

---

### 🧰 기술

```
Python      pandas · numpy · scipy · scikit-learn · Optuna · XGBoost · LightGBM · PyTorch
XAI         SHAP · LIME · Permutation Importance · ALE / PDP
Backend     FastAPI · pytest · ruff · GitHub Actions · uv · Linux
Edge/AI     Jetson Orin Nano · TensorRT · ffmpeg / NVDEC
Web         React · Next.js · Node.js · MongoDB
```
