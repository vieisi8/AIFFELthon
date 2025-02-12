# AIFFELthon
AIFFELthon??
  - AIFFEL 과정 마지막에 진행하는 프로젝트를 지칭함
  - 총 60일간 진행 (24.12.13~25.02.10)

# YJS
![image](https://github.com/user-attachments/assets/b485e975-f4ee-43d3-98ba-196b7c1d304f)
  - 기업(아이젠사이언스)와 협업한 프로젝트
    - 기업과 협업 프로젝트기에 중요한 정보 기입 X

## 프로젝트 개발 배경
신약 개발 과정에서 화학 특허와 논문에 포함된 방대한 데이터를 분석하고 구조-활성 관계를 도출하는 작업은 필수적입니다. 그러나 이 작업은 대량의 데이터를 수작업으로 처리해야 하기 때문에 많은 시간과 비용이 소요되며, 오류 발생 가능성도 큽니다. 이에 물질 구조-활성 관계를 체계적으로 분석하여 설계 효율성을 높이는 데 필요한 데이터 합성 및 자동화 시스템이 부족한 상황입니다. 그런 점을 보안하고자 본 프로젝트를 기획하게 되었습니다.

## 프로젝트 목표
  - 물질 구조-활성 정보를 추출하여 신약 개발 초기 단계의 실패 확률을 줄이는 것

## 📚 기술 스택
  - LLM & AI
    - GPT
    - LangChain Agents
    - Prompt Engineering
  - Front-end
    - Streamlit
  - Back-end
    - Python
    - Streamlit

## 프로젝트 flowchart
![image](https://github.com/user-attachments/assets/d31f0f1f-964a-403a-b86e-1acda0482b5d)

## 프로젝트 기여
  - IUPAC2SMILES Tool 개발
  - 개발된 각 툴의 내부 코드 수정 및 최적화하여 기능 및 효율성 개선
  - Agent 내부 코드를 수정, 구현된 Tool을 통합, Agent 프롬프트 엔지니어링

## YJS 시연

https://github.com/user-attachments/assets/10023a16-8487-401c-ad53-dc95fee40dc8

## 프로젝트 결과/성과
  - 신약 특허 파일에서 SMILES 기반 SAR 테이블 자동 추출 (추출 성능: 각 Tool 성능을 고려 하면 약 70~80%)

## 시사점 및 한계
  - AI 기술이 신약 개발 프로세스를 혁신적으로 개선할 수 있음을 보여줌
  - AI 기반 분석 시스템이 신약 개발의 필수 도구로 자리 잡을 가능성 제시
  - 한계점으로는 SAR 테이블 추출 성능이 높지 않음

## 프로젝트를 통해 배운 점과 아쉬운 점이나 보완할 점
  - 라이브러리 충돌 문제의 해결 방안을 찾아냄
  - 특허 데이터에 대해서만 개발 및 테스트를 진행해 아쉬움이 남음
