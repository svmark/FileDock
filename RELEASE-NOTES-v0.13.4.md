# FileDock 0.13.4 공개 베타

FileDock은 Apple Silicon Mac용 네이티브 2분할 파일 탐색기입니다. 첫 일반 공개 배포본입니다.

## 다운로드

### [⬇️ **FileDock-0.13.4.dmg 바로 다운로드**](https://github.com/svmark/FileDock/releases/download/v0.13.4/FileDock-0.13.4.dmg)

**Apple Silicon Mac · macOS 15 이상**

Developer ID로 서명하고 Apple 공증을 받은 배포본입니다.

[SHA256SUMS 다운로드](https://github.com/svmark/FileDock/releases/download/v0.13.4/SHA256SUMS)

SHA-256: `fb490d3600c862b0e32eafa7e839f511cd750cf81343bf980dfc9640036c6dc9`

## 설치 방법

1. 위의 **DMG 바로 다운로드** 링크를 누릅니다.
2. 받은 `FileDock-0.13.4.dmg`를 열고 **FileDock**을 **Applications(응용 프로그램)** 폴더로 끌어 놓습니다.
3. 응용 프로그램 폴더에서 FileDock을 실행합니다.
4. 인터넷에서 받은 앱이라는 macOS 확인 창이 나오면 **열기**를 누릅니다.
5. 데스크탑·문서·다운로드·외장 디스크 접근을 물으면 사용할 폴더에 대해 **허용**을 누릅니다.

## 주요 기능

- 한 창에서 두 로컬 폴더를 나란히 열기
- 복사·이동·드래그 앤 드롭·이름 변경·복제·휴지통·실행 취소·훑어보기
- 한 패널 보기와 레이아웃·위치 복원
- 즐겨찾기·외장 볼륨·로컬 Google Drive 데스크톱 폴더
- 한국어·영어 인터페이스
- 항목이 많은 폴더의 빠른 불러오기
- 새 폴더를 만든 직후 이름 편집
- 외장 디스크·디스크 이미지의 Finder 방식 꺼내기 버튼
- 폴더 새로고침 중 한 번 클릭한 선택이 간헐적으로 풀리던 문제 수정

## 지원 환경과 검증

- Apple Silicon Mac
- macOS 15 이상
- macOS 26·27에서 테스트
- SNDWorks Co., Ltd. Developer ID 서명
- 앱과 DMG Apple 공증 완료
- 앱·DMG·인터넷에서 내려받은 상태의 앱 Gatekeeper 검사 통과

## 참고

- 소스 코드는 포함하지 않습니다.
- 자동 업데이트는 아직 제공하지 않습니다.
- 공개 배포본에는 FileDock Personal의 기기 간 전송(SSH) 기능이 포함되지 않습니다.
- 중요한 파일을 다룰 때는 먼저 백업하십시오.

---

# English

FileDock is a native two-pane file manager for Apple Silicon Macs. This is the first public binary release.

## Download

### [⬇️ **Download FileDock-0.13.4.dmg**](https://github.com/svmark/FileDock/releases/download/v0.13.4/FileDock-0.13.4.dmg)

**Apple Silicon Mac · macOS 15 or later**

The app is Developer ID signed and notarized by Apple.

[Download SHA256SUMS](https://github.com/svmark/FileDock/releases/download/v0.13.4/SHA256SUMS)

SHA-256: `fb490d3600c862b0e32eafa7e839f511cd750cf81343bf980dfc9640036c6dc9`

## Install

1. Use the **DMG download** link above.
2. Open `FileDock-0.13.4.dmg` and drag **FileDock** to **Applications**.
3. Open FileDock from Applications.
4. Choose **Open** if macOS displays the standard downloaded-app confirmation.
5. Allow access when macOS asks for permission to open Desktop, Documents, Downloads, or removable volumes you want to use.

## Highlights

- Two local folders side by side in one window
- Copy, move, drag and drop, rename, duplicate, trash, undo, and Quick Look
- Single-pane mode with layout and location restoration
- Favorites, removable volumes, and local Google Drive desktop folders
- Korean and English interface
- Faster loading of folders with many items
- Immediate name editing after creating a folder
- Finder-style eject button for removable disks and disk images
- Fixed intermittent single-click selection loss while a folder was refreshing

## Requirements and verification

- Apple Silicon Mac
- macOS 15 or later
- Tested on macOS 26 and 27
- Developer ID signed by SNDWorks Co., Ltd.
- Apple notarization accepted for both the app and DMG
- Gatekeeper validation passed for the app, DMG, and quarantined installed app

## Notes

- Source code is not included.
- Automatic updates are not available yet.
- The public build does not include FileDock Personal's device-to-device SSH feature.
- Back up important files before using any file manager on valuable data.
