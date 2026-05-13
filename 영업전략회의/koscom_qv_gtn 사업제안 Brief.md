---
source_pdf: koscom_qv_gtn_사업제안_Brief.pdf
type: 사업제안 Brief
extracted: 2026-05-04
date: 2026.04
author: QV Labs Inc.
classification: Confidential
---

# KOSCOM + QV + GTN — 글로벌 유가증권 주문 허브 사업 제안

> **부제:** 한국 증권사의 해외주식·채권 주문을 표준화하고 글로벌 실행 네트워크로 연결하는 한국 자본시장 인프라 사업
> **작성:** QV Labs Inc. · **2026.04** · *Confidential*
> **출처:** `koscom_qv_gtn_사업제안_Brief.pdf` (7페이지)

---

## Page 1 — Cover

**KOSCOM + QV + GTN**
**글로벌 유가증권 주문 허브 사업 제안**

한국 증권사의 해외주식·채권 주문을 표준화하고 글로벌 실행 네트워크로 연결하는 한국 자본시장 인프라 사업

2026. 04
QV Labs Inc. | Confidential

---

## Page 2 — 1. 사업 개요 / 2. 사업 배경

### 1. 사업 개요

본 사업은 한국 증권사들이 글로벌 주식 주문을 해외 브로커와 개별적으로 연결하지 않고, **Koscom과 QV가 구성하는 Global Order Hub**를 통해 GTN 등 글로벌 브로커로 주문을 할 수 있도록 해주는 글로벌 투자를 위한 인프라 사업임.

#### 핵심 목적
- 한국 증권사의 해외 브로커 연결 부담 완화 (FIX / 전용선 / 인증 / 운영 부담 절감)
- 글로벌 브로커 온보딩 표준화 및 복수 브로커 연결 인프라 구축
- 주문 집행 품질 모니터링, TCA, 브로커 성과 분석 제공
- 시장 상황에 맞는 다양한 상품 제공
- 미국뿐 아니라 일본, 유럽, 중국 등 글로벌 시장 접근 제공
- 금융감독당국 감사 대비 체계적 보고 시스템 구축

### 2. 사업 배경

#### 2.1 해외주식 시장 현황
국내 해외주식 주문 시장은 이미 상당한 규모로서 지속적으로 성장 중.

| 항목 | 현황 | 사업적 의미 |
|---|---|---|
| **해외주식 수탁수수료** | 2025년 **2조 4,006억 원** (전년 대비 **66.4% 증가**) | 이미 대형 수익원 |
| **미국주식 비중** | 개인 해외주식 포트폴리오 중 약 **90.4%** | 미국주식부터 시작해서 확장해야 함 |
| **2025년 수수료 1위** | 토스증권 4,494억 원 (점유율 약 **18.7%**) | 수수료 경쟁 심화 → 상품 및 서비스로 극복해야 함 |
| **현지 브로커 구조** | DriveWealth 등 미국 현지 브로커의 주문집행 퀄리티에 의존 | 브로커 장애 리스크 노출 및 현장 지속적 애로사항 |
| **규제/운영 변화** | 복수 브로커/ATS 체계 강화 방향 | 공통 Hub 필요성 증가 |

---

## Page 3 — Key Messages / 시장 진입 전략

### Key Messages

1. 해외주식은 이미 국내 증권사의 핵심 수익원 (2025년 수탁수수료 2.4조 원, 전년 대비 66% 성장)
2. 개인 해외주식 flow의 약 **90%가 미국주식에 집중** — 초기 타겟 명확
3. **DriveWealth 장애 사례**처럼 현지 브로커 리스크가 국내 서비스 장애로 직접 전이
4. 복수 브로커/ATS 체계 필요하나, 증권사별 개별 구축은 비용/운영 복잡성이 과대
5. 후발 증권사들의 해외주식 진출 수요 존재 — 차별화된 서비스/상품이 필수

### 2.2 시장 진입 전략

