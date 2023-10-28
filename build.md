Music: 6.23.55  
YouTube: 18.33.40  
Tiktok: 31.9.3  


Install [mMicroG](https://github.com/inotia00/mMicroG/releases) (recommended), [Vanced Extended MicroG](https://github.com/inotia00/VancedMicroG/releases) or [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.4-all.jar  
Integrations: inotia00/revanced-integrations-0.120.4.apk  
Patches: inotia00/revanced-patches-2.195.4.jar  

YouTube
==
- feat(YouTube): add support version `v18.41.39`
- feat(YouTube): drop support version `v18.24.37`
- feat(YouTube): change patch name
`Custom branding icon Revancify blue` → `Custom branding icon Revancify Blue`
`Custom branding icon Revancify red` → `Custom branding icon Revancify Red`
`Custom branding YouTube name` → `Custom branding name YouTube`
`Disable hdr video` → `Disable HDR video`
`Force premium heading` → `Premium heading`
`Hide quick actions` → `Quick actions components`
- feat(YouTube): remove `Custom speed overlay` patch (not suitable for maintenance)
- feat(YouTube): remove `Header switch` patch (deprecated)
- feat(YouTube/Enable debug logging): add `Enable debug buffer logging` settings
- feat(YouTube/Hide account menu): `Hide account menu` now also hides elements in the `You` tab
- feat(YouTube/Hide layout components): remove `Hide official header` settings
- feat(YouTube/Hide shorts components): now hiding all shorts toolbar components will hide the entire shorts toolbar (close https://github.com/inotia00/ReVanced_Extended/issues/1600)
- feat(YouTube/Overlay buttons): add support outline icons (selectable through `options.json`) https://github.com/inotia00/revanced-patches/pull/27
- feat(YouTube/Premium heading): allow using default heading (selectable through `options.json`)
- feat(YouTube/Quick actions components): add `Quick actions top margin` settings
- feat(YouTube/SponsorBlock): add support outline icons (selectable through `options.json`) https://github.com/inotia00/revanced-patches/pull/27
- feat(YouTube/Theme): add set of dark themes to chose from
- fix(YouTube/Hide comment component): integrate `CommentsPreviewDotsFilter`
- fix(YouTube/Hide description components): `Hide music sections` are not hidden in the new layout
- fix(YouTube/Hide load more button): `Hide load more button` hides the expand button in the channel information
- fix(YouTube/Hide player flyout panel): add inform for additional settings menu
- fix(YouTube/Hide player flyout panel): additional settings are hidden even though `Hide stable volume` is not hidden
- fix(YouTube/Hide seek message): force closes in `YouTube v18.36.39`
- fix(YouTube/Hide shorts components): shorts header in search results is not hidden in some accounts
- fix(YouTube/Hide shorts components): `Hide shorts shelf` hides the header of channel information
- fix(YouTube/Hide suggested actions): `Hide suggested actions` hides unintended overlays
- fix(YouTube/Hide suggested video overlay): suggested video overlay not hidden under certain circumstances
- fix(YouTube/Hide suggestions shelf): when the `You` tab is not applied on tablets, empty space lefts https://github.com/inotia00/ReVanced_Extended/issues/1598
- fix(YouTube/Litho filter): app crash if invalid character is used in custom filter
- fix(YouTube/Litho filter): app crashes on some accounts
- fix(YouTube/Litho filter): move to the correct path
- fix(YouTube/Overlay buttons): increase the size of the overlay button by 6% and add some bottom margin
- fix(YouTube/Return YouTube Dislike): RYD prefetching home feed Shorts
- fix(YouTube/Return YouTube Dislike): toast message not shown when RYD API is not available
- fix(YouTube/Return YouTube Dislike): unintended toast message appears when adding a playlist to the library
- fix(YouTube/Return YouTube Dislike): use API back off if client connection fails for any reason
- fix(YouTube/Settings): add dots in strings where they needed https://github.com/inotia00/revanced-patches/pull/26
- fix(YouTube/Settings): add inform for import settings
- fix(YouTube/Settings): import/export settings are in wrong order
- fix(YouTube/Settings): now the reboot dialog does not appear after importing the settings
- fix(YouTube/Spoof player parameters): set the client version correctly
- feat(YouTube/Translations): update translation
`Arabic`, `Bengali`, `Brazilian`, `Bulgarian`, `Chinese Simplified`, `Chinese Traditional`, `Finnish`, `French`, `Greek`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Romanian`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music): add support version `v6.23.55`, `v6.25.53`
- feat(YouTube Music): change patch name
`Custom branding icon Revancify blue` → `Custom branding icon Revancify Blue`
`Custom branding icon Revancify red` → `Custom branding icon Revancify Red`
`Custom branding Music name` → `Custom branding name YouTube Music`
- fix(YouTube Music/Litho filter): app crash if invalid character is used in custom filter
- fix(YouTube Music/Litho filter): move to the correct path
- feat(YouTube Music/Translations): update translation
`Brazilian`, `Korean`, `Polish`, `Russian`, `Turkish`, `Ukrainian`, `Vietnamese`


Reddit
==
- feat(Reddit): add `Hide recently visited shelf` patch https://github.com/inotia00/ReVanced_Extended/issues/1473


Etc
==
- build: bump dependencies
- build: bump patcher to `19.0.0`
- **RVX Manager users need to update RVX Manager**
- **Revancify users need to delete Patch Options** : `7 Delete Components` > `3 Patch Options`
- **rvx-builder users (Android, Termux) just reinstall rvx-builder** : typing `rvxre` in termux
- **rvx-builder users (Windows, Linux, Mac) should manually delete **`options.json`** file**
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.14.2 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.14.2)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  
