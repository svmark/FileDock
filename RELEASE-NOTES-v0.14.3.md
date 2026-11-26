# FileDock 0.14.3 공개 베타

FileDock은 Apple Silicon Mac용 네이티브 2분할 파일 탐색기입니다. 이번 판은 화면과 조작을 Finder에 더 가깝게 맞추고, 꺼내기 단추 결함을 고쳤습니다.

## 다운로드

### [⬇️ **FileDock-0.14.3.dmg 바로 다운로드**](https://github.com/svmark/FileDock/releases/download/v0.14.3/FileDock-0.14.3.dmg)

**Apple Silicon Mac · macOS 15 이상**

Developer ID로 서명하고 Apple 공증을 받은 배포본입니다.

[SHA256SUMS 다운로드](https://github.com/svmark/FileDock/releases/download/v0.14.3/SHA256SUMS)

SHA-256: `2b4bd7cd2643edbf075ccaf872a65f3c8ed842ea82b99871dadbe53dc6b90089`

## 설치·업데이트

1. 위의 **DMG 바로 다운로드** 링크를 누릅니다.
2. 받은 `FileDock-0.14.3.dmg`를 열고 **FileDock**을 **Applications(응용 프로그램)** 폴더로 끌어 놓습니다. 이전 판이 있으면 **대치**를 고릅니다. 설정과 즐겨찾기는 그대로 남습니다.
3. 응용 프로그램 폴더에서 FileDock을 실행합니다.
4. 인터넷에서 받은 앱이라는 macOS 확인 창이 나오면 **열기**를 누릅니다.
5. 데스크탑·문서·다운로드·외장 디스크 접근을 물으면 사용할 폴더에 대해 **허용**을 누릅니다.

## 0.13.4 이후 바뀐 것

- **목록 안에서 폴더 펼치기**: 폴더 옆 ›, →로 한 단계, ⌥→ 또는 ⌥ 클릭으로 하위까지 모두, ←로 접기
- **Finder 모양의 패널 머리줄**: 붙은 뒤로·앞으로 단추와 굵은 폴더 이름. 이름을 ⌘클릭하면 상위 경로 메뉴
- **경로 막대**를 패널 아래로 옮기고 디스크부터 고른 항목까지 표시(⌥⌘P로 켜고 끔)
- **상태 막대**에 ‘선택 수와 남은 공간’(⌘/로 켜고 끔)
- **검색**: 늘 떠 있던 필터 칸 대신 툴바 검색(⌘F)이 지금 패널을 이름으로 거릅니다. Esc로 풉니다.
- **Finder와 같은 날짜 표시**: 오늘·어제, 열을 좁히면 더 짧게. 빈 값은 `--`
- **Tab**은 Finder처럼 다음 항목, **⌃Tab**으로 패널 전환
- 경로 막대 조각·폴더 이름 **우클릭 메뉴**: 반대 패널에서 열기, 상위 폴더에서 보기, 정보 가져오기, 경로 이름 복사, 터미널에서 열기, 서비스
- **iPhone 또는 iPad에서 가져오기**: 사진 찍기·문서 스캔 결과를 그 폴더에 저장
- 복제(⌘D) 뒤 만든 사본 선택, 새 폴더 기본 이름 ‘무제 폴더’(영어 untitled folder)

## 고친 문제

- **꺼내기(⏏) 단추**: 기호 바로 위·아래를 누르면 꺼내지지 않고 그 디스크로 이동하던 문제. 0.13.4 공개 베타에도 있었습니다.
- 한 패널을 닫았다 다시 두 패널로 열면 패널 폭이 바뀌던 문제

## 지원 환경과 검증

- Apple Silicon Mac, macOS 15 이상, macOS 26·27에서 테스트
- SNDWorks Co., Ltd. Developer ID 서명, 앱과 DMG Apple 공증 완료
- 앱·DMG·인터넷에서 내려받은 상태의 앱 Gatekeeper 검사 통과

## 참고

- 소스 코드는 포함하지 않습니다.
- 자동 업데이트는 아직 제공하지 않습니다.
- 공개 배포본에는 FileDock Personal의 기기 간 전송(SSH) 기능이 포함되지 않습니다.
- 중요한 파일을 다룰 때는 먼저 백업하십시오.

---

# English

FileDock is a native two-pane file manager for Apple Silicon Macs. This release brings the interface and controls closer to Finder and fixes the eject button.

## Download

### [⬇️ **Download FileDock-0.14.3.dmg**](https://github.com/svmark/FileDock/releases/download/v0.14.3/FileDock-0.14.3.dmg)

**Apple Silicon Mac · macOS 15 or later**

The app is Developer ID signed and notarized by Apple.

[Download SHA256SUMS](https://github.com/svmark/FileDock/releases/download/v0.14.3/SHA256SUMS)

SHA-256: `2b4bd7cd2643edbf075ccaf872a65f3c8ed842ea82b99871dadbe53dc6b90089`

## Install or update

1. Use the **DMG download** link above.
2. Open `FileDock-0.14.3.dmg` and drag **FileDock** to **Applications**. Choose **Replace** if an earlier version is there; your settings and favorites are kept.
3. Open FileDock from Applications.
4. Choose **Open** if macOS displays the standard downloaded-app confirmation.
5. Allow access when macOS asks for permission to open Desktop, Documents, Downloads, or removable volumes you want to use.

## What's new since 0.13.4

- **Expand folders in the list**: click ›, press → for one level, ⌥→ or ⌥-click for all levels, ← to collapse
- **Finder-style pane header**: joined back/forward buttons and the folder name in bold; ⌘-click the name for the enclosing-folder menu
- **Path bar** moved to the bottom of each pane, from the disk to the selected item (⌥⌘P)
- **Status bar** with selection count and available space (⌘/)
- **Search**: the always-visible filter field is replaced by the toolbar search (⌘F), which filters the active pane by name; Esc clears it
- **Finder-style dates**: Today and Yesterday, shorter formats in narrow columns, and `--` for empty values
- **Tab** moves to the next item as in Finder; **⌃Tab** switches panes
- **Right-click menu** on path bar items and the folder name: Open in Other Pane, Show in Enclosing Folder, Get Info, Copy as Pathname, Open in Terminal, Services
- **Import from iPhone or iPad**: photos and document scans are saved to that folder
- Duplicate (⌘D) selects the new copy; new folders are named “untitled folder”

## Fixes

- **Eject (⏏) button**: clicking just above or below the symbol opened the disk instead of ejecting it. This also affected 0.13.4 Public Beta.
- Pane width changed after closing one pane and showing both panes again

## Requirements and verification

- Apple Silicon Mac, macOS 15 or later, tested on macOS 26 and 27
- Developer ID signed by SNDWorks Co., Ltd.; Apple notarization accepted for both the app and DMG
- Gatekeeper validation passed for the app, DMG, and quarantined installed app

## Notes

- Source code is not included.
- Automatic updates are not available yet.
- The public build does not include FileDock Personal's device-to-device SSH feature.
- Back up important files before using any file manager on valuable data.
