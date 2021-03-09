# 배포 후 수정사항들

## 1.1 버전
2021.03.08 수정
> 1. 앱 이름이 pastWeather로 다운 받아졌다.   

AndroidMaifest.xml에서 아래 @string/app_name 부분을 찾아서 변경해줘야 한다.   
물론 string으로 직접 넣어 줄 수 있지만 해당 app_name을 정의하는 android/app/src/main/res/values/strings.xml에서
`<string name="app_name">어제날씨기억나?</string>` 변경하였다.

```XML
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
  package="com.pastweather">

    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />

    <application
      android:name=".MainApplication"
      android:label="@string/app_name"
      android:icon="@mipmap/ic_launcher"

      android:allowBackup="false"
      android:theme="@style/AppTheme"
      android:usesCleartextTraffic="true">
      <activity
        android:name=".MainActivity"
        android:label="@string/app_name"
```

> 2. 기본 날짜 설정

저번에 만들 때 '02'를 기본 값으로 설정해버려 매번 들어올때마다 2월달 달력이 기본 화면으로 설정되어 있었다.   
해당 월을 받을 수 있도록 변경하였다.