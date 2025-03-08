# ☂️ K 히트 콘텐츠 리뷰 NLP 분석 (2024)
`#데이터분석` `#NLP` `#Crawling`
**‘파묘’, ‘선재업고튀어’ 콘텐츠 리뷰

###  **💁🏻주요 역할**
- 데이터 크롤링 및 전처리
- 리뷰 데이터를 Tokenization하여 중요한 단어를 추출
- 토픽 모델링(LDA) 기법을 통해 리뷰에서 나타나는 주요 주제를 분석
- 리뷰 별로 가장 중요한 토픽과 비중을 시각화 및 요약

### ☀️ 분석 내용
- LDA Topic Modeling 결과
  ![Image](https://github.com/user-attachments/assets/4ecdb562-622b-4c35-90ba-7577ec96172a)
  
- Pyldavis 시각화
  ![Image](https://github.com/user-attachments/assets/030205b5-0387-4754-b941-672dac01d2f5)

**1. Intertopic Distance Map (PC1 vs. PC2)**
- PC1과 PC2는 차원 축소 기법인 MDS (Multidimensional Scaling)을 사용하여 시각적으로 토픽 간 거리를 표시
- 토픽 간 거리는 주제들이 서로 얼마나 유사도를 나타냄

**2. Top-30 Most Relevant Terms for Topic**
- 가장 관련이 깊은 30개의 단어를 나열하며 해당 주제에서 가장 중요한 단어들을 표시
- 빨간색 막대: 토픽에서 해당 단어의 중요도
- 파란색 막대: 해당 단어의 전체 문서에서의 빈도

  ### 🎯 결론
사용자 리뷰에서 중요한 주제를 추출함으로써, 콘텐츠 제작에 있어 사용자의 주요 피드백 및 강점과 약점을 파악하여 추후 마케팅 전략과 후속작 제작 방향 설정이 기여할 수 있습니다!
![Image](https://github.com/user-attachments/assets/fe13edb2-aa43-4b18-aaa4-d8a862dbf605)

![Image](https://github.com/user-attachments/assets/481285a6-8857-4a1a-87a8-9d9f35b00b51)

드라마 ‘’선재업고튀어’ 리뷰에서 가장 비중이 높은 주제는 **"스토리의 몰입감"**, **"캐릭터의 매력"**, **"감정적 반응(설렘, 감동)"** 등으로 요약되었고, 영화 '파묘' 리뷰에서 가장 비중이 높은 주제는 **"긴장감 넘치는 스토리라인과 서스펜스"**, **"특유의 미장센과 음산한 분위기"**, **"주요 배우의 몰입도 높은 연기력"** 등으로 요약되었습니다. 
