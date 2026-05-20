---
title: "AI/ML 트렌드 & 경제 뉴스 다이제스트 - 2026년 05월 20일"
date: 2026-05-20T00:05:22+09:00
categories: ["뉴스", "AI/ML"]
tags: ["LLM", "arXiv", "Reinforcement Learning", "희소행렬", "그래프 정책 최적화", "채움 감소"]
draft: false
cover:
  image: "https://images.unsplash.com/photo-1740137744221-f39d89aa299d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5NTUyOTJ8MHwxfHNlYXJjaHwxfHxBZ2VudCUyMEJhemFhciUyMEVuYWJsaW5nfGVufDB8MHx8fDE3NzkyMDQ3MTJ8MA&ixlib=rb-4.1.0&q=80&w=1080"
  alt: "Photo by Markus Winkler on Unsplash"
  caption: "Photo by Markus Winkler (https://unsplash.com/@markuswinkler) on Unsplash (https://unsplash.com/photos/a-sign-that-says-old-bazzar-on-the-side-of-a-building-E7a3YRupk4I)"
  relative: false
---

> AI/ML 트렌드 10건 · 해외경제 3건 · 국내경제 3건

## 🤖 LLM / AI 최신 뉴스

### 1. Learning Fill-in Reduction Ordering via Graph Policy Optimization for Sparse Matrices

새로운 연구는 희소 행렬의 패턴을 고려한 그래프 정책 최적화 방법을 제안하여 인수 분해 과정에서 발생하는 채움(fill-in)을 줄이는 최적 순서를 학습한다. 기존 강화학습 방법들이 전역적 채움을 무시하거나 로컬 정확한 피드백을 제공하지 못하는 한계를 극복했다.

