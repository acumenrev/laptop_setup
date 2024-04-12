This is a script to set up an macOS laptop for mobile development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

## Install

Download, review, then execute the script:

```bash
curl -H "Cache-Control: no-cache" --remote-name https://raw.githubusercontent.com/acumenrev/laptop_setup/master/laptop_setup
less mac
bash mac 2>&1 | tee ~/macos_setup.log
```


Choose the additional packages when the prompts appear:

```
Do you want to install default dependencies? [y|N]
Do you want to install iOS dependencies? [y|N]
Do you want to install backend dependencies? [y|N]
Do you want to install Android dependencies? [y|N]
Do you want to install Microsoft dependencies? [y|N]
```

## What it sets up

### Default
- [Firefox] Firefox Browser
- [Brave Browser] Brave Browser: The browser that puts you first
- [Google Chrome] Google Chrome
- [Postman] a collaboration platform for API development
- [iTerm2] a replacement for Terminal
- [Homebrew] for managing operating system libraries
- [Zsh] as your shell
- [oh-my-zsh] to spice up your shell
- [VS Code] code editor
- [Proton VPN] Proton VPN
- [Rectangle] Move and resize windows in macOS using keyboard shortcuts or snap areas
- [Sublime Text] Text Editing, Done Right
- [DBeaver Community Edition]  Universal Database Tool 
- [LuLu] LuLu is the free, open-source firewall that aims to block unknown outgoing connections, protecting your privacy and your Mac! 
- [OpenKey] Vietnamese Input System
- [Cloudfare Warp] The free app that makes your Internet safer
- [Notion] App to write, plan, collaborate, and get organized
- [Monitor Control] Tool to control external monitor brightness & volume
- [OnlyOffice] Document editor
- [Atlassian SourceTree] a free Git client for Mac
- [Finicky]: Finicky is a macOS application that allows you to set up rules that decide which browser is opened for every link or url.
- [Heynote]: A dedicated scratchpad for developers
- [Dozer]: Hide menu bar icons to give your Mac a cleaner look.


[Firefox]: https://www.mozilla.org/en-US/firefox/new/
[Brave Browser]: https://brave.com/
[google chrome]: https://www.google.com/chrome/
[postman]: https://www.postman.com/
[iTerm2]: https://iterm2.com/
[homebrew]: http://brew.sh/
[rvm]: https://rvm.io/
[zsh]: http://www.zsh.org/
[oh-my-zsh]: http://ohmyz.sh/
[vs code]: https://code.visualstudio.com/
[Proton VPN]: https://protonvpn.com/
[Rectangle]: https://rectangleapp.com/
[Sublime Text]: https://www.sublimetext.com/
[DBeaver Community Edition]: https://dbeaver.io/
[LuLu]: https://objective-see.org/products/lulu.html
[OpenKey]: https://open-key.org/
[Cloudfare Warp]: https://cloudflarewarp.com/
[Notion]: https://www.notion.so/
[Monitor Control]: https://github.com/MonitorControl/MonitorControl
[OnlyOffice]: https://www.onlyoffice.com/
[atlassian sourcetree]: https://www.sourcetreeapp.com/
[Finicky]: https://github.com/johnste/finicky
[Heynote]: https://github.com/heyman/heynote/
[Dozer]: https://github.com/Mortennn/Dozer

### Backend

- [NVM] for managing versions of Node.JS
- [ngrok] Reverse proxy, secure introspectable tunnels to localhost

[NVM]: https://github.com/creationix/nvm
[ngrok]: https://ngrok.com

### iOS

- [Cocoapods] a dependency manager for Cocoa projects

- [Xcodes] Xcode Version Management

[cocoapods]: https://cocoapods.org/
[Xcodes]: https://github.com/XcodesOrg/XcodesApp

### Android

- [Temurin] OpenJDK from the Adoptium
- [Android Studio] Android IDE
- [Android SDK] Software Development Kit for Android

[temurin]: https://adoptium.net
[android studio]: https://developer.android.com/studio/index.html
[android sdk]: https://developer.android.com/studio/releases/sdk-tools


### Microsoft

- [Microsoft Teams] Meet, chat, call, and collaborate in just one place
- [Microsoft Outlook] Email Client From Microsoft

[Microsoft Teams]: https://www.microsoft.com/en-us/microsoft-teams/group-chat-software
[Microsoft Outlook]: https://outlook.live.com/owa/

