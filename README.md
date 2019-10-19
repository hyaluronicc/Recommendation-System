# Recommendation-System

# 추천 알고리즘의 종류
* 사용되는 정보 기준
1. CF(Collaborative Filtering) : 협업필터링. 사용자의 행동, 취향 정보로 비슷한 취향을 가진 사람을 찾아 추천에 이용. 데이터가 다양하게 분포되어 있어야 함. 
2. CB(Content Based Filtering) : 내용기반 필터링. 아이템에 대한 정보로 비슷한 아이템을 찾아내 추천에 이용. 아이템 정보가 많아야 함.
3. KB(Knowledge Based Recommender) : 해당 도메인 전문가의 지식을 사용해 적절한 아이템을 추천(한혜연의 옷 추천). preference가 다소 약함. 
<img src="https://user-images.githubusercontent.com/46089347/67144796-eb2b5a00-f2b5-11e9-9cb9-b6dfaeedc058.png" width="40%">
4. Hybrid : 하나 이상의 추천 알고리즘을 결합해 추천

* 분석 방법 기준
1. Similarity metrics(correlation, cosine, jaccard, Tanimoto): CF, CB, KB 어디나 기본적으로 사용
2. KNN, MF(Matrix Factorization), SVD ++ : CF에 주로 사용
3. tfidf, Word2Vec : CB에 주로 사용
4. Deep Learning : CF, CB, KB 등 어디나 사용 가능

> RS는 각 item에 대한 각 사용자의 예상 선호도를 추정하는 것
