# errors

> 20210106
'emulator-5554' (emulator-5554): Device is OFFLINE.  
라는 에러가 뜨는데 도대체 뭔지 계속 헤맸다.  
[stackoverflow](https://stackoverflow.com/questions/3152681/android-emulator-5554-offline)에서 보니  
wipe data를 하라는데 그게 도대체 어딨는지 알 수가 있어야지...  
결국 Android studio > 오른쪽 메뉴 중 AVD Manager에 들어간 후에야 찾고 해결 할 수 있었다.

# logic
> 20210114  
뭔가 useState, useEffect의 개념? 및 활용이 잘 이해가 안되는 것 같다.
weatherArr에 새로 담아도 한 번 더 눌러야 갱신된 화면이 렌더링 된다.
정리가 필요함

> 20210121  
역시나 늘어지고 말았다. 이제 남은 일은
- 날씨 아이콘
- 보기 눌러야지 날짜 변화
- 이번달의 경우 어제를 lastday 지정  

달력 다 그리면 어제랑 비교하기부터 만들어야겠다.  

> 20210125
- 이번달이라면 어제를 lastday로 지정하는 건 해결
- 현재는 날짜를 바꾸면 바로바로 달력이 변경되는데 이걸 막아줘야 한다.