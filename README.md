![image](https://user-images.githubusercontent.com/117002193/224100857-b218fbc7-3a12-4a27-a1df-1bbba5b748bc.png)

(이미지 : 셔터스톡)

<br>

<h1>🚀  Mini-Project-3  🚀</h1>

<p>캐글 Spaceship Titanic 예측 대회 참여</p>

<p>데이터 전처리에 많은 시간을 소요</p><hr>


<h2>🛸 전처리 요약 🛸</h2>

① Cabin, Vip, Homeplanet, CryoSleep, Destination  →  XGBClassifier로 예측

② Age  →  중위값 27 

③ Name  →  남녀 (2 분류)

④ PassengerId  →  단체 여행객, 개인 여행객 (2 분류)

⑤ RoomService, FoodCourt, ShoppingMall, Spa, VRDeck  →  Rich, Middle Class, Poor (3 분류) <hr>


<h2>🛰️ 사용한 알고리즘 🛰️</h2>

XGBClassifier

- HyperOPT를 사용하여 구한 최적의 파라미터 사용



