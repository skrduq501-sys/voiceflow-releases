# VoiceFlow 설치 파일

VoiceFlow 알파 테스트용 설치 파일을 올리는 곳입니다. 코드는 여기 없고, 새 버전이 나오면 [Releases](https://github.com/skrduq501-sys/voiceflow-releases/releases)에 설치 파일이 올라갑니다. 이미 설치한 앱은 새 버전이 올라오면 사이드바와 알림으로 알려 줍니다.

## macOS (Apple Silicon)

1. [최신 릴리스](https://github.com/skrduq501-sys/voiceflow-releases/releases/latest)에서 `VoiceFlow-<버전>-arm64.dmg`를 받습니다.
2. dmg를 열고 VoiceFlow를 응용 프로그램 폴더로 끌어 넣습니다.
3. 처음 열 때 "확인되지 않은 개발자" 경고가 뜨면, 시스템 설정 › 개인정보 보호 및 보안 맨 아래에서 **그래도 열기**를 누릅니다. 알파 버전이라 Apple 공증을 받지 않았기 때문이며, 한 번만 하면 됩니다.
4. 앱의 설정 › 권한에서 마이크와 손쉬운 사용을 허용합니다.

업데이트할 때는 새 dmg로 앱을 덮어쓰면 됩니다. 권한과 저장한 API 키는 그대로 남습니다.

## Windows

Windows 설치 파일(`VoiceFlow-Setup-<버전>.exe`)은 같은 릴리스에 따로 추가됩니다. 릴리스에 exe가 없으면 아직 준비 중입니다.

## Claude API 키 (선택)

받아쓰기와 회의 녹음은 키 없이도 이 컴퓨터 안에서 동작합니다. 회의 요약, 명령 모드, 실시간 번역 자막, "방금 뭐라고 했지?"는 Claude API 키가 필요합니다. 설정 › Claude API 키에 넣으면 이 컴퓨터에만 암호화되어 저장됩니다.
