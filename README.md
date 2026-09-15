# HiPass for Windows

HiPass의 Windows 설치파일과 앱 업데이트를 제공하는 공개 배포 저장소입니다.

- [공식 다운로드](https://hipass.despitethat.com/download/)
- [사용 안내](https://hipass.despitethat.com/guide/)
- [릴리스 목록](https://github.com/tkim-au/HiPass-Releases/releases)

현재 정식 버전은 **0.1.6 · Windows 11 x64**입니다. [공식 다운로드](https://hipass.despitethat.com/download/) 또는 [0.1.6 릴리스](https://github.com/tkim-au/HiPass-Releases/releases/tag/v0.1.6)에서 `HiPass-0.1.6-Setup.exe`를 내려받으세요. Python과 앱 실행에 필요한 브라우저가 설치파일에 포함됩니다.

**종단간 암호화**를 추가했습니다. 양쪽 PC를 0.1.6으로 업데이트하고 **설정 → 암호화 설정**에 같은 전송키를 저장한 뒤 옵션을 켜세요. 기본값은 꺼짐입니다. 파일명과 내용을 PC에서 암호화해 Overleaf에 전달하며 자동·수동 전송과 이어받기를 지원합니다. 키는 Overleaf와 별도의 신뢰할 수 있는 경로로 전달하세요. [암호화 설정 순서](https://hipass.despitethat.com/guide/#종단간-암호화)

자동 보내기·받기를 기본으로 표시하며 수동 전송은 설정의 **수동 모드 사용**으로 켤 수 있습니다. 앱 정보에서 업데이트를 확인할 수 있습니다. 0.1.5부터 앱을 사용하는 동안 설치를 준비하는 업데이트 방식을 제공합니다.

**Windows 코드 서명이 없는 설치파일입니다.** 실행 시 알 수 없는 게시자 또는 Microsoft Defender SmartScreen 안내가 표시될 수 있으며, PC 보안 정책에 따라 실행이 차단될 수 있습니다. 업데이트 목록의 Ed25519 서명과 패키지 해시 검증은 유지합니다.

내부 시험 설치본 0.1.0은 업데이트 주소가 없으므로 새 설치파일로 한 번 수동 설치해야 합니다. `Source code` 압축파일과 `.nupkg`는 Windows 설치파일이 아닙니다. `.nupkg`와 `update-index.json`은 앱 내부 업데이트에 사용합니다.

릴리스의 `SHA256SUMS.txt`에서 다운로드한 파일의 SHA-256을 확인할 수 있습니다. 실제 두 PC 전송과 외부 보안 감사는 별도 검증 항목입니다.
