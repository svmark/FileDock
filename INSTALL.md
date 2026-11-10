# Install FileDock

## Installation

1. Download `FileDock-0.13.4.dmg` from the GitHub Releases page.
2. Double-click the DMG.
3. Drag **FileDock** to the **Applications** folder shown in the window.
4. Eject the `FileDock 0.13.4` disk.
5. Open FileDock from Applications or Spotlight.

The app is signed with a Developer ID certificate and notarized by Apple. The first launch may show the standard “downloaded from the Internet” confirmation. Choose **Open**. If macOS reports an unidentified or damaged app, do not bypass the warning; report it through GitHub Issues with the macOS version and the exact message.

## Folder permissions

macOS may ask for permission the first time FileDock opens Desktop, Documents, Downloads, or a removable volume. Choose **Allow** for folders you want to use.

If permission was denied:

1. Open **System Settings → Privacy & Security → Files & Folders**.
2. Find FileDock and enable the required folders.
3. Quit and reopen FileDock.

Full Disk Access is not needed for ordinary Desktop, Documents, and Downloads use. It may be required for other users’ folders or specially protected macOS data. Grant it only if you understand why the selected location requires it.

## Update

Download the newer DMG, drag FileDock to Applications, and choose **Replace**. Favorites, language, window layout, and other settings remain in the user account.

FileDock does not currently include automatic updates. Follow the GitHub repository or check Releases for new versions.

## Remove

Move FileDock from Applications to the Trash.

To remove its saved preferences as well, run this command in Terminal:

```sh
defaults delete ai.sndworks.folderheaven
```

## 한국어

1. Releases에서 `FileDock-0.13.4.dmg`를 내려받아 엽니다.
2. **FileDock**을 **Applications(응용 프로그램)** 폴더로 끌어 놓습니다.
3. 응용 프로그램 폴더에서 FileDock을 실행합니다.
4. 인터넷에서 받은 앱이라는 확인 창이 나오면 **열기**를 누릅니다.
5. 데스크탑·문서·다운로드·외장 볼륨 접근을 물으면 사용할 폴더에 대해 **허용**을 누릅니다.

업데이트할 때는 새 DMG의 FileDock을 응용 프로그램 폴더에 넣고 **대치**를 고르면 됩니다. 자동 업데이트는 아직 제공하지 않습니다.
