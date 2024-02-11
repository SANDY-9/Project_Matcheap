# 서울맛칩
서울시에서 선정한 착한가격업소 정보앱(App) 서비스

<img src="./img/img.gif">

</br>

## 개발목표
1. **네이버 지도 API** 사용과 **GPS** 연동
2. 카카오톡, 네이버 **OAuth** 소셜 로그인 연동
3. Shared Preferences, **Room Database**를 이용한 로컬 데이터 처리, 미리 채우기
4. **Retrofit2 + OkhttpClient**를 이용한 REST 요청
5. 라이브데이터(LiveData)와 **옵저버(Observer) 패턴**의 사용

</br>

## 주요기능
화면|내용|기능|개발자
------|---|---|---
로그인|소셜 로그인|- 카카오 로그인</br>- 네이버 로그|임선미
홈|카테고리별 착한가격업소|- 카테고리별(지역, 종류)에 따라 착한가격업소 정보 제공</br>- 거리순/평점순 정렬|김혁주
지도|서울시 착한가격업소 지도|- 네이버 지도 SDK를 이용한 착한가격업소 위치 지도</br>- 필터 : 종류, 거리|임선미
검색|착한가격업소 검색|- 검색어 히스토리 저장<br>- 검색어 자동완성</br>- 가게명, 메뉴명 부분검색 지원 |임선미
업소 상세화면|착한가격업소 상세 정보 화면|- 업소 정보 제공</br>- 길찾기 제공</br>- SNS 공유하기</br>- 찜하기</br>- 사용자 리뷰|임선미
마이페이지|마이페이지|- 로그인 정보</br>- 내 활동내역 정보, 리뷰 관리</br>- 찜 목록 관리</br>|송태수
</br>

## Skills
<img src="https://img.shields.io/badge/Android-34A853?style=flat&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=Kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/RESTful API-000000?style=flat&logo=&logoColor=000000"/> 
+ DataBinding, ViewBinding
+ Room
+ Retrofit2, Rxjava
+ Coroutine
+ Naver Map SDK
+ FusedLocaionProvider
+ Naver, Kakao OAuth2.0 Login SDK
+ Glide
+ UI : ConstaintLayout, ViewPager2, TabLayout, RecyclerView

</br>

## Links
+ 프로젝트 팀 개발 노션 페이지 : [링크](https://reflective-goose-443.notion.site/fb5211c06c454920b16db11a16ce7707?pvs=4)</br>
+ 서울맛칩(1.0) 시연영상 : [보러가기](https://drive.google.com/file/d/1hn-nxNK-qp2pk6rj4MP51ntXwZqwFqvV/view)</br>
+ 서울맛칩 리팩토링(2.0) 버전 : [서울맛칩 리팩토링 코드 보러가기](https://github.com/SANDY-9/Project_SeoulMatcheap2.0)</br>
</br>
