# 개인정보 및 네트워크 안내

`연아의 수학 모험` 첫 APK는 계정과 서버 없이 작동하는 로컬 우선 학습 게임입니다.

- 어린이 이름 입력, 음성 녹음, 카메라, 위치, 연락처, 자유 대화 기능이 없습니다.
- 표시 이름 `연아`는 앱에 포함된 고정 문구이며 외부 API로 전송되지 않습니다.
- 정답률, 풀이 시간, 재시도, 힌트 사용량과 최근 기록은 Android 앱 전용 저장소에만
  저장됩니다.
- 생성형 AI API 키가 포함되어 있지 않으며 AI API 호출 코드가 실행되지 않습니다.
- Antura의 Unity Services Analytics 초기화는 패키지 `com.yeona.mathadventure`에서
  시작 전에 차단됩니다.
- 외부 저장소 읽기·쓰기 권한은 포함되어 있지 않습니다.

개발용 Unity APK 특성상 `INTERNET`, `ACCESS_NETWORK_STATE`, `POST_NOTIFICATIONS` 권한이
선언되어 있습니다. 현재 Math Journey 기능은 이 권한을 사용해 사용자 데이터나 학습
기록을 외부로 전송하지 않습니다.

