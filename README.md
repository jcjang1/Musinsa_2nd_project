# Musinsa_2nd_project
큐레이팅 기반 시즌별 상품 추천 / 리뷰 긍부정 분석

- 큐레이팅
  - [ MUSINSA -> 매거진 -> 큐레이팅 ] 큐레이팅 내용을, 무신사 자체 브렌드인 무신사 스텐다드 상품 설명을 크롤링
  - tf-idf를 통해 크롤링한 큐레이팅 내용과 상품 설명의 빈도 비교를 통해 상품 추천
  - 결과
  <img wight="80%" src="https://user-images.githubusercontent.com/95558633/205137066-33ac543e-3a2b-4d5c-8a88-d17a1337b695.png">
  
  
- 후기
  - 상품 리뷰 내용을 크롤링하여 긍정적인 내용인지, 부정적인 내용인지 판단하기 위해 Logistic regression 모델로 학습
  - 긍/부정 댓글의 데이터 불균형을 over/under sampling을 통해 해결해보고자 함 
  
  
- 기타 코드
  - 일부 작업을 편리하게 하기 위해 작성한 코드
