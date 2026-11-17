# Mac Remote Windows releases

아이폰의 같은 Mac Remote 앱에서 Mac과 Windows PC를 제어하기 위한 Windows 호스트 배포입니다.

[최신 Windows 버전 다운로드](https://github.com/oh-jinsu/mac-remote-releases/releases/latest/download/MacRemote-Windows-x64.zip)

ZIP 전체를 압축 해제하고 MacRemoteWindows.exe를 한 번 실행하세요. 사용자 폴더에 설치하며, 이후 서명된 새 버전은 앱이 자동으로 다운로드하고 원격 연결이 없을 때 적용합니다. 기존 페어링은 유지합니다.

- Windows 11 x64. 처음 실행할 때 영상 인코더를 원본 배포처에서 자동으로 받아 SHA-256을 확인합니다.
- 앱이 트레이에서 실행 중이어도 자동 절전을 방지하고 화면보호기는 유지합니다. 회사 정책의 잠금과 수동 잠금·절전은 유지됩니다.
- 이 저장소에는 공개 실행 패키지와 업데이트 서명만 있습니다. 개인 소스·서명 개인키·접속 정보는 포함하지 않습니다.
- Windows 실기기에서의 화면·입력·전원·자동 교체 검증은 아직 진행되지 않았습니다. 릴리스 노트와 패키지의 설명서를 참고하세요.

The updater pins the publisher's ECDSA P-256 public key and verifies the signed release metadata, package SHA-256 and version before replacement. Release uploads are completed in draft before publication. The full encoder binary is obtained directly from [Gyan's FFmpeg distribution](https://www.gyan.dev/ffmpeg/builds/) on first use, and is not redistributed in these update archives. Third-party notices are included in each package.
