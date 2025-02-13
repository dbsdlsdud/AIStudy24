# AIStudy24
파이썬을 이용한 머신러닝 딥러닝 학습용

* [Matplotlib Tutorial - 파이썬으로 데이터 시각화하기](https://wikidocs.net/book/5011)
* [sklearn의 train_test_split() 사용법](https://blog.naver.com/siniphia/221396370872)
* [Colors,Line,Marker 종류](https://github.com/dbsdlsdud/AIStudy24/blob/02a197cbe80d7f3d977c1a08809bc6e6e02330d8/Colors_Line_Marker.ipynb)
* [한국어 형태소 분석 기초](https://velog.io/@hunterhunter/%ED%95%9C%EA%B5%AD%EC%96%B4-%ED%98%95%ED%83%9C%EC%86%8C-%EB%B6%84%EC%84%9D-%EA%B8%B0%EC%B4%88)
* [패딩하는 법](https://yeko90.tistory.com/entry/keras-how-to-padding-with-padsequences)
* [원-핫 인코딩](https://wikidocs.net/22647)
* [임베딩](https://casa-de-feel.tistory.com/28)
* [텍스트 전처리](https://wikidocs.net/21694)


# 머신러닝

[시나리오1]

AI 활용하는 기법 학습
 
1. MBC상점에서 앱마켓을 운영한다.
2. 앱마켓에서 살아있는 생선을 팔기 시작했다.
3. 물류센터에서 생선을 고르는 직원이 있는데 생선이름을 외우지 못했다.
4. 생선의 종류는 도미, 곤들매기, 농어, 강꼬치고기, 빙어, 송어 등등

AI미션 : 생선의 길이가 30cm이상이면 도미

* 24/12/30 [머신러닝_생선길이학습](https://github.com/dbsdlsdud/AIStudy24/blob/master/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D_%EC%83%9D%EC%84%A0%EA%B8%B8%EC%9D%B4%ED%95%99%EC%8A%B5.ipynb) / [훈련세트_테스트세트](https://github.com/dbsdlsdud/AIStudy24/blob/9262a678ff1240c4201bc00dd0582792062504c4/%ED%9B%88%EB%A0%A8%EC%84%B8%ED%8A%B8_%ED%85%8C%EC%8A%A4%ED%8A%B8%EC%84%B8%ED%8A%B8.ipynb)
* 24/12/31 [데이터_전처리학습](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EB%8D%B0%EC%9D%B4%ED%84%B0_%EC%A0%84%EC%B2%98%EB%A6%AC%ED%95%99%EC%8A%B5.ipynb)

***

[시나리오2]

이웃회귀를 통한 물고기 무게 예측

1. 여름에 농어철로 농어 주문이 크게 늘었다.
2. MBC마켓에서 업계최초로 농어를 무게 단위로 판매하려고 한다.
3. 무게단위로 판매하려면 가격 측정도 원활하고 고객도 합리적으로 판단 할 수 있다.
4. 공급처에서 생성 무게를 잘못 측정해서 보낼 경우 농어의 무게를 재측정해야 한다.

다른 데이터는 정상범위가 있으니 예측할 수 있을까? 에 대한 문제
예측 방법 : 회귀 -> 샘플 데이터가 필요하다 (외부에서 56개의 샘플을 받아 처리할 것)

지도학습은 크게 2가지로 나눠진다.
1. 분류(2진분류)
2. 회귀(예측 : 확률(임의의 어떤 숫자로 예측)) : 두 변수 사이에 상관관계 분석

* 24/12/31 [이웃회귀](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%9D%B4%EC%9B%83%ED%9A%8C%EA%B7%80.ipynb)
* 25/01/02 [k_최근접한계](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/k_%EC%B5%9C%EA%B7%BC%EC%A0%91%ED%95%9C%EA%B3%84.ipynb) / [다중회귀](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EB%8B%A4%EC%A4%91%ED%9A%8C%EA%B7%80.ipynb)

***

[시나리오3]

럭키백 확률 표시하기

1. MBC쇼핑몰에서 럭키백을 판매하기로 했다.
2. 럭키백에 생선이 들어있는데 7가지 종류의 생선이 랜덤하게 들어있다.
3. 럭키백에서 어떤 생선이 나올지 7가지 종류의 생선에 대한 확률이 필요하다.

* 25/01/03 [로지스틱회귀_소프트맥스](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EB%A1%9C%EC%A7%80%EC%8A%A4%ED%8B%B1%ED%9A%8C%EA%B7%80_%EC%86%8C%ED%94%84%ED%8A%B8%EB%A7%A5%EC%8A%A4.ipynb)
* 25/01/06 [확률적경사하강법](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%ED%99%95%EB%A5%A0%EC%A0%81%EA%B2%BD%EC%82%AC%ED%95%98%EA%B0%95%EB%B2%95.ipynb)

***

[시나리오4]

로지스틱 회귀 모델을 적용하여 와인 종류 구별하기

1. MBC마켓에서 신상품으로 캔 와인을 판매하려고 한다.
2. 주류는 온라인 판매 불가, 온라인 예약 후 오프라인 매장에서 구매 유도
3. 입고된 와인을 보니 어떤 와인인지 구분이 안 되어있다.
4. 구분 방법 : 캔에 인쇄된 (알콜도수, 당도, pH) ->  값으로 와인 종류 구별
5. 품질 확인용으로 뜯은 테스트용 캔을 데이터로 활용

* 25/01/06 [결정트리](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EA%B2%B0%EC%A0%95%ED%8A%B8%EB%A6%AC.ipynb)
* 25/01/07 [교차검증_그리드서치](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EA%B5%90%EC%B0%A8%EA%B2%80%EC%A6%9D_%EA%B7%B8%EB%A6%AC%EB%93%9C%EC%84%9C%EC%B9%98.ipynb) / [트리와앙상블](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%ED%8A%B8%EB%A6%AC%EC%99%80%EC%95%99%EC%83%81%EB%B8%94.ipynb)

# 딥러닝

[시나리오1]

비지도 학습(Unsupervised Learning)을 이용한 분류 -> 사람이 가르쳐주지 않아도 데이터에 있는 무언가를 학습한다.

사진의 픽셀값을 모두 평균내면 비슷한 과일끼리 모일까? -> 과일사진 300개 준비 후 분류

1. MBC마켓에서 이벤트 진행
2. 본인이 구매한 과일 사진을 홈페이지에 업로드시 추첨을 통해 상품 제공
3. 고객이 올린 사진을 학습해서 과일 사진을 분류해보기

* 25/01/08 [군집알고리즘](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EA%B5%B0%EC%A7%91%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98.ipynb) / [k_평균](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/k_%ED%8F%89%EA%B7%A0.ipynb) / [주성분분석](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%A3%BC%EC%84%B1%EB%B6%84%EB%B6%84%EC%84%9D.ipynb)

***

[시나리오2]

1. MBC마켓에서 럭키백을 패션분야에 접목 시키려고 한다.
2. 패션 분야이기 때문에 상품 개수는 늘어나고 어종이 아닌 일반 잡화용으로 제공한다.

* 25/01/09 [인공신경망](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%9D%B8%EA%B3%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb) / [심층신경망](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%8B%AC%EC%B8%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb)
* 25/01/10 [심층신경망](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%8B%AC%EC%B8%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb) / [인공신경망기타도구](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%9D%B8%EA%B3%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D%EA%B8%B0%ED%83%80%EB%8F%84%EA%B5%AC.ipynb)
* 25/01/13 [합성곱신경망](https://github.com/dbsdlsdud/AIStudy24/blob/4dacb9050b6bbf65fad931303fc99907bffcf8c0/%ED%95%A9%EC%84%B1%EA%B3%B1%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb) / [합성곱시각화](https://github.com/dbsdlsdud/AIStudy24/blob/4dacb9050b6bbf65fad931303fc99907bffcf8c0/%ED%95%A9%EC%84%B1%EA%B3%B1%EC%8B%9C%EA%B0%81%ED%99%94.ipynb)

***

[시나리오3]

댓글을 분석하는 기법 연구

1. MBC마켓이 AI를 이용해 많은 부분이 개선됐고 이벤트도 성공적으로 결론이 났다.
2. 요즘 상품에 대한 댓글 이슈가 있어서 댓글을 보고 좋은 상품인지 개선해야 될 상품인지 분석하고 싶어 한다.

* 25/01/14 [순차데이터와 순환신경망](https://github.com/dbsdlsdud/AIStudy24/blob/9c1e616a262f2692f0ec0849208b60e4d41bd838/%EC%88%9C%EC%B0%A8%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%99%80%EC%88%9C%ED%99%98%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb)
* 25/01/15 [LSTM_GRU](https://github.com/dbsdlsdud/AIStudy24/blob/9c1e616a262f2692f0ec0849208b60e4d41bd838/LSTM_GRU.ipynb)
