# 개인 맞춤형 카드 추천 Agent 🤖 - 챗봇의 정석  

<img width="1920" alt="mockup" src="https://github.com/user-attachments/assets/4f6bc1e1-b517-43f3-bef9-c3d496d2ebe2" />


---

## 💳 프로젝트 소개 

**챗봇의 정석**은 사용자 맞춤 **카드 추천**과 **금융 문의 답변**을 제공하는 **카드 추천 Agent** 서비스입니다. 카드 선택 과정에서 누구나 겪는 **복잡함을 줄이고**, 필요한 정보만 **빠르게 제공**하여 더 쉽게 자신의 **라이프스타일**에 맞는 카드를 선택하는 것을 목표로 합니다.



주요 서비스 기능은 아래와 같으며 [2. ✨ 주요 화면 및 기능](#feature)에서 자세히 확인하실 수 있습니다.

- ⭐ **카드 혜택 설명 및 비교**

- ⭐ **혜택 기반 카드 상품 추천**

- ⭐ **금융 용어 QnA**

- ⭐ **카드 상품 및 가입 관련 QnA**

- ⭐ **개인 소비 패턴 기반 카드 추천**


## ⚒️ 1. 기술 스택

| 구분                                                                    | 기술 스택                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 🔗[FrontEnd](https://github.com/FISA5th-AI-Final-Team4/FrontEnd)     | <img src="https://img.shields.io/badge/ReactJS-61DAFB?style=for-the-badge&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=FFCF27">                                                                                                                                                                                                                                                                                                                                                        |
| 🔗[BackEnd](https://github.com/FISA5th-AI-Final-Team4/BackEnd)      | <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">                                                                                                                                                                                                                                                                                                                                                   |
| 🔗[LLM Agent](https://github.com/FISA5th-AI-Final-Team4/LLMServer)    | <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=LangGraph&logoColor=white"/> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=Ollama&logoColor=white"> <br> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">                                                                                                                         |
| 🔗[MCP Server](https://github.com/FISA5th-AI-Final-Team4/MCPServer)    | <img src="https://img.shields.io/badge/MCP-1C3C3C?style=for-the-badge&logo=modelcontextprotocol&logoColor=white"/> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=Ollama&logoColor=white"> <br> <img src="https://img.shields.io/badge/scikit-learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> |
| 🔗[Database](https://github.com/FISA5th-AI-Final-Team4/LocalDbSetup) | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white"/> <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">                                                                                                                                                                                                                                                                                                                                                                         |
| **협업 및 개발** | <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Slack-E01E5A?style=for-the-badge"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"> <br> <img src="https://img.shields.io/badge/VSCode-24ACF2?style=for-the-badge"> <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=GoogleColab&logoColor=E8710A"> <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=FFFFFF"> |



각 원격 저장소 페이지에서 더 자세한 설명을 확인하실 수 있습니다.

🔗 [커밋 컨벤션](https://github.com/FISA5th-AI-Final-Team4/.github/wiki/%EC%BB%A4%EB%B0%8B-%EC%BB%A8%EB%B2%A4%EC%85%98)
 



## <span id="feature">✨ 2. 주요 화면 및 기능 <span>

| **✨ 카드 혜택 설명 및 비교** | **✨ 혜택 기반 카드 상품 추천** | **✨ 개인 소비 패턴 기반 카드 추천** |
| :------: | :------: | :------: |
| <img height="720" alt="image 74" src="https://github.com/user-attachments/assets/9d7e56f3-efb2-48db-85b1-d4b421e566b0" /> | <img height="720" alt="image 75" src="https://github.com/user-attachments/assets/b569ca2e-2c45-4df9-a6c6-b731a1584cc3" /> | <img height="720" alt="image 78" src="https://github.com/user-attachments/assets/0f0f17d5-8e2e-4ed7-a422-a11c448f4f48" /> |
| **✨ 카드 상품 및 가입 관련 QnA** | **✨ 금융 용어 QnA** | **✨ 기본 응답 및 사용자 피드백** |
| <img height="720" alt="image 77" src="https://github.com/user-attachments/assets/9322aec7-fdfc-4f5b-9c2c-144b94b74a79" /> | <img height="720" alt="image 62" src="https://github.com/user-attachments/assets/c41fe1b8-4ba4-4792-8d18-d0dcb4bb0f19" /> | <img height="720" alt="image 80" src="https://github.com/user-attachments/assets/cced9ae3-f8b3-42b3-bb45-b23070eb74f9" /> |

### ⭐ **카드 혜택 설명 및 비교**

- 사용자가 특정 카드의 혜택을 알고 싶거나, 여러 카드를 비교하고 싶을 때 카드 상품 설명서에서 관련 문단을 찾아 한눈에 정리해 주는 기능입니다.
- 하나의 질문을 여러 관점의 검색 쿼리로 확장하는 Multi-Query Retrieval과 벡터 DB 기반 RAG를 활용해, 카드별 혜택·연회비·카테고리 할인 정보 등을 모아서 이해하기 쉬운 비교형 답변으로 제공합니다.

### ⭐ **혜택 기반 카드 상품 추천**

- 사용자가 **원하는 혜택(예: 편의점·교통·해외결제·적립 위주 등)**을 입력하면, 카드 상품 지식 그래프 위에서 관련된 카드들을 찾아 적합한 카드들을 추천해 주는 기능입니다.
- nano-graphrag 기반 GraphRAG을 활용하여 카드 간 연관 관계와 혜택 구조를 함께 고려해 답변을 생성하며, 대화 히스토리를 반영해 이전 상담 맥락까지 이어지는 추천을 제공합니다.

### ⭐ **금융 용어 QnA**

- 사용자가 카드 이용·발급 과정에서 자주 마주치는 **금융 용어**의 뜻을 물어보면, 질문에서 핵심 키워드를 뽑아 **PostgreSQL + pg_bigm** 유사도 검색으로 가장 알맞은 용어를 찾아 설명해 주는 기능입니다.
- 오타나 띄어쓰기("연회삐", "연 회비")가 포함되어 있어도 2-gram 기반 유사도 점수로 가까운 용어를 찾아내고, **대표 정의**와 함께 **관련 용어**도 함께 제시하여 사용자가 주변 개념까지 한 번에 이해할 수 있도록 돕습니다.

### ⭐ **카드 상품 및 가입 관련 QnA**

- 카드 상품 특징, 발급 절차, 재발급·해지 등과 관련된 **자주 묻는 질문(FAQ)**에 대해 답변합니다.  
- FAQ 데이터베이스를 대상으로 **Bi-Encoder + Cross-Encoder** 기반 2단계 의미 검색을 적용하여, 사용자 질문과 가장 유사한 카드/가입 관련 FAQ를 찾아 정확한 답변과 함께 관련 질문도 함께 제공합니다.

### ⭐ **개인 소비 패턴 기반 카드 추천**

- 로그인된 **사용자의 소비 데이터에 기반**하여 개인 맞춤형 카드 추천을 제공합니다.
- 사용자의 **월별 소비 패턴을 분석**하여 군집화하고, 각 군집에 적합한 카드를 추천합니다.
- 비 로그인 상태의 경우 챗봇 메세지로 로그인을 지원하여 로그인합니다.

## 📽️ 3. 시연 영상

<video src="https://github.com/user-attachments/assets/7d841893-f65e-42cc-bebe-09b9431e75a9" controls width="1920">
    [시연 영상 파일 주소](https://github.com/FISA5th-AI-Final-Team4/.github/tree/main/assets)
</video>






## 📦 4. 시스템 아키텍처

<img width="1920" alt="image" src="https://github.com/user-attachments/assets/465fee69-c97e-4795-85ee-8dde31d2fdcb" />

<img width="1920" alt="image" src="https://github.com/user-attachments/assets/dc95ab7e-1c61-4165-b461-1a73ed1e9846" />



## 😎 5. 팀원 소개

| **강인혁** |  **배시훈** | **이정환** |
| :------:  | :------: | :------: |
| [<img src="https://github.com/user-attachments/assets/6dfcd51d-b377-4fab-b93f-0f8bbd534de0" height=160/> <br/> @kenkang99](https://github.com/kenkang99) | [<img src="https://github.com/user-attachments/assets/56f857a8-82b1-4bbc-982e-e943a8d3e454" height=160/> <br/> @BaeSihun](https://github.com/BaeSihun) | [<img src="https://github.com/user-attachments/assets/f3bb5246-57b7-4640-8d98-8820a5a7af86" height=160/> <br/> @ljh4770](https://github.com/ljh4770) |
| **PM**/**AI Engr.** | **Data Engr.**/**ML Engr.** | **FE/BE**/**Infra Engr.** |

## 📚 6. 역할 분담

### 강인혁 — PL / PM & AI Engineer

- **🧑‍💼 서비스 기획 및 팀 운영**
    - 프로젝트 주제 발의 및 목표 & 지표 설정, 개발 일정 수립

- **✨ AI 기능 개발**
    - 카드 혜택 설명/비교 기능 구현, 혜택 기반 카드 추천 모델 개발

- **⚡️ RAG 시스템 고도화**
    - AI Agent 설계, RAG 성능 개선 Graph RAG 파이프라인 구축, LangSmith 이용 성능 추적

- **💽 데이터 처리 담당**
    - 우리카드 상품 정보 크롤링, 카드 상품 설명서·혜택 텍스트 정제

### 배시훈 — Data & ML Engineer

- **✨ ML 기능 개발**
    - 소비 데이터 분석 및 군집화 모델링, 소비 패턴 기반 카드 추천 로직 개발

- **✨ QnA 기능 개발**
    - 금융 용어 QnA, 카드 가입/상품 관련 QnA 기능 개발 및 성능 개선

- **🗃️ 데이터 엔지니어링**
    - 금융 용어·FAQ 데이터 크롤링, ERD 설계, DB 구축

- **♻️ MCP 기능 마이그레이션**
    - RAG 및 ML 파이프라인 서버 통합 및 코드 리팩터링

### 이정환 — FE / BE & Infra Engineer

- **✨ 챗봇 기능 개발**
    - 웹소켓 기반 실시간 통신 적용, LangGraph 기반 MCP 툴 호출 및 가드레일 구현

- **🏗️ 서비스 아키텍처 설계**
    - 로드 밸런싱·사용자 응답 속도 고려 서비스 아키텍처 설계

- **☁️ 인프라 구축 및 배포**
    - 온프레미스·AWS 환경에서 서비스 배포, Docker 기반 개발 환경 구성

- **🛠️ 백엔드 아키텍처 및 서버 개발**
    - FastAPI 기반 서버 구조 설계, API 및 서비스 로직 개발

- **🖥️ 프론트엔드 구현**
    - 클라이언트 화면 구현 및 기능 연동


## 📝 7. 프로젝트 정보


| 항목 | 내용 |
|------|-------|
| **소속** | 우리 FIS Academy 5기 AI 엔지니어링 과정 4팀 |
| **프로젝트 기간** | 2025.10.13 ~ 2025.12.05 |
| **사용 데이터 출처** | - [우리카드 상품 설명 데이터](https://pc.wooricard.com/dcpc/yh1/crd/crd02/H1CRD202S00.do?ctgrCd=S000017&hiPrdCtgrCd=M110018)<br> - [우리카드 FAQ](https://pc.wooricard.com/dcpc/yh1/cct/cct03/H1CCT203S07.do)<br> - [개인 소비 데이터](https://www.aihub.or.kr/aihubdata/data/view.do?pageIndex=1&currMenu=&topMenu=&srchOptnCnd=OPTNCND001&searchKeyword=&srchDetailCnd=DETAILCND001&srchOrder=ORDER001&srchPagePer=20&srchDataRealmCode=REALM015&aihubDataSe=data&dataSetSn=71792)<br> - [금융 용어 (CREFIA)](https://gongsi.crefia.or.kr/portal/financialProdInfo/finanGlossary)<br> - [금융 용어 (한경)](https://dic.hankyung.com/economy/list/?word=%EC%8B%A0%EC%9A%B0%EC%B9%B4%EB%93%9C)<br> - [금융 용어 (FSS)](https://fine.fss.or.kr/fine/fnctip/fncDicary/list.do?menuNo=900021&pageIndex=3&src=&kind=&searchCnd=1&searchStr=)<br> - [금융 용어 (Koscom)](https://www.koscom.co.kr/portal/bbs/B0000034/list.do?ise=P&searchWrd=&menuNo=200646) |
