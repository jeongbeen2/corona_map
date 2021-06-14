# Coronaga

- Coronaga는 COVID-19에 대한 다양한 정보를 제공하는 어플리케이션 입니다.
- corona API를 이용해서 국내 코로나 환자에 대한 정보를 받아오고, 깔끔한 UI를 통해서 한눈에 파악할 수 있습니다.
- 선별 진료소에 대한 API와 kakao MAP API를 이용해 선별 진료소에 대한 위치정보를 바로 받아올 수 있습니다.
- 백신에 관한 간단한 정보를 홈 화면에 배치했습니다.

- 추후, 아래와 같은 정보들을 추가할 예정입니다.
- [ ] 코로나 관련 뉴스 기사
- [ ] 코로나 환자에 대한 정보를 그래프로 시각화
- [ ] 백신에 대한 정보 페이지

## 1. 홈 화면에 백신에 대한 카드뉴스

![스크린샷 2021-06-14 오후 11 47 52](https://user-images.githubusercontent.com/68345069/121913468-633c7280-cd6c-11eb-8a04-7ccd13142a9b.png)

홈 화면에는 카드뉴스를 업로드 함으로써, 가볍게 보고 읽을 수 있는 자료를 준비했습니다.

## 2. 국내 카운팅 및 시도별 발생동향

![image](https://user-images.githubusercontent.com/68345069/121811007-e347d700-cc9d-11eb-8861-82905f511e46.png)

코로나 관련 데이터(확진자, 완치자 등)를 수치화하여 전국구로 나타냈습니다.

## 3. 선별 진료소 안내

![스크린샷 2021-06-14 오후 11 48 18](https://user-images.githubusercontent.com/68345069/121912650-b8c44f80-cd6b-11eb-9695-3a5efe7ab8c7.png)

![스크린샷 2021-06-14 오후 11 48 44](https://user-images.githubusercontent.com/68345069/121912719-c679d500-cd6b-11eb-9ec4-04093e0aaf01.png)

경기도내에 있는 인증된 선별 진료소를 검색할 수 있습니다.

## 사용한 API

- 국내 코로나 동향 API
  https://github.com/dhlife09/Corona-19-API
- 선별진료소 API
  https://data.gg.go.kr/portal/data/service/selectServicePage.do?page=1&rows=10&sortColumn=&sortDirection=&infId=461Q599QLK8UTE14E3LW12837248&infSeq=3&order=&loc=
- 카카오 Map API
  https://apis.map.kakao.com/
