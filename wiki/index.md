# PRO ILI SMART — Wiki Index

> 이 문서는 PRO ILI SMART 프로젝트 지식베이스의 카탈로그입니다.
> LLM이 쿼리 시 이 파일을 먼저 읽고 관련 페이지를 탐색합니다.

---

## 엔티티 (Entities) — `wiki/entities/`
제품, 기능 모듈, 핵심 인물(페르소나), 경쟁사, 외부 시스템 등 고유명사 단위 페이지.

### 제품 & 모듈
| 페이지 | 한줄 요약 | 출처 수 |
|:---|:---|:---:|
| [[PRO-ILI-SMART]] | 반도체 소부장 SME용 AI+Lean+ISO 통합 플랫폼 전체 개요 | 13 |
| [[Smart-Audit]] | ISO 양식 자동 매핑 기반 Audit 리포트 생성 엔진 | 5 |
| [[Zero-UI]] | 음성/비전 AI 기반 마찰 없는 현장 데이터 수집기 | 5 |
| [[Lean-Diagnosis]] | COPQ 4대 낭비 금액 환산 및 ROI 대시보드 | 4 |
| [[NC-Correction]] | 긴급 부적합(NC) 시정 조치 패키지 | 4 |
| [[Global-Vendor-Accelerator]] | 해외 팹 벤더 등록 가속기 (Phase 2) | 3 |
| [[Data-Integrity-System]] | Insert-only 감사 로그 및 RBAC 권한 제어 | 2 |
| [[Bulk-Import]] | CSV/Excel 기준정보 일괄 업로드 도구 | 1 |

### 페르소나
| 페이지 | 역할 | 유형 |
|:---|:---|:---:|
| [[Persona-박품질]] | HBM/EUV 부품사 품질팀장 (Champion) | Core |
| [[Persona-정태식]] | NC 위기 CEO (Decider) | Extreme |
| [[Persona-오반장]] | 20년차 현장 반장 (End-User) | Extreme |
| [[Persona-김도약]] | 해외진출 CEO (Visionary) | Core |
| [[Persona-한셋업]] | 신공장 TF 팀장 | Adjacent |
| [[Persona-최야근]] | 품질기획실 실무 대리 | Core |

### 경쟁사 & 외부 기관
| 페이지 | 한줄 요약 |
|:---|:---|
| [[Competitor-Miracom]] | 미라콤아이앤씨 — 스마트팩토리 MES 1위 |
| [[Competitor-OnePredict]] | 원프레딕트 — 딥러닝 예지보전 1강 |
| [[Competitor-MachinaRocks]] | 마키나락스 — 산업용 MLOps |
| [[Competitor-KSA-KPC]] | 한국표준협회(KSA) / 한국생산성본부(KPC) |

---

## 개념 (Concepts) — `wiki/concepts/`
프레임워크, 전략, 기술 아키텍처 등 도메인 지식 페이지.

### 비즈니스 전략
| 페이지 | 한줄 요약 |
|:---|:---|
| [[AOS-DOS-Matrix]] | 고객 절박함 × 시장 가치 결합 분석 |
| [[JTBD]] | Jobs to be Done 페르소나별 핵심 과업 모델 |
| [[Zero-Paperwork]] | 120시간→1분 행정 자동화 핵심 가치 |
| [[Porters-Five-Forces]] | 3대 시장별 5 Forces 경쟁 환경 분석 |
| [[KSF]] | 5대 핵심성공요인 전략 |
| [[Value-Chain]] | 경쟁사 가치 사슬 비교 분석 |
| [[Problem-Definition]] | 3대 시장 통합 문제정의서 |
| [[Market-Size-TAM-SAM-SOM]] | 시장 규모 산출 및 세분화 전략 |
| [[Revenue-Model]] | 보조금 연계 SaaS 구독 수익 구조 |
| [[GTM-Strategy]] | Go-to-Market 시장 진입 쐐기 전략 |
| [[RegTech-Vision]] | 원청 실사 프리패스 — 최종 비즈니스 종착지 |
| [[Persona-Spectrum-Map]] | 12종 페르소나 전략적 영향력 매핑 |
| [[Customer-Journey-Map]] | 12종 페르소나 고객 여정 지도 |

### 기술 아키텍처
| 페이지 | 한줄 요약 |
|:---|:---|
| [[Tech-Stack]] | Next.js + Supabase + Gemini API 기술 제약 |
| [[System-Architecture]] | 시스템 컴포넌트 및 ERD |
| [[Security-Compliance]] | 보안/개인정보/규제(PIPA·GDPR) 요구사항 |
| [[AI-Governance]] | 모델 카드, VMP, Drift 감지, HitL 거버넌스 |
| [[NFR-Performance]] | 성능·가용성·무결성 비기능 요구사항 |

---

## 출처 요약 (Sources) — `wiki/sources/`
`raw/` 폴더의 원본 문서별 수집(Ingest) 요약 페이지.

| 페이지 | 원본 파일 | 핵심 키워드 |
|:---|:---|:---|
| [[src-00-PRD]] | 00_PRD_v1.md | PRD 품질 게이트 Full Pass 4.72/5.0 |
| [[src-05-SRS]] | 05_SRS_v1.md | SRS 기술 요구사항 (29148:2018) |
| [[src-06-VP-Sheet]] | 06_Value-proposition-sheet | PSO 흐름, 3대 가치 기둥 |
| [[src-10-JTBD]] | 10_jtbd-interview-report.md | 6종 JTBD 카드 |
| [[src-01-Porters]] | 1_porters-Five-foreces.md | 3대 시장 5 Forces |
| [[src-02-Competitors]] | 2_competents-analysis.md | 경쟁사 통합 분석 |
| [[src-03-ValueChain]] | 3_value-chain.md | 가치 사슬 분석 |
| [[src-04-KSF]] | 4_ksf-report.md | 5대 KSF |
| [[src-05-Problem]] | 5_problem-definition.md | 문제정의서 |
| [[src-06-TAM-SAM-SOM]] | 6_TAM-SAM-SOM+MarketSegment.md | 시장 규모 및 세분화 |
| [[src-07-Persona]] | 7_persona-spectrum-map.md | 페르소나 스펙트럼 |
| [[src-08-CJM]] | 8_customer-journey-map.md | 12종 고객 여정 |
| [[src-09-AOS-DOS]] | 9_aos-dos-analysis.md | AOS-DOS 매트릭스 |
