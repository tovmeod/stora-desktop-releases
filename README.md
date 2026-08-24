# stora-desktop-releases
Stora Desktop release assets and update manifest (D-01/D-02) — no source code

<!-- GENERATED:INSTALL:START -->
1. Download the latest AppImage from the
   [releases page](https://github.com/tovmeod/stora-desktop-releases/releases/latest).
2. Make it executable:
   ```bash
   chmod +x Stora*.AppImage
   ```
3. Launch it:
   ```bash
   ./Stora*.AppImage
   ```

Requires glibc >= 2.35 (Ubuntu 22.04+, Debian 12+, Fedora 36+, Linux Mint 21+; does not support Ubuntu 20.04 or Debian 11).
<!-- GENERATED:INSTALL:END -->

<!-- GENERATED:INSTALL-WINDOWS:START -->
1. Download the latest installer (`.exe`) from the
   [releases page](https://github.com/tovmeod/stora-desktop-releases/releases/latest).
2. Run the installer.
3. Windows will show a **"Windows protected your PC"** SmartScreen warning --
   this is expected: the installer is not signed with a paid Windows
   code-signing certificate. Click **More info**, then **Run anyway** to
   continue. This warning is unrelated to the app's own auto-update
   signing key -- SmartScreen checks the installer's Authenticode
   signature, a separate mechanism from the updater's signature, so the
   updater key does not (and cannot) address this warning.
4. [WebView2](https://developer.microsoft.com/microsoft-edge/webview2/) is
   required and is already installed on Windows 10 1803+ and Windows 11;
   on older builds the installer downloads it automatically.

Requires Windows 10 (Windows 10 version 1803 (April 2018 Update) or newer, and Windows 11).
<!-- GENERATED:INSTALL-WINDOWS:END -->
