# AIStudy24
파이썬을 이용한 머신러닝 딥러닝 학습용

* [Matplotlib Tutorial - 파이썬으로 데이터 시각화하기](https://wikidocs.net/book/5011)
* [Colors,Line,Marker 종류](https://github.com/dbsdlsdud/AIStudy24/blob/02a197cbe80d7f3d977c1a08809bc6e6e02330d8/Colors_Line_Marker.ipynb)

# 머신러닝

[시나리오1]
(AI 활용하는 기법 학습
 
1. MBC상점에서 앱마켓을 운영한다.
2. 앱마켓에서 살아있는 생선을 팔기 시작했다.
3. 물류센터에서 생선을 고르는 직원이 있는데 생선이름을 외우지 못했다.
4. 생선의 종류는 도미, 곤들매기, 농어, 강꼬치고기, 빙어, 송어 등등

AI미션 : 생선의 길이가 30cm이상이면 도미)

* 24/12/30 [머신러닝_생선길이학습](https://github.com/dbsdlsdud/AIStudy24/blob/master/%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D_%EC%83%9D%EC%84%A0%EA%B8%B8%EC%9D%B4%ED%95%99%EC%8A%B5.ipynb) / [훈련세트_테스트세트](https://github.com/dbsdlsdud/AIStudy24/blob/9262a678ff1240c4201bc00dd0582792062504c4/%ED%9B%88%EB%A0%A8%EC%84%B8%ED%8A%B8_%ED%85%8C%EC%8A%A4%ED%8A%B8%EC%84%B8%ED%8A%B8.ipynb)
* 24/12/31 [데이터_전처리학습](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EB%8D%B0%EC%9D%B4%ED%84%B0_%EC%A0%84%EC%B2%98%EB%A6%AC%ED%95%99%EC%8A%B5.ipynb)

***

[시나리오2]
(이웃회귀를 통한 물고기 무게 예측

1. 여름에 농어철로 농어 주문이 크게 늘었다.
2. MBC마켓에서 업계최초로 농어를 무게 단위로 판매하려고 한다.
3. 무게단위로 판매하려면 가격 측정도 원활하고 고객도 합리적으로 판단 할 수 있다.
4. 공급처에서 생성 무게를 잘못 측정해서 보낼 경우 농어의 무게를 재측정해야 한다.

다른 데이터는 정상범위가 있으니 예측할 수 있을까? 에 대한 문제
예측 방법 : 회귀 -> 샘플 데이터가 필요하다 (외부에서 56개의 샘플을 받아 처리할 것)

지도학습은 크게 2가지로 나눠진다.
1. 분류(2진분류)
2. 회귀(예측 : 확률(임의의 어떤 숫자로 예측)) : 두 변수 사이에 상관관계 분석)

* 24/12/31[이웃회귀](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%9D%B4%EC%9B%83%ED%9A%8C%EA%B7%80.ipynb)
* 25/01/02 [k_최근접한계](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/k_%EC%B5%9C%EA%B7%BC%EC%A0%91%ED%95%9C%EA%B3%84.ipynb) / [다중회귀](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EB%8B%A4%EC%A4%91%ED%9A%8C%EA%B7%80.ipynb)
* 25/01/03 [로지스틱회귀_소프트맥스](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EB%A1%9C%EC%A7%80%EC%8A%A4%ED%8B%B1%ED%9A%8C%EA%B7%80_%EC%86%8C%ED%94%84%ED%8A%B8%EB%A7%A5%EC%8A%A4.ipynb)
* 25/01/06 [확률적경사하강법](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%ED%99%95%EB%A5%A0%EC%A0%81%EA%B2%BD%EC%82%AC%ED%95%98%EA%B0%95%EB%B2%95.ipynb) / [결정트리](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EA%B2%B0%EC%A0%95%ED%8A%B8%EB%A6%AC.ipynb)
* 25/01/07 [교차검증_그리드서치](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EA%B5%90%EC%B0%A8%EA%B2%80%EC%A6%9D_%EA%B7%B8%EB%A6%AC%EB%93%9C%EC%84%9C%EC%B9%98.ipynb) / [트리와앙상블](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%ED%8A%B8%EB%A6%AC%EC%99%80%EC%95%99%EC%83%81%EB%B8%94.ipynb)

# 딥러닝

* 25/01/08 [군집알고리즘](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EA%B5%B0%EC%A7%91%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98.ipynb) / [k_평균](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/k_%ED%8F%89%EA%B7%A0.ipynb) / [주성분분석](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%A3%BC%EC%84%B1%EB%B6%84%EB%B6%84%EC%84%9D.ipynb)
* 25/01/09 [인공신경망](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%9D%B8%EA%B3%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb) / [심층신경망](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%8B%AC%EC%B8%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb)
* 25/01/10 [심층신경망](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%8B%AC%EC%B8%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D.ipynb) / [인공신경망기타도구](https://github.com/dbsdlsdud/AIStudy24/blob/033ba5d90ad72371147e63f24dfedbe7f159082e/%EC%9D%B8%EA%B3%B5%EC%8B%A0%EA%B2%BD%EB%A7%9D%EA%B8%B0%ED%83%80%EB%8F%84%EA%B5%AC.ipynb)