해외주식 시장은 이미 상위 5개 증권사가 과점하고 있어, 정면 경쟁보다는 **후발 증권사 공략 후 대형사 확장 전략**이 유효함.

- **1단계:** 해외주식 서비스를 구축하려는 **중소형 증권사**를 대상으로 Hub의 즉시 연결 가치 제공
- **2단계:** 차별화된 상품(테마/전략/퀀트) + TCA/감사 대응 서비스를 통해 **대형사로 확장**
- **GTN 고유 장점 활용:** 80여개국 글로벌 주식시장 접근, 주식과 채권 모두 소수점 주문 실행 등 기존 현지 브로커(Cantor, DriveWealth 등)가 제공하지 못하는 **글로벌 커버리지와 멀티에셋 역량 보유**

> **Strategic Implication:** Koscom + QV Hub는 국내 증권사의 글로벌 주문 연결, 브로커 다변화, 집행품질 관리, TCA/감사 대응을 표준화하는 공통 인프라로서 중소형 증권사들의 필요와 고충을 해결하면서 새로운 사업 기회 제공.

---

## Page 4 — 3. 비즈니스 구조 / 4. 3사 역할 정의

### 3.1 Outbound Order Flow

한국 증권사의 해외주식 주문이 Hub를 거쳐 GTN으로 전달되는 기본 흐름:

```
한국 증권사 ─→ Global Order Hub (Koscom + QV) ─→ GTN (글로벌 실행)
```

### 3.2 Hub 내부 구조

| Koscom Layer | QV Layer |
|---|---|
| FIX Gateway 구축/운영 | 상품 설계 / Product Engine |
| OMS / Order Routing | TCA / Execution Analytics |
| 전용선 / 보안 네트워크 | Execution Governance |
| 시스템 운영 / 모니터링 | Broker Performance Scorecard |
| 증권사 Onboarding / 인증 | 해외 브로커 BD / 온보딩 |

### 4. 3사 역할 정의

각 회사는 대체하기 어려운 하나의 핵심 레이어를 담당함.

| 구분 | **Koscom** | **QV** | **GTN** |
|---|---|---|---|
| 포지션 | Infrastructure Provider | Intelligence + BD Layer | Execution Partner |
| 역할 1 | 국내 증권사 연결 인프라 | Product Engine (상품 설계) | 글로벌 실행 채널 |
| 역할 2 | 전용선 / 네트워크 운영 | TCA / Execution Governance | 80+ 주식시장 연결 |
| 역할 3 | FIX Gateway + OMS | Broker Scorecard | 채권 실행 가능 |
| 역할 4 | 운영 / SLA / 모니터링 | 국내 증권사 마케팅 지원 | 소수점 주문 지원 |
| 역할 5 | 한국 시장 신뢰 인프라 | 해외 브로커 BD / 온보딩 | Execution Economics 제공 |

---

## Page 5 — QV 포지셔닝 / 6. 수익 모델 / 7. 코스콤 관점 시작

### QV = Hub 내부의 Product & Execution Intelligence Layer

QV는 Hub 내부에서 상품 및 TCA Analytics를 제공하는 **Intelligence 운영 레이어**로서 기능:
- 글로벌 상품 / 포트폴리오 / 테마·전략 주문 설계 / 주문 메타데이터 내장
- TCA / 감사용 analytics 제공
- 국내 증권사 마케팅 지원 (고객 유인)
- 해외 브로커 온보딩 및 BD 주도

→ Hub의 Intelligence Layer 제공자로서 해당 flow에서 발생하는 수익에 참여함.

### 6. 수익 모델 및 배분 구조

#### 6.1 수익원
- 초기에는 **한국 증권사로부터 별도 플랫폼 사용료를 받지 않음**을 전제로 함.
- 따라서 주요 수익원은 **GTN execution economics** (Hub-routed Korean outbound flow에서 발생)이며, 이를 양 사가 쉐어하는 수익 모델.

#### 6.2 잠정 수익배분안 (현재 네고 중)

