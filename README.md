# Recommendation-System

# 추천 알고리즘의 종류
* 사용되는 정보 기준
1. CF(Collaborative Filtering) : 협업필터링. 사용자의 행동, 취향 정보로 비슷한 취향을 가진 사람을 찾아 추천에 이용
2. CB(Content Based Filtering) : 내용기반 필터링. 아이템에 대한 정보로 비슷한 아이템을 찾아내 추천에 이용
3. KB(Knowledge Based Recommender) : 해당 도메인 전문가의 지식을 사용해 적절한 아이템을 추천(한혜연의 옷 추천)
<img src="https://user-images.githubusercontent.com/46089347/67144796-eb2b5a00-f2b5-11e9-9cb9-b6dfaeedc058.png" width="40%">
4. Hybrid : 하나 이상의 추천 알고리즘을 결합해 추천

* 분석 방법 기준
1. Similarity metrics(correlation, cosine, jaccard, Tanimoto)
: CF, CB, KB 어디나 기본적으로 사용
