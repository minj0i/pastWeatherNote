# 개발 후기
## 현황
현재는 빌드까지 완료한 후 구글플레이스토어에 검토요청한 상태입니다.   

사용가능한 기능은 다음과 같습니다.
1. 달력형으로 과거날씨 조회하기 (도시/날짜 선택)
2. 현재위치를 받아 어제날씨와 비교하기   
3. 광고
   
기상청 공공데이터포털에서 제공하는 과거 날씨 관련 API를 사용하였습니다.   
기상청데이터로 모든 것을 사용하고 싶었으나,   
위치정보를 받아 기상청데이터를 사용하고자한다면   
```
위치정보의 보호 및 이용 등에 관한 법률'에 따라 방송통신위원회에 '위치정보서비스 허가'를 받거나 '위치기반 서비스사업 신고'를 하여야 합니다. 
```
라는 걸 보고 현재위치를 받아 어제날씨와 비교하는 API는   
외국사이트인 openweathermap에서 제공하는 API를 사용하게 되었습니다.

구글애드몹으로 광고를 붙였습니다.

## 추후계획
구글로그인제공 및 로그인 사용자에게는 자주찾는 도시를 저장할 수 있도록 제공할 예정입니다.   
따라서 파이어베이스 로그인/인증을 사용할 계획입니다.   
기기에 따라 발생하는 디자인이슈를 확인하고 처리할 계획입니다.

## 후기
처음에는 Note도 써가며 진행할 생각이었습니다만,   
짬짬이 시간을 내어 평일 일과가 끝나고 퇴근 후 개발을 하다보니 에러를 해결하고 다음 개발을 진행하기 바빠 제대로 일지를 작성하지 못했습니다.   
다음개발 시에는 좀 더 꼼꼼히 작성해 볼 생각입니다.   
처음 만들었던 앱에 비해 디자인에 좀 더 신경을 많이 썼습니다.   
확실히 예쁘니 남들에게 자랑할 수 있어진 것 같습니다.(광고 눌러달라고 하기에도 수월해졌어요.)    
매번 처음 생각보다 실제로 개발을 진행하면서 구현범위를 줄이게 되는 것 같습니다.   
원하는 목표만큼 구현할 수 있도록 실력을 더 키우고, 더 성실하게 해야할 것 같습니다.   
그럼에도 불구하고 역시나, 완성을 하고 나니 뿌듯합니다(^^)