| **GTN** | **Koscom** | **QV** |
|---|---|---|
| **50% (+)** | **25% ~ 30%** | **20% ~ 25%** |
| 글로벌 실행 및 수익화 엔진 | 한국-side 인프라/운영/신뢰 | 상품/TCA/Governance/BD |

> 해외 증권사는 보통 10% 정도의 영업 커미션을 제공하나, **20% 이상은 매우 드문 경우**로 현재 네고 중임.

> **Hub-Routed Outbound Flow** = Koscom + QV Hub를 통해 GTN으로 전달되는 모든 한국 증권사 주문

### 7. 코스콤 관점의 전략적 가치 *(다음 페이지에 계속)*

---

## Page 6 — 7. 코스콤 관점의 전략적 가치 / 8. Next Steps / About GTN

### 7. 코스콤 관점의 전략적 가치

| **현재** | **Hub를 주도하면** |
|---|---|
| 증권사는 글로벌 플레이어와 직접 연결 | 한국-side 글로벌 Gateway 장악 |
| Outbound 인프라는 계속 분산 | 장기 outbound flow economics 확보 |
| 코스콤 역할은 국내시장 중심에 머무름 | 표준 브로커 연결 모델 정립 |
| 글로벌 flow economics가 외부로 이전 | 멀티브로커/멀티에셋 확장 옵션 확보 |

### 8. Next Steps

1. **Koscom-QV 공동 아키텍처 협의** (역할, IP, revenue 원칙 합의)
2. **GTN-facing commercial proposal 확정** (수익배분 및 flow 정의)
3. **Pilot 증권사 선정** (초기 1~2개 증권사)
4. **기술 설계** (FIX / OMS / Gateway / QV module scope)
5. **Hub 개발 및 GTN 연결, 고객 온보딩 & 테스트**
6. **서비스 런칭** — GTN anchor 이후 multi-broker 확장

> **Positioning Statement (영문):** Koscom provides the trusted Korean order infrastructure, QV provides the embedded product and execution intelligence layer, and GTN provides global execution — together creating Korea's first scalable Global Order Hub for outbound equity flow.

### About GTN

GTN은 브로커, 은행, 자산운용사, 핀테크 기업에 확장 가능한 트레이딩 및 투자 솔루션을 제공하는 글로벌 핀테크 기업이자 **B2B 전문 증권사**로, 직원 500명 이상이 브라질, 홍콩, 사우디아라비아, 싱가포르, 남아프리카, 스리랑카, UAE, 영국, 미국에서 근무하며, 영국·미국·싱가포르·UAE·남아프리카·홍콩에 증권업 라이선스를 보유하고 있음.

현재 단일 계정으로 트레이딩, 청산, 결제, 수탁이 가능하며 90개 이상 시장에서 8개 자산 클래스를 커버하고 있고, API/FIX 기반으로 파트너사의 주문 및 백엔드에 통합. **소수점 주식 거래(fractional trading)도 지원.**

---

## Page 7 — 전략적 투자자 / About QV Labs

### 전략적 투자자

세계은행 그룹의 **IFC**와 도쿄증권거래소 상장 대형 금융그룹인 **SBI Group**이 전략적 투자자임.

GTN의 차별점은 미국 주식만이 아닌 **90+ 글로벌 시장 커버리지**, 채권 포함 **8개 자산 클래스**, **소수점 거래**, 그리고 **IFC/SBI라는 전략적 투자자 기반의 글로벌 신뢰도**를 가지고 있음.

### About QV Labs

㈜큐브이랩스는 한국과 미국의 금융시장에서 30여년간 활약했던 **홍익대학교 황현철 교수**가 창업한 핀테크 산학벤처기업으로, 현재 **AI 및 퀀트 기반의 다양한 전략들과 상품을 제공할 수 있는 리서치 및 시스템 개발을 선도**하고 있음.

---

## 관련 노트
- [[해외 브로커 활용 비즈니스]]
- [[GTN Brochure 2023-11]]
- [[GTN Group Presentation - Spring 2026]]
- [[영업전략회의 보고자료]]
