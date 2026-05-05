

# 🌊 IPAP: 지능형 오염원 통합 분석 플랫폼
**Intelligent Pollution Analysis Platform**

> **2025 대국민 지하수 빅데이터 공모전 | 환경부장관상(최우수상) 수상작**  
> AI와 수리 모델링을 결합하여 지하수 오염의 원인과 경로를 과학적으로 규명합니다.

<br>

## 💡 Background & Objective

### **추진 배경**
* **사회적 위기 확산:** 광주 산업단지 발암물질 유출 및 제주 지하수 오염 등 급증하는 환경 사고
* **데이터 파편화:** 여러 기관에 분산된 오염원 및 수질 데이터로 인해 통합적인 대응체계 부재
* **기존 시스템의 한계:** 경험 중심의 사후 대응으로 인한 규명 골든타임 상실 및 복원 비용의 기하급수적 증가

### **프로젝트 목표**
* **선제적 관리:** 사후 대응 중심에서 AI 기반의 예방적·선제적 관리 체계로 전환
* **지능형 분석:** 데이터 기반의 이상 감지, 유입 경로 역추적, 오염원 추론 기능 통합
* **효율성 극대화:** AI 기술을 통한 오염 규명 시간 단축 및 행정적·경제적 손실 절감

<br>

## 📌 Project Overview
**국내 최초, 수리 모델링(Physics)과 그래프 신경망(GNN)의 하이브리드 접근법**  
IPAP은 지하수 오염 발생 시 **'어디서(Where) → 어떻게(Origin) → 누가(Who)'**로 이어지는 3단계 원인 규명 프레임워크를 통해 오염의 근원지를 정밀하게 타격하는 차세대 환경 AI 솔루션입니다.

<br>

## 🔍 Core Architecture & Methodology

### **1. Data Engineering (Input)**
* **Multi-Source Integration:** 분산된 9종의 오염원 데이터를 '시군구' 단위로 연계 및 표준화
* **Feature Engineering:** 불투수층 면적, 총 오염 부하량 등 복합 오염 지표 개발
* **Region Matrix:** 모델 최적화를 위한 지역별 오염 특성 벡터(Feature Vector) 구축

### **2. 3-Step Analysis Framework (AI Fusion)**
| 단계 | 명칭 | 주요 기술 및 내용 |
| :-- | :--- | :--- |
| **STEP 01** | **오염 이벤트 감지** | 법적 기준치 기반 실시간 모니터링 및 이상치 DB 자동화 |
| **STEP 02** | **물리 경로 역추적** | **Flopy(MODFLOW)** 기반 역방향 유동 모델링으로 후보 권역 도출 |
| **STEP 03** | **오염원 유형 추론** | **GNN(Graph Neural Network)**을 통한 공간 관계 및 패턴 유사도 분석 |

<br>

## 🍀 Key Differentiation
* **융합 기술:** 물리 기반 수리 모델링과 데이터 기반 딥러닝의 상호 보완적 결합
* **입체적 분석:** 위치와 원인을 동시에 규명하는 End-to-End 자동화 파이프라인
* **XAI 지향:** 분석 결과의 과학적 근거 제시로 정책 결정의 신뢰성 확보

<br>

## 💻 Tech Stack
| Category | Tech |
| :--- | :--- |
| **Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Analysis** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) |
| **Modeling** | ![MODFLOW](https://img.shields.io/badge/MODFLOW/Flopy-0067B1?style=flat-square) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) |

<br>

## 🌟 Visuals
### **🖥️ System Interface**
1. **통합 관제 대시보드:** 실시간 지하수 오염 현황 및 핵심 지표 시각화
2. **AI 분석 리포트:** 오염원 유형별 통계 및 인터랙티브 데이터 분석
3. **지능형 맵 서비스:** 지도 기반 오염 감지 지점 및 확산 경로 시각화
4. **지역 비교 인사이트:** 지역별 오염 양상 비교 분석 및 AI 기반 최적 솔루션 제언

<br>

## 👥 Team '샘났다!'
* **정소미** [![Github](https://img.shields.io/badge/Github-link?style=social&logo=github)]([https://github.com/](https://github.com/))
* **이정원** [![Github](https://img.shields.io/badge/Github-link?style=social&logo=github)](https://github.com/)
* **편도현** [![Github](https://img.shields.io/badge/Github-link?style=social&logo=github)](https://github.com/)

<br>

## 📞 Contact
* **Email:** [1wosxai@gmail.com]
* **Links:** [환경부](http://me.go.kr) | [국가지하수정보센터](https://www.gims.go.kr)
