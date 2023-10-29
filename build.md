YouTube: 18.41.39  


Install [mMicroG](https://github.com/inotia00/mMicroG/releases) (recommended), [Vanced Extended MicroG](https://github.com/inotia00/VancedMicroG/releases) or [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.4-all.jar  
Integrations: inotia00/revanced-integrations-0.120.6.apk  
Patches: inotia00/revanced-patches-2.195.6.jar  

YouTube
==
- fix(YouTube): compile error occurs when both the `Theme` patch and the `MaterialYou` patch are excluded
- fix(YouTube/Hide seekbar): xml parsing error occurs due to limitations in the patch structure
- feat(YouTube/Translations): update translation
`Italian`, `Korean`, `Turkish`, `Vietnamese`


YouTube Music
==
- fix(YouTube Music/Custom package name): YouTube Music's clone package name in the patch options matches the YouTube's clone package name


Etc
==
- This release is a hotfix, so read [revanced-patches-v2.195.4](https://github.com/inotia00/revanced-patches/releases/tag/v2.195.4) release note for the full changelog
- **RVX Manager users need to update RVX Manager**
- **Revancify users need to delete Patch Options** - `7 Delete Components` > `3 Patch Options`
- **rvx-builder users (Android, Termux) just reinstall rvx-builder** - typing `rvxre` in termux
- **rvx-builder users (Windows, Linux, Mac) should manually delete **`options.json`** file**
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.14.2 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.14.2)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  
