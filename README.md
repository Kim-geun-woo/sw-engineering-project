# 🍽️ 개인 맞춤형 식재료 추천 시스템 (설계 및 분석)

본 프로젝트는 사용자 맞춤형 식재료 추천 서비스를 위한
UI 설계, 유스케이스/시퀀스/클래스 다이어그램, DFD, 아키텍처 설계,
비용 산정, 위험 관리 등 소프트웨어 전반의 설계 및 분석 업무를 수행하였습니다.
실제 프로그램 개발 단계는 포함되어 있지 않습니다.

---

## 📌 프로젝트 개요

- **목표**: 개인별 신체 측정 데이터를 바탕으로 최적의 영양소를 고려해 맞춤형 식재료를 추천하는 시스템 설계
- **진행 기간**: 2024.03 ~ 2024.06
- **참여 인원**: 총 4명
- **내 역할**: UI 설계, 시퀀스 다이어그램 작성, 비용 산정, 위험 계획 수립

---

## 👤 담당 역할 정리

| 팀원 | 역할 |
|------|------|
|  본인    | UI 설계, 시퀀스 다이어그램 작성, 비용 산정, 위험 계획 수립 |
| 팀원 A    | DFD, 유스케이스 다이어그램 및 시나리오 작성 |
| 팀원 B    | 클래스 다이어그램, 아키텍처 설계 |
| 팀원 C    | UI 기본 정책 수립, 사이트맵 구성, 시퀀스 다이어그램 작성 |

---

## 🧩 핵심 설계 산출물

| 항목 | 설명 |
|------|------|
| ✅ UI 설계 정책 | 기본 정책 정의 및 전체 서비스 플로우 설계 |
| ✅ 유스케이스 다이어그램 | 사용자와 시스템 간의 주요 상호작용 정의 |
| ✅ 유스케이스 시나리오 | 시나리오는 PDF 문서로 별도 제공 |
| ✅ 시퀀스 다이어그램 | 기능별 데이터 흐름 및 객체 간 상호작용 시각화 |
| ✅ 클래스 다이어그램 | 주요 클래스 및 속성/메서드 정의 |
| ✅ DFD | 시스템 내 데이터 흐름과 처리 과정 시각화 |
| ✅ 아키텍처 설계 | 시스템 구조, 모듈 간 관계 정의 |
| ✅ 비용 산정 | 기능점수 기반 비용 예측 및 보정 |
| ✅ 위험 계획 | 프로젝트 리스크 및 대응 방안 설계 |

---

## 💵 비용 산정 요약

| 기능 유형 | 개수 | 점수 |
|-----------|------|------|
| ILF       | 2    | 15.0 |
| ELF       | 1    | 5.4  |
| EI        | 8    | 32.0 |
| EO        | 7    | 36.4 |
| EQ        | 5    | 19.5 |
| **총합**  | –    | **108.3** |

- **보정 전 원가**: `108.3 × 553,114원 = 59,902,246원`
- **보정 계수**: 1.28 × 0.94 × 0.95 × 1.0 × 1.0 = 1.14
- **보정 후 원가**: **약 68,470,664원**

---

## ⚠️ 위험 계획

| 위험 요소 | 가능성 | 영향도 | 대응 방안 |
|-----------|--------|--------|-----------|
| 요구사항 변경 | 중 | 상 | 팀 회의를 통해 요구사항 분석 및 수정 |
| 소통 부족     | 중 | 하 | 주간 회의 및 협업 툴 적극 활용 |
| 구현 기간 부족 | 중 | 상 | 우선순위 설정, 범위 조정 |
| 인력 변동     | 중 | 상 | 역할 재분배 및 사전 공유 |
| 데이터 손실   | 하 | 중 | 정기 백업 실시 |
| 팀원 무관심   | 하 | 중 | 소통을 통한 팀 분위기 개선 |

---

## 🖼️ 다이어그램 예시

### 📌 UI 플로우차트
![UI 흐름도](https://github.com/Kim-geun-woo/sw-engineering-project/raw/main/images/flowchart.jpg)

### 📌 유스케이스 다이어그램
![Use Case Diagram](https://github.com/Kim-geun-woo/sw-engineering-project/raw/main/images/usecase_diagram.png)

### 📌 시퀀스 다이어그램
![Sequence Diagram](https://github.com/Kim-geun-woo/sw-engineering-project/raw/main/images/sequence_diagram.png)

### 📌 클래스 다이어그램
![Class Diagram](https://github.com/Kim-geun-woo/sw-engineering-project/raw/main/images/class_diagram.png)

### 📌 DFD (데이터 흐름도)
![DFD](https://github.com/Kim-geun-woo/sw-engineering-project/raw/main/images/DFD.jpg)

### 📌 아키텍처 설계
![Architecture Diagram](https://github.com/Kim-geun-woo/sw-engineering-project/raw/main/images/architecture.jpg)

---

### 📝 유스케이스 시나리오

유스케이스 시나리오는 PDF 문서로 정리되어 있으며, 아래 링크를 통해 확인할 수 있습니다.

📄 [유스케이스 시나리오 보기 (PDF)](https://github.com/Kim-geun-woo/sw-engineering-project/blob/main/docs/usecase_scenarios.pdf)

---

## 🛠️ 사용 툴

- UML 모델링: **Enterprise Architect**
- 문서 작성: Excel, Word
- 협업 도구: Notion, Google Drive
