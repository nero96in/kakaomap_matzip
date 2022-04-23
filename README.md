# 카카오맵 즐겨찾기로 표현된 "전국 맛집 대망라" 

오래전부터 인터넷에 떠돌고 있는 93개 카테고리의 맛집 목록을 알게 되었다. 나름 구조적으로 잘 정리되어 있는 목록이었는데, 카카오맵을 사용하는 사람들이 일일이 즐겨찾기에 입력하기에는 너무나 많은 양이어서 어느 정도의 처리 후 Kakaomap api와 내부 즐겨찾기 등록 매커니즘을 활용해 자동으로 맛집 검색 및 즐겨찾기 등록을 진행했다.

각 카테고리에는 세부 카테고리가 또 나름 정의되어 있었는데, 즐겨찾기 폴더는 100개까지 만들어지는 관계로 세부 카테고리는 각 맛집의 이름 앞부분에 적어 두었다. (세부카테고리 없으면 그냥 식당이름만 있음)

**잘못된 부분들도 많을거고 추가되지 않은 것들도 많을테니 참고바람! 조금씩 채워나갈 거예요**

## 사용 설명
> 읽기 귀찮다면 그냥 아래 맛집 카테고리에서 먹고 싶은 메뉴의 주소를 클릭하고 알아서 하면된다! :)
1. 먹고 싶은 메뉴를 생각해본다.
2. 카카오맵이 깔려있는지 확인한다. 없으면 깔기!
3. 아래 맛집 카테고리에서 메뉴에 해당하는게 있는지 확인하고 오른쪽 주소를 클릭한다.
4. 주소를 클릭하고 카카오맵과 연결한다.
5. 지도에 맛집을 표시하고 싶으면, 구독을 누르면 된다. 구독을 누르면 즐겨찾기 탭에서 구독된 즐겨찾기 폴더 오른쪽에 토글 버튼이 생기는데 그 토글 버튼을 ON 하면 지도에 표시가 된다.
6. 그리고 잘 쓰면 된다! (잘 썼다면 우측 상단에 별 눌러주세요 ㅎㅎ)

