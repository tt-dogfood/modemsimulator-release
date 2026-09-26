# CLIP 모뎀 에뮬레이터 (Android)

LG 가전 Wi-Fi 모뎀 펌웨어(CLIP)를 Android 기기에서 모뎀처럼 실행하는 개발용 앱입니다.
이 레포의 파일은 릴리즈 스크립트가 만듭니다. 직접 고치지 마세요.

## 설치

최신 버전은 **v1.0.0** (2026-09-26) 입니다.

- 폰에서 받기: [clip-modem-emulator-1.0.0.apk](https://raw.githubusercontent.com/tt-dogfood/modemsimulator-release/main/apk/clip-modem-emulator-1.0.0.apk)
- PC 에서 설치: `adb install -r clip-modem-emulator-1.0.0.apk`
- Android API 26 이상, arm64-v8a / x86_64 기기

폰 브라우저로 받아 설치하려면 그 브라우저에 ‘알 수 없는 앱 설치’ 권한을 허용해야 합니다.

## 업데이트

앱 메뉴(⋮) > **업데이트 확인** 을 누르면 새 버전을 받아 설치합니다. 앱을 열 때도 하루에 한 번 확인합니다.

- 처음 업데이트할 때 이 앱에 ‘알 수 없는 앱 설치’ 권한을 허용해야 합니다.
- 설치하기 전에 실행 중인 모뎀을 중지합니다. 모뎀 flash 와 설정은 그대로 남습니다.
- 직접 빌드한 개발 빌드(debug 서명)가 설치되어 있으면 서명 키가 달라 업데이트되지 않습니다. 앱을 삭제하고 새로 설치하세요.

## 버전

| 버전 | 날짜 | 변경 내용 |
| --- | --- | --- |
| [v1.0.0](https://raw.githubusercontent.com/tt-dogfood/modemsimulator-release/main/apk/clip-modem-emulator-1.0.0.apk) | 2026-09-26 | 첫 배포. 앱 메뉴 > 업데이트 확인으로 새 버전을 받아 설치할 수 있습니다. |

## 파일

- `latest.json`: 최신 버전 정보. 앱이 업데이트를 확인할 때 읽습니다.
- `releases.json`: 전체 버전 기록 (크기, SHA-256, 서명 인증서 SHA-256)
- `apk/`: 버전별 APK