- **출처**: arxiv cs lg
- **링크**: [Learning Fill-in Reduction Ordering via Graph Poli](https://arxiv.org/abs/2605.17362)

---

### 2. Agent Bazaar: Enabling Economic Alignment in Multi-Agent Marketplaces

LLM 기반의 자율 경제 에이전트가 시장에 진입하면서 발생할 수 있는 시스템적 위험을 분석한 연구. 에이전트들이 시장에 참여하며 집단적 행동이 시장 변동성을 키우고 사기 행위를 은폐할 수 있음을 지적하고, 'Agent Bazaar'라는 다중 에이전트 시뮬레이션 프레임워크를 제안해 경제적 정렬(Economic Alignment) 평가를 시도한다.

- **출처**: arxiv cs lg
- **링크**: [Agent Bazaar: Enabling Economic Alignment in Multi](https://arxiv.org/abs/2605.17698)

---

### 3. Memisis: Orchestrating and Evaluating Synthetic Data for Tabular Health Datasets

Memisis는 의료 테이블 데이터용 합성 데이터를 오케스트레이션하고 평가하는 도구입니다. 기존 합성 데이터 도구와 대규모 언어 모델, 최첨단 평가 지표를 활용하여 프라이버시, 유틸리티, 공정성을 동시에 고려합니다. 하류 예측 작업과 임상 의사결정 지원을 위해 고품질 데이터 가용성 확보를 목표로 합니다.

- **출처**: arxiv cs lg
- **링크**: [Memisis: Orchestrating and Evaluating Synthetic Da](https://arxiv.org/abs/2605.17758)

---

### 4. Revisiting the Adam-SGD Gap in LLM Pre-Training: The Role of Large Effective Learning Rates

LLM 사전학습에서 SGD가 Adam보다 성능이 떨어지는 이유를 분석한 연구. SGD가 Adam과 같은 큰 유효 학습률을 유지하지 못하기 때문이라는 점을 이론적·경험적으로 규명했다. 학습이 작은 그래디언트 노름과 큰 가중치-그래디언트 비율로 특징지어지는 것이 핵심 원인이다.

- **출처**: arxiv cs lg
- **링크**: [Revisiting the Adam-SGD Gap in LLM Pre-Training: T](https://arxiv.org/abs/2605.17787)

---

### 5. Learning Variable-Length Tokenization for Generative Recommendation

새로운 연구는 추천 시스템에서 아이템을 고정 길이의 토큰으로 인코딩하는 기존 방식의 한계를 지적하고, 인기 있는 아이템은 짧은 토큰, 소수 아이템은 긴 토큰이 더 효과적임을 실험을 통해 입증했다. 이 '인기-길이 역설'은 아이템의 특성에 맞는 가변 길이 토큰화가 추천 성능을 극대화할 수 있음을 시사한다.

- **출처**: arxiv cs lg
- **링크**: [Learning Variable-Length Tokenization for Generati](https://arxiv.org/abs/2605.17779)

---

### 6. OrbiSim: World Models as Differentiable Physics Engines for Embodied Intelligence

OrbiSim은 물리 기반의 세계 모델을 다층 신경망 동역학과 강화 학습과 연결하는 새로운 로봇 시뮬레이션 패러다임을 제안합니다. 시뮬레이션 루프 전체에 걸쳐 내부적으로 미분 가능한 구조를 통해 로봇의 환경 이해와 행동 최적화를 통합적으로 처리할 수 있습니다.

- **출처**: arxiv cs lg
- **링크**: [OrbiSim: World Models as Differentiable Physics En](https://arxiv.org/abs/2605.16395)

---

### 7. GenTS: A Comprehensive Benchmark Library for Generative Time Series Models

AI 연구진들이 생성형 시계열 모델을 위한 종합 벤치마크 라이브러리 'GenTS'를 공개했다. 기존 시계열 라이브러리가 주로 판별 모델에 맞춰져 있어 합성, 예측, 보간 등의 생성 모델 작업을 지원하기 어렵다는 한계를 극복하기 위한 것이다. 적대적 학습이나 확산 프로세스 등 생성 모델의 복잡한 패러다임을 표준화된 워크플로우로 지원한다.

- **출처**: arxiv cs lg
- **링크**: [GenTS: A Comprehensive Benchmark Library for Gener](https://arxiv.org/abs/2605.17804)

---

### 8. AMO: Adaptive Muon Orthogonalization

AMO(Adaptive Muon Orthogonalization)는 대규모 사전 학습에서 AdamW를 대체할 수 있는 Muon 알고리즘의 성능을 향상시키기 위해 매개변수 행렬별로 다르게 작동하는 적응형 뉴턴-슈울츠 정교화 스케줄을 도입했다. 기존 방법이 모든 행렬에 동일한 스케줄을 적용하는 반면, AMO는 연산 유형과 학습 단계에 따라 변화하는 행렬 기하학적 특성을 고려해 최적화한다.

- **출처**: arxiv cs lg
- **링크**: [AMO: Adaptive Muon Orthogonalization](https://arxiv.org/abs/2605.17806)

---

### 9. A Unified Framework for Data-Free One-Step Sampling via Wasserstein Gradient Flows

연구자들은 웨이서스타인 그래디언트 흐름을 기반으로 데이터 없이도 단일 스텝으로 비정규화된 목표 분포에서 샘플을 추출할 수 있는 통합 이론 프레임워크를 개발했다. 다양한 f-발산 목적함수에 대해 속도 필드가 공통된 형태를 가지며, 이는 모든 방법이 동일한 점근적 목표 분포로 수렴함을 보여준다.

- **출처**: arxiv cs lg
- **링크**: [A Unified Framework for Data-Free One-Step Samplin](https://arxiv.org/abs/2605.17808)

---

### 10. Investigating Action Encodings in Recurrent Neural Networks in Reinforcement Learning

이 연구는 강화 학습(RL)에서 순환 신경망(RNN)의 동작 인코딩에 대한 분석을 다루며, RNN이 상태를 구축하고 정책 및 가치 함수를 학습하는 데 어떻게 중요한 역할을 하는지 설명합니다. 특히, 성능 향상에 기여하는 주요 설계 선택 사항과 구현 세부 사항들을 조사합니다.

- **출처**: arxiv cs lg
- **링크**: [Investigating Action Encodings in Recurrent Neural](https://arxiv.org/abs/2605.16318)

---

## 🌍 해외 경제 뉴스

### 1. SoftBank Founder’s Starstruck Bet on OpenAI Raises Concern

- **출처**: bloomberg economy
- **링크**: [SoftBank Founder’s Starstruck Bet on OpenAI Raises](https://www.bloomberg.com/news/features/2026-05-19/softbank-founder-son-s-devotion-to-openai-s-altman-spooks-some-insiders)

---

### 2. Japan Spent Billions and Yen Is Still Falling

- **출처**: bloomberg economy
- **링크**: [Japan Spent Billions and Yen Is Still Falling](https://www.bloomberg.com/graphics/2026-japanese-yen-timeline/)

---

### 3. Rising Heat Strains US Power Grid Needing Off-Season Repairs

- **출처**: bloomberg economy
- **링크**: [Rising Heat Strains US Power Grid Needing Off-Seas](https://www.bloomberg.com/news/articles/2026-05-19/rising-heat-strains-us-power-grid-in-need-of-off-season-repairs)

---

## 🇰🇷 국내 경제 뉴스

### 1. 국제유가, 이란 협상 진전 기대에 4거래일 만에 소폭 하락

(뉴욕=연합뉴스) 김연숙 특파원 = 3거래일 연속 상승했던 국제유가가 19일(현지시간) 소폭 하락했다.

- **출처**: yonhap economy
- **링크**: [국제유가, 이란 협상 진전 기대에 4거래일 만에 소폭 하락](https://www.yna.co.kr/view/AKR20260520007200072)

---

### 2. 달러-원, 美 국채금리 급등에 추가 상승…1,508.70원 마감

(뉴욕=연합뉴스) 진정호 연합인포맥스 특파원 = 달러-원 환율이 야간 거래에서 소폭 상승했다.

- **출처**: yonhap economy
- **링크**: [달러-원, 美 국채금리 급등에 추가 상승…1,508.70원 마감](https://www.yna.co.kr/view/AKR20260520006500002)

---

### 3. 비거주 1주택자 ‘세낀집’ 풀어줬지만…하이닉스 직원쯤 돼야 삽니다

비거주 1주택 실거주 유예 영향 전세금 LTV 넘으면 대출안돼 15억 매물은 현금 14억 필요 실수요자 급매물 나와도 외면 금수저 자녀·현금부자에 유리 실거주 유도 정책 실효성..

- **출처**: mk economy
- **링크**: [비거주 1주택자 ‘세낀집’ 풀어줬지만…하이닉스 직원쯤 돼야 삽니다](https://www.mk.co.kr/news/realestate/12052771)

---

