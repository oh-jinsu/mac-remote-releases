# SimpleRemote

같은 iPhone 앱에서 Mac과 Windows PC를 제어하는 SimpleRemote의 서명된 배포 파일 저장소입니다. 앱 소스·서명 개인키·페어링 정보는 공개하지 않습니다.

[Mac 0.8.0 다운로드](https://github.com/oh-jinsu/mac-remote-releases/releases/tag/mac-v0.8.0)

- macOS 14 이상, Intel·Apple Silicon 공용 앱입니다. Developer ID 서명·Apple 공증을 통과했고 앱에 공증 티켓을 첨부했습니다. 화면 기록·손쉬운 사용 권한은 macOS에서 별도로 허용해야 합니다.
- Mac은 서명된 업데이트 안내와 패키지를 검증하고 자동으로 업데이트합니다.
- 새 공개 버전은 인터넷 중계를 자동으로 사용합니다. SSH·VPN·LAN 직접 연결 설정은 필요 없습니다. QR에는 비밀키가 있으므로 공유하지 마세요.
- 앱의 TLS 1.3 연결은 iPhone과 컴퓨터 사이에서 종료됩니다. 중계 서버는 화면·입력 평문을 해독하지 못하지만 IP·기기 식별자·연결 시간·전송량은 알 수 있습니다.
- 공개 베타는 일반 기기당 하루 1 GiB, 서버 전체 하루 5 GiB의 전송 한도가 있으며 UTC 00:00에 초기화됩니다. 온라인 호스트 32개·동시 스트림 8개로 제한합니다.

**iPhone 컴패니언의 일반 App Store 배포는 아직 준비 중입니다. Windows는 가원소프트 회사 계정의 Microsoft Store 배포를 준비 중이며, 현재 Store 설치 링크는 없습니다.**

기존 개인용 Windows 1.2.2 자동 업데이트 자산은 호환성을 위해 유지합니다. 새 공개 Windows 배포는 Store MSIX를 사용합니다. 기존 버전은 실행 중 자동 절전과 화면보호기 자동 실행을 일시 방지하며 종료 시 복원합니다. 회사 정책과 수동 잠금·절전은 유지합니다. 실제 Windows의 설치·화면·입력·전원 동작 검증은 별도 필요합니다.