## 맛집 카테고리
01. 평양냉면 - http://kko.to/yCzXmVgpI
02. 메밀국수 (소바) - http://kko.to/Aw1nn_hSp
03. 막국수 - http://kko.to/G6YrqnooG
04. 콩국수 - http://kko.to/u8Rfld41G
05. 국밥 해장국 - http://kko.to/ymwUVaOVA
06. 설렁탕 - http://kko.to/s6aAkQPC3
07. 감자탕 - http://kko.to/3FpUHfyzn
08. 순대 - http://kko.to/UChvvJKVE
09. 닭볶음탕 - http://kko.to/-ZcpyaMky
10. 추어탕 - http://kko.to/I-z3UibVt
11. 육개장 - http://kko.to/38i9SSYVY
12. 대구탕 - http://kko.to/M1IEV3fiX
13. 김밥 - http://kko.to/aG8KK_IHy
14. 김치찌개 - http://kko.to/NFSz9daxH
15. 부대찌개 - http://kko.to/7b6Z_zlbE
16. 청국장 - http://kko.to/5YOqeEuFh
17. 된장 - http://kko.to/pPYEJbEdI
18. 간장게장 - http://kko.to/xHL87thzL
19. 삼계탕 - http://kko.to/XpBqSAQCw
20. 보쌈 - http://kko.to/DpH_PY3vA
21. 족발 - http://kko.to/d5m2B1Kpc
22. 치킨 - http://kko.to/XdL_C5-NJ
23. 돈까스 - http://kko.to/dQ3bLpF1o
24. 함박 스테이크 - http://kko.to/OZmYUAcWN
25. 떡볶이 - http://kko.to/YmcyE0Sl5
26. 라면 - http://kko.to/x5ahIGZZX
27. 라멘 - http://kko.to/kdWKjeBqn
28. 우동 - http://kko.to/ZNoV4tqqu
29. 튀김 - http://kko.to/ZvXvFG46e
30. 순두부, 두부 - http://kko.to/Hcsyfsltc
31. 피자 - http://kko.to/Y2cwMN4Go
32. 아이스크림, 젤라또 - http://kko.to/mqSCtfGk2
33. 갓포요리집 - http://kko.to/Syb0NlOnJ
34. 죽 - http://kko.to/ZQ80C6v7O
35. 덮밥, 백반, 벤또(도시락) - http://kko.to/n8oBozO4d
36. 꼬치구이, 로바다야끼 - http://kko.to/E5GCzBx0B
37. 냉동삼겹살 - http://kko.to/jNilPL_U-
38. 기사식당 - http://kko.to/drBbylbL1
39. 스테이크, BBQ - http://kko.to/y8Yt3tgoq
40. 칼국수 - http://kko.to/efQwacbOj
41. 수제맥주 맥주 맛있는 곳 - http://kko.to/5_cizjLCF
42. 아구찜 - http://kko.to/lS6njkz7J
43. 생선구이 & 조림 - http://kko.to/YUxi2SgcJ
44. 돼지갈비 - http://kko.to/bu8S9eG1T
45. 돼지고기 - http://kko.to/7MC_lCw4-
46. 유럽 음식 - http://kko.to/d012RTyDP
47. 중동 음식 - http://kko.to/gJ0-KYvPt
48. 아프리카 음식 - http://kko.to/wOntq7hCT
49. 북중남미 - http://kko.to/06Yjl1o_E
50. 아시아 음식 - http://kko.to/z_9TzKlF1
51. 기네스 - http://kko.to/YGh4n-ICv
52. 사케 - http://kko.to/vGC2QDfRG
53. 몰트 위스키 - http://kko.to/Xp4AbesU6
54. 칵테일 - http://kko.to/088Wpee-M
55. 막걸리 - http://kko.to/RiJg2QH5K
56. 중국집 - http://kko.to/yK9KtK7-P
57. 한국식 만두 - http://kko.to/Gg7SeNJI8
58. 수제비 - http://kko.to/fCj5KFvfF
59. 국수 - http://kko.to/zDMF0yEFA
60. 스시 - http://kko.to/VPJx6Oqdm
61. 해물탕 - http://kko.to/xsHIyvzfs
62. 갈비찜 - http://kko.to/o7sftgqza
63. 소고기 - http://kko.to/Qz7v8I7R3
64. 곱창 - http://kko.to/HSkNfRASh
65. 샤브샤브 - http://kko.to/VnBmEQ7fj
66. 낙지 오징어 - http://kko.to/QrGQR-pIr
67. 쭈꾸미 - http://kko.to/aKKv7HekF
68. 복어 - http://kko.to/41OoOJ87_
69. 장어 (민물장어/바다장어/갯장어/꼼장어) - http://kko.to/5mAfXQn-W
70. 보양 (염소/용봉탕/민어) - http://kko.to/XEfA7S01l
71. 양고기 - http://kko.to/fWZWXIoBC
72. 오리 (백숙/베이징덕 제외한 오리요리) - http://kko.to/ccZtDkF-0
73. 닭(치킨/삼계탕/닭도리탕X) - http://kko.to/u5FO2g8L0
74. Italian - http://kko.to/zYV1M9CFX
75. French - http://kko.to/3Col76765
76. Contemporary - http://kko.to/8RPzw2bPl
77. New Korean - http://kko.to/dzi8h_9al
78. Wine & Dine - http://kko.to/NTC_H49n2
79. Pasta - http://kko.to/kTgMP9vzh
80. 햄버거 - http://kko.to/hJXVgvyhN
81. 호텔 - http://kko.to/b2HA8itrz
82. 비빔밥 솥밥 - http://kko.to/p0wtInfda
83. 채식 - http://kko.to/FVLIr-Ht0
84. 참치 - http://kko.to/INFGiKgM-
85. 랍스터, 킹크랩, 대게 - http://kko.to/pKRqUiAFA
86. 남도 음식 - http://kko.to/dC9szwEsE
87. 횟집 - http://kko.to/0q9hfGcwC
88. 방송맛집 - http://kko.to/7kEB3sPY2
89. 서울 노포 식당 - http://kko.to/odjF4bKlc
90. 떡집 - http://kko.to/4y8LTC69A
91. 디저트 - http://kko.to/Avvb43KFm
92. 빵집 - http://kko.to/60mrvEcPw
93. 커피 - http://kko.to/KlZELk6IQ

## 만들어진 과정
* `matzip.txt`내의 맛집 리스트에서 "**정왕**동 **겁나맛집**"의 형태로 가공한 뒤 카카오맵에서 키워드로 검색 후 나오는 결과를 카테고리별로 구별하여 즐겨찾기에 등록했다. 가공 방식은 간단히 설명하면 다음과 같다.
    * 기본적으로 "-"를 기준으로 목록을 나누고 1번째("정왕동"), 3번째("겁나맛집")의 텍스트를 이어 붙여 검색한다.
    * "-"로 나누었을 때 나누어진 요소가 3개 미만이라면 1번째, 2번째 텍스트를 이어 붙여 검색한다. 두 요소가 같다면 둘 중 하나만 사용한다.
    * "-"로 나누지 않았다면, " "로 나누고 1번째, 2번째 요소를 이어 붙여 검색한다.
* 가공 후에 검색 결과가 다음의 경우라고 할 때, 즐겨찾기에 일단 추가되지 않았다.
    * 검색 결과가 5개 이상인 경우
    * 검색 결과가 없는 경우
* 즐겨찾기에 추가되지 않은 맛집 리스트는 `errors.json`에 기록되어 있고 추후 시간이 될 때, 추가되도록 할 것이다.

## 유의 사항
* 사람이 만든 목록을 자동화 하여 즐겨찾기를 제작한 것이기 때문에, 즐겨찾기에 있는 가게가 잘못 표시되었을 수 있다. 그럴 땐, 그 가게의 설명을 보고 스스로 다시 검색해보면 좀 더 정확한 결과가 나올 수 있으니 참고하자.
* 알아본 결과, 조금 오래된 자료라고 하니 이 점 참고하길 바란다. (2019년 4월이 필자가 확인한 가장 오래된 공유글이었다.)
* 맛집 리스트의 원작자가 이 글을 보거나 지인이라면 연락 주셨으면 좋겠다. (업데이트 하고 계신지 궁금합니다..!)
* 기타 피드백 대환영!