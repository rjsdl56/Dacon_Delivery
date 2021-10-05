# 요약정리

### 주제 : 포스트 코로나 배달 문화 변화 및 소상공인 자력 활성화 방안

- 진행기간 : 2021.08.11 ~ 2021.08.25
- 프로젝트 유형 : 팀 프로젝트
- 팀원 : 박성준, 김수인, 김시현

### 데이터

- [Dacon](https://dacon.io/competitions/official/235753/data)
  - KT빅데이터플랫폼
    - dlvr_call.csv
    - popl.csv
    - StarupOrClosing_Shop_ver2.csv
    - StartupOrClosing_Region_ver2.csv
  - DS4C
    - COVID_19
- [KT빅데이터플랫폼](https://bdp.kt.co.kr/invoke/SOKBP0701/?srchRsltsrch=주문지역)
  - 주문지역 주거 특성
- 기타
  - [서울 시군구 경계](https://mkjjo.github.io/python/2019/08/18/seoul_map.html)
  - [공시지가](https://www.data.go.kr/data/15004246/fileData.do)
  - [일반음식점](https://www.localdata.go.kr/devcenter/dataDown.do?menuNo=20001)

### 박성준 주요 수행사항

- 기초 아이디어 제시
- 데이터 EDA & 전처리
- 코로나 영향력 파악 및 배달건수와의 상관관계 파악
- 공시지가 및 폐업수 동적시각화
- 파생변수를 이용한 시각화
- 배달건수, 거리, 배달시간 상관관계 분석
- 배달금액 시각화 및 창업 우선순위 지역 선정

### 코드 설명

- DACON_PK_1
  - 논문에서 진행되었던 배달데이터 전처리 내용을 본 공모전 데이터 범위에 맞게 진행한 파일입니다.
- DACON_PK_2
  - 해당 내용은 데이콘에서 제공한 코로나 데이터를 간단히 살펴본 내용입니다.
  - 모든 데이터가 누적데이터 형식으로 되어있으며 일일 파생변수를 생성한 코드가 있습니다.
  - 사용할 데이터를 선별해놓았으며, 각 데이터에 대한 간단한 진행계획이 적혀 있습니다.
- DACON_PK_3
  - 해당 내용은 데이콘에서 제공한 창폐업 데이터를 간단히 살펴본 내용입니다.
  - 배달데이터에서 살펴본 바와 달리, 압도적으로 폐업의 수가 많은 것을 확인했습니다.
  - 이후 공시지가 데이터와 연결하여 시각화를 진행할 예정입니다.
  - 각 데이터에 대한 간단한 진행계획이 주석으로 적혀져 있습니다.
- DACON_PK_4
  - 해당 내용은 행정동별 공시지가를 파악하여 동적 지도 시각화를 진행하려고 했던 파일입니다.
- DACON_PK_5
  - 해당 내용은 지금까지 진행한 전처리와 시각화를 모아놓은 것입니다.
  - 이 내용을 기반으로 Dacon 제출코드를 작성합니다.
- 야근원정대_버거킹데이
  - 해당 파일이 데이콘 기초자료로 활용될 ipynb 파일입니다.
  - 내부에 사용된 이미지와 내용은 repository에 업로드된 이미지 자료와 논문을 참고하시면 될 것 같습니다.
- 야근원정대_오늘 저녁은 치킨이닭!
  - 해당 내용은 팀원과 함께 협업하기 위해 정리된 파일입니다.
  - 팀원의 코드를 해당 버전에 맞춰 진행할 생각입니다.
- 야근원정대_'안' 고독한박명수방
  - 해당 내용은 Dacon 제출을 위해 가독성을 높인 파일입니다.
  - 배달수수료에 대한 분석이 추가되었습니다.
- 야근원정대_최종본초안
  - 임의로 팀원의 코드를 통합한 초안입니다.
- 통합본_semi_final
  - 모든 코드를 통합한 뒤, 재점검을 위한 파일입니다.
- 통합본_final
  - 모든 코드를 재점검한 뒤, 스토리텔링을 위한 파일입니다.
- 명수옹과 함께하는 코로나 시대 배달 문화 분석
  - Dacon 시범 제출용 파일입니다.
- 명수옹과 함께하는 코로나 시대 배달 문화 분석_210824
  - Dacon 제출 전 팀원 코드 리뷰를 위한 파일입니다.
- 명수옹과 함께하는 코로나 시대 배달 문화 분석_210825
  - Dacon 최종 제출 파일입니다.