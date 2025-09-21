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
- [Microsoft Edge] Microsoft Edge is the AI-powered browser. A smarter way to protect create find browse game shop learn
- [Google Chrome] Google Chrome
- [Postman] a collaboration platform for API development
- [iTerm2] a replacement for Terminal
- [Homebrew] for managing operating system libraries
- [Zsh] as your shell
- [oh-my-zsh] to spice up your shell
- [VS Code] code editor
- [Rectangle] Move and resize windows in macOS using keyboard shortcuts or snap areas
- [Sublime Text] Text Editing, Done Right
- [DBeaver Community Edition]  Universal Database Tool 
- [LuLu] LuLu is the free, open-source firewall that aims to block unknown outgoing connections, protecting your privacy and your Mac! 
- [OpenKey] Vietnamese Input System
- [Cloudfare Warp] The free app that makes your Internet safer
- [Notion] App to write, plan, collaborate, and get organized
- [Monitor Control] Tool to control external monitor brightness & volume
- [OnlyOffice] Document editor
- [Finicky]: Finicky is a macOS application that allows you to set up rules that decide which browser is opened for every link or url.
- [Heynote]: A dedicated scratchpad for developers
- [Dozer]: Hide menu bar icons to give your Mac a cleaner look.
- [Superfile]: Navigating folders inside terminal
- [Maccy]: Clipboard Management
- [Fork]: Git Client
- [Marta]: File Manager for macOS.
- [Warp]: Warp is the terminal with AI and your dev team's knowledge built-in.
- [Adguard]: Stand alone ad blocker
- [Adguard-VPN]: VPN for privacy and security
- [Telegram]: Messaging app with a focus on speed and security
- [Ice Menu Bar]: Ice is a powerful menu bar management tool. While its primary function is hiding and showing menu bar items, it aims to cover a wide variety of additional features to make it one of the most versatile menu bar tools available.
- [OnyX]: Verify system files structure, run miscellaneous maintenance and more
- [Bitwarden]: Desktop password and login vault
- [CotEditor]: The Plain-Text Editor for macOS
- [intellidock]: Hides the Dock when it is overlapped by a window
- [keka]: the macOS file archiver. Store more, share with privacy
- [AppLite]: Make managing third party applications a breeze with Applite
- [AltTab]: Windows alt-tab on macOS




[Firefox]: https://www.mozilla.org/en-US/firefox/new/
[Microsoft Edge]: https://www.microsoft.com/en-us/edge?form
[google chrome]: https://www.google.com/chrome/
[postman]: https://www.postman.com/
[iTerm2]: https://iterm2.com/
[homebrew]: http://brew.sh/
[rvm]: https://rvm.io/
[zsh]: http://www.zsh.org/
[oh-my-zsh]: http://ohmyz.sh/
[vs code]: https://code.visualstudio.com/
[Rectangle]: https://rectangleapp.com/
[Sublime Text]: https://www.sublimetext.com/
[DBeaver Community Edition]: https://dbeaver.io/
[LuLu]: https://objective-see.org/products/lulu.html
[OpenKey]: https://open-key.org/
[Cloudfare Warp]: https://cloudflarewarp.com/
[Notion]: https://www.notion.so/
[Monitor Control]: https://github.com/MonitorControl/MonitorControl
[OnlyOffice]: https://www.onlyoffice.com/
[Finicky]: https://github.com/johnste/finicky
[Heynote]: https://github.com/heyman/heynote/
[Dozer]: https://github.com/Mortennn/Dozer
[Superfile]: https://github.com/MHNightCat/superfile
[Maccy]: https://maccy.app
[Fork]: https://fork.dev/
[Marta]: https://marta.sh/
[Warp]: https://www.warp.dev/
[Adguard]: https://adguard.com/
[Adguard-VPN]: https://adguard-vpn.com/
[Telegram]: https://macos.telegram.org/
[Ice Menu Bar]: https://github.com/jordanbaird/Ice
[OnyX]: https://www.titanium-software.fr/en/onyx.html
[Bitwarden]: https://bitwarden.com/
[CotEditor]: https://coteditor.com/
[intellidock]: https://mightymac.app/intellidock/
[keka]: https://www.keka.io/en/
[AppLite]: https://aerolite.dev/applite
[AltTab]: https://alt-tab-macos.netlify.app/

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

