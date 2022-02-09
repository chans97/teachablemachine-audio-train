### 연구 목적

구글의 teachablemachine의 오디오 기계학습(지도학습)을 통해서 경상도 지역의 방언을 표준어와 구분할 수 있을지 확인하는 것에 목적이 있다.

학습데이터는 경상도 지역 남자 6명, 경상도 지역 여자 20명으로 그 수가 적다.

이 연구를 활용해서, "경상도에서 살아남기" 서비스에 AI 판별 기능을 적용할지 판단하고자 한다.

---

### 2022-02-09 연구 결과

억양 그 음높낮이보다는 음색, 발성에 더 영향을 많이 받는다.

그렇기 때문에, 각 문장에 대한 차이는 크게 보이지 않는다.( 발성, 음색이 더 중요하기 때문)

데이터 학습에 사용된 사람들을 기반으로는 높은 정확도를 보이나 실제 사용에서의 정확도는 의문이다.

하지만 실제 데이터를 직접 들어보니 서울사람들의 음색 발성과 경상도 사람들의 음색 발성 자체가 차이가 나기 때문에 유의미하게 두 집단을 판별할 수도 있겠다는 생각이 들었다.(문장간 차이는 유의미하지 않음) => 데이터의 양의 많다면 충분히 가능하다.

---

### 사용방법

start 버튼을 누르고 기다린다.

음성녹음을 통해 발화를 녹음하면, 실시간으로 데이터를 판별한다.

1-native-man : 경상도 남자

1-native-woman : 경상도 여자

1-seoul-man : 서울 남자

1-seoul-woman : 서울 여자

배경 소음 : 배경 소음
