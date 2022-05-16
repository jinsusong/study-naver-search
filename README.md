# naver search colloquium


## 2022
- [Deep Dive into Longtail E-commerce Recommendation](https://www.notion.so/Commerce-AI-Deep-Dive-into-Longtail-E-commerce-Recommendation-f00cbe55ea364434bff6cfa5e1e00bb0)
  - Commerce AI
  - 추천 시스템에서 발생하는 롱테일 문제를 해결



- [Commerce AI : ](https://www.notion.so/Naver-Search-Colloquium-4edd7772dcec43bd94390e923d23da8f) **Online Serving AD Relevance Model Using BERT**
  - 광고 랭킹 & Cold-start Problem
  - bert 활용
  - 쿼리 → 실시간 임베딩 구함. → 최근 사용된 쿼리는 캐싱에 저장 →

- [NLP search : ](https://www.notion.so/Naver-Search-Colloquium-4edd7772dcec43bd94390e923d23da8f) **Conversational AI with Big Generative LM**
  - 챗봇과 같은 대화에서는 시간에 따라 변화하는 대답( 날씨, 미세먼지 ,나이 등등..) 이 있고 변하지 않는 대답을 구분해서 대답해줌.
  - 더 자연스러운 대화를 위한 연구를 진행함.

- [NLP papago : ](https://www.notion.so/Naver-Search-Colloquium-4edd7772dcec43bd94390e923d23da8f) **Meta-Learning for the low-resource domain**
  - 현재 일상대화에서의 번역은 잘 사용되지만
  - 특정 도메인에서의 번역은 잘 사용하지 않음.
  - 도메인 전문 번역기
  - 번역을 위한 코퍼스를 많이 학습하면 되지만 코퍼스가 많이 없을때는 어떻게 할까?
  - Source domain , Target domain, Shared Kneoledge

- [NLP Search : ](https://www.notion.so/Naver-Search-Colloquium-4edd7772dcec43bd94390e923d23da8f) **Search Applications with Big Generative LM**
  - 검색 시스템
  - Null-query 유형 : 사용자 검색 질의에 검색 내용을 찾지 못한 경우 다른 질의로 바꿔서 검색
      - 오타가 있는 경우
      - 띄어쓰기가 잘 안된 경우
      - 자소 단위가 섞여 있는 경우
      - 잘못된 정보를 사용하는 경우
  - SERP1 Summarization : 검색 결과 요약
      - Abstract summariztion에서 발생하는 Faithfulness문제
      - 요약 대상의 문서가 많고 길어서 단일 모델의 입력으로 사용하기에 한계
  - Shopping Review Summarization : 리뷰 취합해서 요약
      - 리뷰 클러스터링 진행
      - 대표 리뷰 추출 & 한줄 요약
  - Free-form QuestionAnswering : 자유 대화
