# 연아의 수학 모험

`Yeona Math Adventure`의 Android 테스트 APK 배포 저장소입니다.

## 다운로드

[YeonaMathAdventure-v0.1.1.apk 바로 다운로드](https://github.com/jamaica8612/yeona-math-adventure/releases/download/v0.1.1/YeonaMathAdventure-v0.1.1.apk)

[최신 버전 안내 페이지](https://github.com/jamaica8612/yeona-math-adventure/releases/latest)

현재 버전: `v0.1.1`

- 파일: `YeonaMathAdventure-v0.1.1.apk`
- 크기: 147,359,681 bytes (140.53 MiB)
- SHA-256: `5CDA764DEAD7B0CAF44A6B7EDB100C5821B9281492CD9DFDAE9D6ACF52FDE9C4`
- Android 7.1(API 25) 이상
- ARMv7 및 ARM64 지원
- 가로 화면, 폰·태블릿 대응

`v0.1.1`은 실제 기기에서 한국어 글자가 보이지 않던 `v0.1.0`의 TMP 폰트 생성 문제를
수정했습니다. Pretendard 한글 글리프와 머티리얼을 빌드 전에 APK에 넣으며, 개발용 오류
콘솔도 비활성화했습니다. 같은 패키지와 서명으로 `v0.1.0` 위에 업데이트 설치할 수 있어
기존 로컬 학습 기록이 유지됩니다.

이 APK는 Google Play 배포용 서명이 아닌 Android 디버그 키로 서명된 테스트 버전입니다.
브라우저로 APK를 받은 뒤 Android의 안내에 따라 해당 브라우저 또는 파일 앱의
`알 수 없는 앱 설치` 권한을 한 번 허용해야 할 수 있습니다.

## 들어 있는 활동

- 게임형 초기 실력 확인
- 목표 숫자 만들기
- 공평하게 나누기
- 규칙과 공간 퍼즐
- 개념별 적응형 난이도와 로컬 학습 기록
- 부모용 `익숙함 / 연습 중 / 도움이 필요함` 상태

게임은 AI API나 계정 없이 완전히 동작합니다. 이름 입력, 음성 녹음, 자유 입력 기능이
없으며 학습 기록은 앱 전용 로컬 저장소에만 보관됩니다. 첫 개발용 APK에는 Unity/Antura
패키지에서 선언한 `INTERNET`, `ACCESS_NETWORK_STATE`, `POST_NOTIFICATIONS` 권한이 있지만,
Math Journey는 네트워크 요청을 만들지 않고 패키지 전용 가드가 Unity Analytics 초기화를
차단합니다. 자세한 내용은 [PRIVACY.md](PRIVACY.md)를 참고하세요.

## 오픈소스 고지

이 앱은 [Antura](https://github.com/vgwb/Antura) commit
`a60a8ba9e87d054aea5d757188cc2050e9289fb1`을 기반으로 별도의 Math Journey를 추가했습니다.
Antura 코드는 BSD-2-Clause, 자산은 별도 표시가 없으면 CC-BY-4.0입니다. Pretendard는
SIL Open Font License 1.1입니다. GCompris와 Matheor는 개념과 일반적인 게임 방식만
참고했으며 해당 프로젝트의 코드나 자산을 복사하지 않았습니다.

전체 출처와 배포 고지는 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)에 있습니다.

