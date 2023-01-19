# ds-sa-cp2


## 1월 19일
### 회의 내용

- 협업 체계 구축 : 깃허브에 파일 올리면서 공유
    (참고자료)
    - https://xively.tistory.com/17
    - https://fomaios.tistory.com/entry/Git-Github-%EA%B0%99%EC%9D%80-%EC%A0%80%EC%9E%A5%EC%86%8C-%ED%95%A8%EA%BB%98-%EC%93%B0%EA%B8%B0feat%ED%98%91%EC%97%85%ED%95%98%EA%B8%B0
- 서로 진행한 시각화 공유

- 데이터 용량 줄이기(전현아)
    - int64 → int32 / object → category
    
- 베이스라인(신동휘)
    - rating 최빈값 4로 타겟값 설정
    
- 추천 모델링
    - 타겟값 rating을 예측하는 모델을 만들어 유저마다 각각 영화 평점을 예측해 내림차순으로 정렬해 높은 점수를 얻은 상위 몇 개의 영화 추천해주기
    - 신동휘(CB)
    - 전현아(CF)
    - 화요일까지 만들어서 서로 알려주기
    
- 평가지표
    - MAE, RMSE를 사용
    - 우선순위는 RMSE가 낮은 모델
    (참고자료)
    - https://sungkee-book.tistory.com/11
