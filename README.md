# 연아의 별다리 모험

`Yeona Math Adventure`의 Android 테스트 APK 공식 다운로드 저장소입니다.

## 다운로드

[YeonaMathAdventure-v0.2.0.apk 바로 다운로드](https://github.com/jamaica8612/yeona-math-adventure/releases/download/v0.2.0/YeonaMathAdventure-v0.2.0.apk)

[최신 버전 안내 페이지](https://github.com/jamaica8612/yeona-math-adventure/releases/latest)

현재 버전: `v0.2.0`

- 파일: `YeonaMathAdventure-v0.2.0.apk`
- 크기: 136,169,655 bytes (129.86 MiB)
- SHA-256: `7096D4A28E389320095E2C10191B523E825FD2B8CDF88335F2DECEEA016B0043`
- Android 7.1(API 25) 이상
- ARM64 기기 전용
- 가로 화면, 폰·태블릿 대응

브라우저로 APK를 받은 뒤 Android 안내에 따라 해당 브라우저 또는 파일 앱의
`알 수 없는 앱 설치` 권한을 한 번 허용해야 할 수 있습니다. 같은 패키지와 서명으로
v0.1.1 위에 업데이트 설치할 수 있어 기존 개념별 학습 기록과 별 보상이 유지됩니다.

오래된 ARMv7 기기에는 [v0.1.1 다운로드](https://github.com/jamaica8612/yeona-math-adventure/releases/tag/v0.1.1)를 이용할 수 있습니다.

## v0.2.0의 게임 세계

- 클레이 스타일 숲속 잔치, 별다리, 공간 공방
- 새 별 친구 `반디`의 안내와 축하 반응
- 공평하게 나누기 → 목표 숫자 만들기 → 규칙과 공간 퍼즐로 이어지는 6판 실력 탐험
- 확인 버튼 없이 배치와 식 완성 뒤 자동 판정
- 성공 배경 변화, 별가루, 첫 섬 보상 선택
- 개념별 적응형 난이도와 로컬 학습 기록
- 부모용 `익숙함 / 연습 중 / 도움이 필요함` 상태

Unity EditMode 테스트 89/89, Android Gradle `assembleRelease`, APK v2 서명, zipalign,
`android:debuggable=false`를 확인했습니다. 빌드 PC에는 Android 기기가 연결되어 있지 않아
실제 폰/태블릿 화면은 설치 후 한 번 확인해야 합니다.

게임은 AI API나 계정 없이 완전히 동작합니다. 이름 입력, 음성 녹음, 자유 입력 기능이
없으며 학습 기록은 앱 전용 로컬 저장소에만 보관됩니다. Unity/Antura 패키지가 선언한
`INTERNET`, `ACCESS_NETWORK_STATE`, `POST_NOTIFICATIONS` 권한은 남아 있지만 Math Journey는
네트워크 요청을 만들지 않고 패키지 전용 가드가 Unity Analytics 초기화를 차단합니다.
자세한 내용은 [PRIVACY.md](PRIVACY.md)를 참고하세요.

## 오픈소스와 생성 자산

이 앱은 [Antura](https://github.com/vgwb/Antura) commit
`a60a8ba9e87d054aea5d757188cc2050e9289fb1` 기반의 별도 Math Journey입니다. Antura 코드는
BSD-2-Clause, 자산은 별도 표시가 없으면 CC-BY-4.0입니다. Pretendard는 SIL Open Font
License 1.1입니다. GCompris와 Matheor는 개념과 일반적인 게임 방식만 참고했으며 코드나
자산을 복사하지 않았습니다.

v0.2.0의 클레이 배경과 `반디`는 이 프로젝트를 위해 OpenAI 이미지 생성으로 제작한
프로젝트 원본 자산입니다. APK는 이미지 생성 서비스에 연결되지 않습니다. 전체 출처와
배포 고지는 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)에 있습니다.

이 APK는 Google Play 배포용 서명이 아닌 Android 디버그 키로 서명된 테스트 버전입니다.
