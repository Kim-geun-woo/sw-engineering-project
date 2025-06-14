# 🍽️ 개인 맞춤형 식재료 추천 시스템

> 사용자의 기호 및 입력 정보를 기반으로, 개인 맞춤형 식재료를 추천하는 시스템  
> UI 설계부터 UML 분석, 비용 산정 및 위험 관리까지 **소프트웨어 설계 전 과정을 수행**

---

## 📌 프로젝트 개요

- **목표**: 사용자의 입력을 바탕으로 식재료를 개인 맞춤으로 추천하는 시스템 설계
- **진행 기간**: 2024.03 ~ 2024.06
- **참여 인원**: 총 4명
- **내 역할**: UI 설계, 시퀀스 다이어그램 작성, 비용 산정, 위험 계획 수립

---

## 👤 담당 역할 정리

| 역할 | 상세 내용 |
|------|-----------|
| UI 설계 | 기본 정책 정의, 사이트맵 및 화면 흐름 설계 |
| 시퀀스 다이어그램 | 기능별 데이터 및 흐름 구조 시각화 |
| 비용 산정 | FP(Function Point) 기반 산정 및 보정 |
| 위험 계획 | 6개 리스크 항목 분석 및 대응 전략 수립 |

---

## 🧩 핵심 설계 산출물

| 항목 | 설명 |
|------|------|
| ✅ UI 설계 정책 | 기본 정책 정의 및 전체 서비스 플로우 설계 |
| ✅ 유스케이스 다이어그램 | 사용자와 시스템 간의 주요 상호작용 정의 |
| ✅ 시퀀스 다이어그램 | 주요 기능의 흐름과 객체 간 상호작용 시각화 |
| ✅ DFD (Data Flow Diagram) | 데이터 흐름 및 처리 구조 정의 |
| ✅ 클래스 다이어그램 | 주요 클래스 및 속성/메서드 정의 |
| ✅ 비용 산정 | 기능점수 기반 비용 예측 |
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
![UI 흐름도]([./images/flowchart.png](https://github.com/user-attachments/assets/ecf1d2f2-7d61-43d5-b01f-c35f83fc5d60))

### 📌 유스케이스 다이어그램
![Use Case Diagram]([./images/usecase_diagram.png](https://github.com/user-attachments/assets/c4cfd93a-3900-487d-a64d-a3f61c4cc4d4))

### 📌 시퀀스 다이어그램
![Sequence Diagram]([./images/sequence_diagram.png](https://github.com/user-attachments/assets/f4a051bd-9198-4c88-b641-0cbf3174e31d))

### 📌 클래스 다이어그램
![Class Diagram]([./images/class_diagram.png](https://github.com/user-attachments/assets/4fdf94b4-bbdb-499f-8037-5d294a41efbd))

### 📌 아키텍처 설계
![Architecture Diagram]([./images/architecture.png](https://github.com/user-attachments/assets/7fd7d2e9-8165-4073-b001-b5c94931787b))

### 📌 DFD (데이터 흐름도)
![DFD]([./images/dfd.png](https://github.com/user-attachments/assets/30295d76-0a2a-444d-89e8-63b0a0aef48f))

---

### 📝 유스케이스 시나리오

유스케이스 시나리오는 PDF 문서로 정리되어 있으며, 아래 링크를 통해 확인할 수 있습니다.

📄 [유스케이스 시나리오 보기 (PDF)]([[./documents/usecase_scenarios.pdf](https://github.com/Kim-geun-woo/sw-engineering-project/blob/main/docs/usecase_scenarios.pdf)](https://github.com/Kim-geun-woo/sw-engineering-project/blob/main/docs/usecase_scenarios.pdf))

---
## 🛠️ 사용 툴

- UML 모델링: **Enterprise Architect**
- 문서 작성: Excel, Word
- 협업 도구: Notion, Google Drive

