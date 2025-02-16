# Changelog

## [1.0.6a](https://github.com/fvwmorg/fvwm3/tree/1.0.6a) (2023-01-16)

## What's Changed
### Other Changes
* dist: doc: include all doc sources by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/806


**Full Changelog**: https://github.com/fvwmorg/fvwm3/compare/1.0.6...1.0.6a
## [1.0.6](https://github.com/fvwmorg/fvwm3/tree/1.0.6) (2023-01-14)

## What's Changed
### Breaking Changes
* remove fvwm-config by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/731
* ta/alloca by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/722
* deprecate color commands by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/738
* Ensure a default colorset is always configured. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/740
* commands: remove DefaultColors & DefaultColorset by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/749
* MenuStyle: Remove Depreciated options and non colorset  by @somiaj in https://github.com/fvwmorg/fvwm3/pull/757
### Enhancements
* decor: allow window borders separate colours by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/730
* Update Move shuffle logic to jump to next monitor by @somiaj in https://github.com/fvwmorg/fvwm3/pull/742
* conditional: screen: simplify logic by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/746
* Allow SidePic in default-config. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/762
* Move shuffle, ensure window inside working area. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/767
* Translucent Menus by @somiaj in https://github.com/fvwmorg/fvwm3/pull/760
* Updates to FvwmPager scaling math to improve visual aspects due to rounding errors. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/790
### Other Changes
* doc: don't install fvwm3_manpage_source by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/712
* Rename .stalonetrayrc to stalonetrayrc by @wfp5p in https://github.com/fvwmorg/fvwm3/pull/713
* Fix background resetting in default-config by @somiaj in https://github.com/fvwmorg/fvwm3/pull/714
* desk_add: fix window counting by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/716
* remove unused variable by @omar-polo in https://github.com/fvwmorg/fvwm3/pull/718
* two clock_t and time_t casts for portability by @omar-polo in https://github.com/fvwmorg/fvwm3/pull/719
* changing sprintf -> snprintf & co by @omar-polo in https://github.com/fvwmorg/fvwm3/pull/720
* DesktopConfiguration: send status_send() by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/724
* FvwmScript.c: fix wrong size of TabCom array by @slazav in https://github.com/fvwmorg/fvwm3/pull/725
* gotodesk: simplify logic for shared/global by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/727
* Add a multicolor border example to default-config by @somiaj in https://github.com/fvwmorg/fvwm3/pull/732
* Some pedantic clean up of whitespace and add missing translation strings. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/733
* Tweak HilightBorderColorset by @lgsobalvarro in https://github.com/fvwmorg/fvwm3/pull/737
* docs: remove obsolete GNOME references by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/739
* MWMBorder: fix calculation by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/743
* Don't set border colorsets by default. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/747
* style: silence warning for unconsumed string by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/745
* Add split manpages to default-config. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/750
* FvwnIconMan use font as fallback for tips font. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/751
* FvwmIconMan: Don't chop window display string by @somiaj in https://github.com/fvwmorg/fvwm3/pull/752
* fvwm-config: remove .in file by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/758
* FvwmPager make mini windows always round down. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/756
* Clean up some build warnings by @somiaj in https://github.com/fvwmorg/fvwm3/pull/759
* Move shuffle modifications. by @somiaj in https://github.com/fvwmorg/fvwm3/pull/764
* borders: treat 0 pixels as 1 pixel border by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/765
* AddWindow: don't crash reparenting by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/786
* ModuleSynchronous: don't segfault on free() by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/787
* FvwmIconMan: fix segfault in initialisation by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/800
* randr: quit when no screens found & not active by @ThomasAdam in https://github.com/fvwmorg/fvwm3/pull/801

## New Contributors
* @wfp5p made their first contribution in https://github.com/fvwmorg/fvwm3/pull/713

**Full Changelog**: https://github.com/fvwmorg/fvwm3/compare/1.0.5...1.0.6
## [1.0.5](https://github.com/fvwmorg/fvwm3/tree/1.0.5) (2022-09-28)

[Full Changelog](https://github.com/fvwmorg/fvwm3/compare/1.0.4...1.0.5)

**Breaking changes:**

- Function parser rewrite & Repeat command deprecation [\#642](https://github.com/fvwmorg/fvwm3/issues/642)
- MapRequest: don't fake map/unmap events [\#703](https://github.com/fvwmorg/fvwm3/pull/703) ([ThomasAdam](https://github.com/ThomasAdam))
- Rewrite function parser and remove the Repeat command [\#643](https://github.com/fvwmorg/fvwm3/pull/643) ([ThomasAdam](https://github.com/ThomasAdam))
- Update and cleanup SnapAttract code. [\#641](https://github.com/fvwmorg/fvwm3/pull/641) ([somiaj](https://github.com/somiaj))
- Doc: split manpages into sections [\#637](https://github.com/fvwmorg/fvwm3/pull/637) ([ThomasAdam](https://github.com/ThomasAdam))
- Remove Efence and Dmalloc support [\#635](https://github.com/fvwmorg/fvwm3/pull/635) ([ThomasAdam](https://github.com/ThomasAdam))

**Implemented enhancements:**

- A better ManualPlacement that allows drawing the geometry of the new window. [\#674](https://github.com/fvwmorg/fvwm3/issues/674)
- expand: add monitor.prev variable [\#699](https://github.com/fvwmorg/fvwm3/pull/699) ([ThomasAdam](https://github.com/ThomasAdam))
- Add AnyScreen to conditional in IconManClick [\#696](https://github.com/fvwmorg/fvwm3/pull/696) ([somiaj](https://github.com/somiaj))
- \_NET\_WM\_NAME: update to fvwm3 [\#609](https://github.com/fvwmorg/fvwm3/pull/609) ([ThomasAdam](https://github.com/ThomasAdam))

**Fixed bugs:**

- Style \* Icon cause Fvwm3 stuck in loading when restart. [\#681](https://github.com/fvwmorg/fvwm3/issues/681)
- Recaptured windows can have a negative offset away from the page they should be on [\#678](https://github.com/fvwmorg/fvwm3/issues/678)
- VLC still decorates its transient window even when explicitly given the NakedTransient style [\#673](https://github.com/fvwmorg/fvwm3/issues/673)
- configuring with `--disable-png` causes builds to fail [\#669](https://github.com/fvwmorg/fvwm3/issues/669)
- Emoji in window titles make FvwmIconMan stop showing window names. [\#654](https://github.com/fvwmorg/fvwm3/issues/654)
- Unable to initialize RandR [\#650](https://github.com/fvwmorg/fvwm3/issues/650)
- PipeRead when called from a function cannot grab pointer [\#610](https://github.com/fvwmorg/fvwm3/issues/610)
- Man Pages Cleanup [\#554](https://github.com/fvwmorg/fvwm3/issues/554)
- Windows from various pages are moved to page 0 0 on fvwm3 restart [\#694](https://github.com/fvwmorg/fvwm3/issues/694)
- Separator in menu gets focus [\#675](https://github.com/fvwmorg/fvwm3/issues/675)
- Unshading a window with WindowShade function sometimes makes the window lose "true input focus". [\#671](https://github.com/fvwmorg/fvwm3/issues/671)
- When configured with `--disable-xft` fvwm3 fails to build. [\#667](https://github.com/fvwmorg/fvwm3/issues/667)
- my fvwm config does not work with recent chromium [\#663](https://github.com/fvwmorg/fvwm3/issues/663)
- FvwmEvent event new\_desk gets triggered multiple times in multi-monitor shared setup [\#655](https://github.com/fvwmorg/fvwm3/issues/655)
- Windows with style "PositionPlacement Center" split between monitors [\#648](https://github.com/fvwmorg/fvwm3/issues/648)
- FVWM branch dv/pager-noaspect crashes with core dump [\#647](https://github.com/fvwmorg/fvwm3/issues/647)
- SnapAttraction prefers wrong window [\#631](https://github.com/fvwmorg/fvwm3/issues/631)
- FvwmPrompt is installed unstripped [\#618](https://github.com/fvwmorg/fvwm3/issues/618)
- DesktopName fails to set desktop name under described circumstances [\#606](https://github.com/fvwmorg/fvwm3/issues/606)
- FvwmEvent event monitor\_focus broken in FVWM3 1.0.4 [\#604](https://github.com/fvwmorg/fvwm3/issues/604)
- Building FvwmPrompt disables FvwmConsole, but still installs manual page. [\#597](https://github.com/fvwmorg/fvwm3/issues/597)
- Wait command in configuration file can cause unexpected issues with GeometryWindow. [\#590](https://github.com/fvwmorg/fvwm3/issues/590)
- "GeometryWindow Hide" doesn't work [\#589](https://github.com/fvwmorg/fvwm3/issues/589)
- Special characters \(umlauts\) are sometimes not displayed correctly in the window title [\#482](https://github.com/fvwmorg/fvwm3/issues/482)
- FvwmEvent: handle previous\_monitor and no longer passthrough ID  [\#701](https://github.com/fvwmorg/fvwm3/pull/701) ([ThomasAdam](https://github.com/ThomasAdam))
- doc: don't build FvwmConsole.1 if FvwmPrompt enabled [\#700](https://github.com/fvwmorg/fvwm3/pull/700) ([ThomasAdam](https://github.com/ThomasAdam))
- DesktopConfiguration shared: keep windows in-situ [\#697](https://github.com/fvwmorg/fvwm3/pull/697) ([ThomasAdam](https://github.com/ThomasAdam))
- desk\_add: fix starting desk/monitor [\#689](https://github.com/fvwmorg/fvwm3/pull/689) ([ThomasAdam](https://github.com/ThomasAdam))
- shared: fix flagging of new\_desk [\#687](https://github.com/fvwmorg/fvwm3/pull/687) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix for lock recusion in handle\_all\_expose\(\) [\#683](https://github.com/fvwmorg/fvwm3/pull/683) ([mherrb](https://github.com/mherrb))
- Asciidoc fixes [\#676](https://github.com/fvwmorg/fvwm3/pull/676) ([topcat001](https://github.com/topcat001))
- grow: ignore transient windows [\#627](https://github.com/fvwmorg/fvwm3/pull/627) ([ThomasAdam](https://github.com/ThomasAdam))
- MoveToScreen: fix NULL-dereference [\#605](https://github.com/fvwmorg/fvwm3/pull/605) ([ThomasAdam](https://github.com/ThomasAdam))
- Bugfix: fvwm-menu-desktop --get-menus [\#593](https://github.com/fvwmorg/fvwm3/pull/593) ([somiaj](https://github.com/somiaj))

**Closed issues:**

- Code Cleanup: Codacy issues list [\#107](https://github.com/fvwmorg/fvwm3/issues/107)

**Merged pull requests:**

- avoid sprintf\(%n\) [\#653](https://github.com/fvwmorg/fvwm3/pull/653) ([omar-polo](https://github.com/omar-polo))
- FvwmPrompt: add GOFLAGS to build stripped [\#619](https://github.com/fvwmorg/fvwm3/pull/619) ([Zirias](https://github.com/Zirias))
- Wait: don't run until windows are captured [\#592](https://github.com/fvwmorg/fvwm3/pull/592) ([ThomasAdam](https://github.com/ThomasAdam))
- CMD\_GeometryWindow: Move NULL check. [\#591](https://github.com/fvwmorg/fvwm3/pull/591) ([somiaj](https://github.com/somiaj))
- cleanup: address warnings [\#705](https://github.com/fvwmorg/fvwm3/pull/705) ([ThomasAdam](https://github.com/ThomasAdam))
- modconf: disable debug [\#698](https://github.com/fvwmorg/fvwm3/pull/698) ([ThomasAdam](https://github.com/ThomasAdam))
- GotoDesk: avoid over-eager matching [\#695](https://github.com/fvwmorg/fvwm3/pull/695) ([ThomasAdam](https://github.com/ThomasAdam))
- update\_fvwm\_monitor: cosmetic change [\#692](https://github.com/fvwmorg/fvwm3/pull/692) ([ThomasAdam](https://github.com/ThomasAdam))
- menuitem: set selectable when not a separator [\#690](https://github.com/fvwmorg/fvwm3/pull/690) ([ThomasAdam](https://github.com/ThomasAdam))
- Windowshade: explicitly set input focus [\#672](https://github.com/fvwmorg/fvwm3/pull/672) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmPrompt: update core modules [\#665](https://github.com/fvwmorg/fvwm3/pull/665) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmPrompt: update vendor deps [\#664](https://github.com/fvwmorg/fvwm3/pull/664) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix selectable flag for the Resize window operation menu item [\#656](https://github.com/fvwmorg/fvwm3/pull/656) ([topcat001](https://github.com/topcat001))
- Fix ExitFunction [\#651](https://github.com/fvwmorg/fvwm3/pull/651) ([pghvlaans](https://github.com/pghvlaans))
- DisplayPosition: fix segfault [\#645](https://github.com/fvwmorg/fvwm3/pull/645) ([ThomasAdam](https://github.com/ThomasAdam))
- convert UPDATE\_FVWM\_SCREEN from macro to function [\#644](https://github.com/fvwmorg/fvwm3/pull/644) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/dv logfile [\#640](https://github.com/fvwmorg/fvwm3/pull/640) ([ThomasAdam](https://github.com/ThomasAdam))
- Resize: fix resize bounds [\#638](https://github.com/fvwmorg/fvwm3/pull/638) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/dv2 [\#636](https://github.com/fvwmorg/fvwm3/pull/636) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/dv misc [\#634](https://github.com/fvwmorg/fvwm3/pull/634) ([ThomasAdam](https://github.com/ThomasAdam))
- Reject out of range windows for Move and Resize commands. [\#633](https://github.com/fvwmorg/fvwm3/pull/633) ([ThomasAdam](https://github.com/ThomasAdam))
- FVWMMFL: ignore SIGPIPE [\#632](https://github.com/fvwmorg/fvwm3/pull/632) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/dv ifdev [\#630](https://github.com/fvwmorg/fvwm3/pull/630) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/from dv [\#629](https://github.com/fvwmorg/fvwm3/pull/629) ([ThomasAdam](https://github.com/ThomasAdam))
- DesktopName: don't duplicate entries with same name [\#607](https://github.com/fvwmorg/fvwm3/pull/607) ([ThomasAdam](https://github.com/ThomasAdam))
- Patches from Debian [\#599](https://github.com/fvwmorg/fvwm3/pull/599) ([ThomasAdam](https://github.com/ThomasAdam))

## [1.0.4](https://github.com/fvwmorg/fvwm3/tree/1.0.4) (2021-07-17)

[Full Changelog](https://github.com/fvwmorg/fvwm3/compare/1.0.3...1.0.4)

**Breaking changes:**

- Deprecate Label for FvwmPager [\#342](https://github.com/fvwmorg/fvwm3/issues/342)
- Extend \*FvwmIconMan:Resolution to include specific Desktop / Pager [\#455](https://github.com/fvwmorg/fvwm3/issues/455)
- Replace libbson with cJSON [\#408](https://github.com/fvwmorg/fvwm3/issues/408)
- FvwmButtons: Shrink windows when honoring Hints. [\#577](https://github.com/fvwmorg/fvwm3/pull/577) ([somiaj](https://github.com/somiaj))
- Replace libbson with cJSON [\#571](https://github.com/fvwmorg/fvwm3/pull/571) ([ThomasAdam](https://github.com/ThomasAdam))
- Add commands to configure the size/position window. [\#558](https://github.com/fvwmorg/fvwm3/pull/558) ([ThomasAdam](https://github.com/ThomasAdam))
- Retire FvwmTile and FvwmCascade wrappers. [\#515](https://github.com/fvwmorg/fvwm3/pull/515) ([somiaj](https://github.com/somiaj))

**Implemented enhancements:**

- Set min. size for windows shown in pager [\#542](https://github.com/fvwmorg/fvwm3/issues/542)
- Moving windows: allow for "warping" to other windows in a given direction [\#540](https://github.com/fvwmorg/fvwm3/issues/540)
- Update monitor struct to know if monintor edges are OUTSIDE\_EDGE or INSIDE\_EDGE [\#523](https://github.com/fvwmorg/fvwm3/issues/523)
- Two issues with the WindowList [\#151](https://github.com/fvwmorg/fvwm3/issues/151)
- Feature Request: Enable using the 'c' unit with the "MinWindowSize" and "MaxWindowSize" styles [\#145](https://github.com/fvwmorg/fvwm3/issues/145)
- Allow per monitor EdgeCommand and EdgeLeaveCommand [\#582](https://github.com/fvwmorg/fvwm3/pull/582) ([somiaj](https://github.com/somiaj))
- expand: add prev\_{desk,pagex,pagey} [\#579](https://github.com/fvwmorg/fvwm3/pull/579) ([ThomasAdam](https://github.com/ThomasAdam))
- Improve translations [\#568](https://github.com/fvwmorg/fvwm3/pull/568) ([somiaj](https://github.com/somiaj))
- Cleanup SetRCDefaults\(\) [\#567](https://github.com/fvwmorg/fvwm3/pull/567) ([somiaj](https://github.com/somiaj))
- Add local configuration file to the default-config. [\#557](https://github.com/fvwmorg/fvwm3/pull/557) ([somiaj](https://github.com/somiaj))
- Add icon for Run Command. [\#552](https://github.com/fvwmorg/fvwm3/pull/552) ([somiaj](https://github.com/somiaj))
- Add command: Move shuffle \[flags\] direction\(s\) [\#550](https://github.com/fvwmorg/fvwm3/pull/550) ([somiaj](https://github.com/somiaj))
- expand: add desk, pagex, pagey variables [\#539](https://github.com/fvwmorg/fvwm3/pull/539) ([ThomasAdam](https://github.com/ThomasAdam))
- Add a screen option to the Scroll command. [\#531](https://github.com/fvwmorg/fvwm3/pull/531) ([ThomasAdam](https://github.com/ThomasAdam))
- RandR: support RandRFunc for screen changes [\#525](https://github.com/fvwmorg/fvwm3/pull/525) ([ThomasAdam](https://github.com/ThomasAdam))

**Fixed bugs:**

- Pager do not show smalls windows in the correct place when snapped to the edge [\#541](https://github.com/fvwmorg/fvwm3/issues/541)
- EwmhBaseStruts glitch when using screen with different resolutions [\#66](https://github.com/fvwmorg/fvwm3/issues/66)
- Fvwm segfaults parsing module configuration [\#575](https://github.com/fvwmorg/fvwm3/issues/575)
- Swallowing FvwmPager inside FvwmButtons breaks resizing FvwmButtons when aspect ratio resizing is used [\#573](https://github.com/fvwmorg/fvwm3/issues/573)
- Move X Y Warp doesn't move pointer to window. [\#551](https://github.com/fvwmorg/fvwm3/issues/551)
- Maximize fullscreen command does not clear \_NET\_WM\_STATE\_FULLSCREEN when exiting fullscreen [\#545](https://github.com/fvwmorg/fvwm3/issues/545)
- EdgeLeaveCommand don't work or need a page change to work [\#543](https://github.com/fvwmorg/fvwm3/issues/543)
- FvwmPager Icon view fix background color. [\#537](https://github.com/fvwmorg/fvwm3/issues/537)
- FvwmPager with bad aspect ratio on dual-head display [\#522](https://github.com/fvwmorg/fvwm3/issues/522)
- AnimatedMove [\#513](https://github.com/fvwmorg/fvwm3/issues/513)
- Spelling errors found by lintian. [\#511](https://github.com/fvwmorg/fvwm3/issues/511)
- SnapAttraction: take into account individual monitors [\#466](https://github.com/fvwmorg/fvwm3/issues/466)
- FvwmPager not taking into account global screen dimensions when configured with DeskTopScale [\#223](https://github.com/fvwmorg/fvwm3/issues/223)
- FvwmPager: moving windows inside FvwmPager is inconsistent [\#198](https://github.com/fvwmorg/fvwm3/issues/198)
- Add force\_icons\_size kludge to .stalonetrayrc. [\#581](https://github.com/fvwmorg/fvwm3/pull/581) ([somiaj](https://github.com/somiaj))
- Fix pass through binding logic. [\#570](https://github.com/fvwmorg/fvwm3/pull/570) ([somiaj](https://github.com/somiaj))
- Make default-config greyed colorset grey. [\#566](https://github.com/fvwmorg/fvwm3/pull/566) ([somiaj](https://github.com/somiaj))
- Cleanup FvwmScript manual page. [\#565](https://github.com/fvwmorg/fvwm3/pull/565) ([somiaj](https://github.com/somiaj))
- GNOME: remove DO\_IGNORE\_GNOME\_HINTS [\#556](https://github.com/fvwmorg/fvwm3/pull/556) ([lgsobalvarro](https://github.com/lgsobalvarro))
- Unmaximize: restore \_NET\_WM\_STATE [\#546](https://github.com/fvwmorg/fvwm3/pull/546) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix compiler warnings in modules/FvwmScript/Instructions.c [\#544](https://github.com/fvwmorg/fvwm3/pull/544) ([pm215](https://github.com/pm215))
- Rework FvwmPager to move windows easier [\#536](https://github.com/fvwmorg/fvwm3/pull/536) ([ThomasAdam](https://github.com/ThomasAdam))
- Move: disable working area when screen given [\#535](https://github.com/fvwmorg/fvwm3/pull/535) ([ThomasAdam](https://github.com/ThomasAdam))
- Make RightPanel use primary monitor dimensions. [\#530](https://github.com/fvwmorg/fvwm3/pull/530) ([somiaj](https://github.com/somiaj))
- Set base struts only for primary monitor in default-config. [\#528](https://github.com/fvwmorg/fvwm3/pull/528) ([somiaj](https://github.com/somiaj))
- Change FvwmPager Logic for initial window size. [\#527](https://github.com/fvwmorg/fvwm3/pull/527) ([somiaj](https://github.com/somiaj))
- EWMH\_GetWorkArea use monitor dimensions. [\#526](https://github.com/fvwmorg/fvwm3/pull/526) ([somiaj](https://github.com/somiaj))
- Make SnapAttraction snap to edges of all monitors. [\#521](https://github.com/fvwmorg/fvwm3/pull/521) ([somiaj](https://github.com/somiaj))
- Update FvwmCommand to allow multiple args. [\#514](https://github.com/fvwmorg/fvwm3/pull/514) ([somiaj](https://github.com/somiaj))

**Merged pull requests:**

- Extend FvwmIconMan Resolution configuration. [\#561](https://github.com/fvwmorg/fvwm3/pull/561) ([somiaj](https://github.com/somiaj))
- Allow Min/Max WindowSize style to use client size [\#560](https://github.com/fvwmorg/fvwm3/pull/560) ([somiaj](https://github.com/somiaj))
- Add more columns to default-config menu ItemFormat. [\#559](https://github.com/fvwmorg/fvwm3/pull/559) ([somiaj](https://github.com/somiaj))
- Fix broken link. [\#529](https://github.com/fvwmorg/fvwm3/pull/529) ([somiaj](https://github.com/somiaj))
- Spelling error fixes. [\#512](https://github.com/fvwmorg/fvwm3/pull/512) ([somiaj](https://github.com/somiaj))
- Working on 1.0.4 [\#509](https://github.com/fvwmorg/fvwm3/pull/509) ([ThomasAdam](https://github.com/ThomasAdam))
- release/1.0.4 [\#585](https://github.com/fvwmorg/fvwm3/pull/585) ([ThomasAdam](https://github.com/ThomasAdam))
- module expand: don't overwrite previous expansion [\#576](https://github.com/fvwmorg/fvwm3/pull/576) ([ThomasAdam](https://github.com/ThomasAdam))
- conditional: fix whitespace/comma parsing [\#572](https://github.com/fvwmorg/fvwm3/pull/572) ([ThomasAdam](https://github.com/ThomasAdam))
- Configure a colorset for XDGMenu options. [\#564](https://github.com/fvwmorg/fvwm3/pull/564) ([somiaj](https://github.com/somiaj))
- Menu: add option to grey entries out [\#563](https://github.com/fvwmorg/fvwm3/pull/563) ([ThomasAdam](https://github.com/ThomasAdam))
- Remove \*FvwmPager: Label configuration option. [\#562](https://github.com/fvwmorg/fvwm3/pull/562) ([somiaj](https://github.com/somiaj))
- move: Warp: move pointer to centre of window [\#553](https://github.com/fvwmorg/fvwm3/pull/553) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmPager: Improvments with dealing with tiny windows on tiny pagers. [\#548](https://github.com/fvwmorg/fvwm3/pull/548) ([somiaj](https://github.com/somiaj))
- PanFrame improvements [\#547](https://github.com/fvwmorg/fvwm3/pull/547) ([ThomasAdam](https://github.com/ThomasAdam))
- pager: teach Icon view about colorsets [\#538](https://github.com/fvwmorg/fvwm3/pull/538) ([ThomasAdam](https://github.com/ThomasAdam))
- placement: fix mouse positioning [\#533](https://github.com/fvwmorg/fvwm3/pull/533) ([ThomasAdam](https://github.com/ThomasAdam))
- EdgeScroll: a few improvements [\#524](https://github.com/fvwmorg/fvwm3/pull/524) ([ThomasAdam](https://github.com/ThomasAdam))
- Update manual for Echo/EchoFuncDefinition [\#520](https://github.com/fvwmorg/fvwm3/pull/520) ([somiaj](https://github.com/somiaj))
- release: remove dev-docs from release tarball [\#518](https://github.com/fvwmorg/fvwm3/pull/518) ([ThomasAdam](https://github.com/ThomasAdam))
- configure: remove stale references to BUGADDR [\#517](https://github.com/fvwmorg/fvwm3/pull/517) ([ThomasAdam](https://github.com/ThomasAdam))
- Configuration tweaks [\#516](https://github.com/fvwmorg/fvwm3/pull/516) ([ThomasAdam](https://github.com/ThomasAdam))
- build: add CHANGELOG.md to dist [\#510](https://github.com/fvwmorg/fvwm3/pull/510) ([ThomasAdam](https://github.com/ThomasAdam))

## [1.0.3](https://github.com/fvwmorg/fvwm3/tree/1.0.3) (2021-05-30)

[Full Changelog](https://github.com/fvwmorg/fvwm3/compare/1.0.2...1.0.3)

**Breaking changes:**

- perllib: remove references to Tk [\#502](https://github.com/fvwmorg/fvwm3/pull/502) ([ThomasAdam](https://github.com/ThomasAdam))
- Remove xpmroot link. [\#495](https://github.com/fvwmorg/fvwm3/pull/495) ([somiaj](https://github.com/somiaj))
- Remove FvwmConsoleC.pl front-end [\#379](https://github.com/fvwmorg/fvwm3/pull/379) ([slazav](https://github.com/slazav))

**Implemented enhancements:**

- FvwmIconMan must handle resolution settings better in per-monitor mode [\#396](https://github.com/fvwmorg/fvwm3/issues/396)
- fvwm2 compat: provide FvwmCommandS symlink to Module FvwmMFL [\#391](https://github.com/fvwmorg/fvwm3/issues/391)
- Support desktop configuration similar to xmonad/herbstluftwm [\#260](https://github.com/fvwmorg/fvwm3/issues/260)
- DesktopConfiguration: introduce `shared` option [\#452](https://github.com/fvwmorg/fvwm3/pull/452) ([ThomasAdam](https://github.com/ThomasAdam))
- Improve runcmd in the default-config. [\#506](https://github.com/fvwmorg/fvwm3/pull/506) ([somiaj](https://github.com/somiaj))
- Conditionals: add TitleAt{Top,Bottom,Left,Right} [\#439](https://github.com/fvwmorg/fvwm3/pull/439) ([ThomasAdam](https://github.com/ThomasAdam))
- conditionals: add HasBorders/HasTitle [\#416](https://github.com/fvwmorg/fvwm3/pull/416) ([ThomasAdam](https://github.com/ThomasAdam))

**Fixed bugs:**

- Core dump at start with NsCDE as configuration [\#464](https://github.com/fvwmorg/fvwm3/issues/464)
- rename binary fvwm3 -\> fvwm [\#440](https://github.com/fvwmorg/fvwm3/issues/440)
- Memory leak in \_\_execute\_function [\#425](https://github.com/fvwmorg/fvwm3/issues/425)
- FvwmPager: Division by zero in x\_pager.c [\#413](https://github.com/fvwmorg/fvwm3/issues/413)
- fvwm crash with Program terminated with signal SIGABRT [\#383](https://github.com/fvwmorg/fvwm3/issues/383)
- Fvwm-menu-desktop fails if used with --get-menus [\#234](https://github.com/fvwmorg/fvwm3/issues/234)
- fvwm/session.c has left FVWM\_SM\_DEBUG\_FILES enabled [\#480](https://github.com/fvwmorg/fvwm3/issues/480)
- Desktop Names wrongly reported by wmctrl under fvwm3 [\#477](https://github.com/fvwmorg/fvwm3/issues/477)
- Font shadow offset miscalculated [\#475](https://github.com/fvwmorg/fvwm3/issues/475)
- Moving shaded windows across screens [\#473](https://github.com/fvwmorg/fvwm3/issues/473)
- Two PanFrame/EdgeScroll issues. \(Regression cf. FVWM2.\) [\#459](https://github.com/fvwmorg/fvwm3/issues/459)
- Actions from a pinned menu are triggered by mouse move instead of mouse release [\#456](https://github.com/fvwmorg/fvwm3/issues/456)
- Font-rendering causes fvwm to lock-up [\#446](https://github.com/fvwmorg/fvwm3/issues/446)
- \(CurrentPage, AnyScreen\) calculation slightly too generous. \(Regression cf. fvwm2.\) [\#443](https://github.com/fvwmorg/fvwm3/issues/443)
- \_NET\_CURRENT\_DESKTOP tracking breaks google-chrome [\#442](https://github.com/fvwmorg/fvwm3/issues/442)
- Changing EdgeThickness moves PanFrameRight.win to a wrong position [\#436](https://github.com/fvwmorg/fvwm3/issues/436)
- FvwmPager shows app on wrong page with StartsOnDesk [\#433](https://github.com/fvwmorg/fvwm3/issues/433)
- 21 byte memory leak in merge\_styles \(3 tiny leaks of 7 bytes\) [\#430](https://github.com/fvwmorg/fvwm3/issues/430)
- Some files/dirs not removed by make uninstall [\#422](https://github.com/fvwmorg/fvwm3/issues/422)
- Invalid read of size 1 \(reading freed memory\) [\#418](https://github.com/fvwmorg/fvwm3/issues/418)
- PanFrames: surround monitor edges only for global mode [\#398](https://github.com/fvwmorg/fvwm3/issues/398)
- RandR: Maximizing windows between boundaries picks wrong monitor [\#394](https://github.com/fvwmorg/fvwm3/issues/394)
- FvwmCommand is missing a man page [\#393](https://github.com/fvwmorg/fvwm3/issues/393)
- FvwmIconMan lists wrong windows in \(certain?\) multi-monitor configurations. [\#390](https://github.com/fvwmorg/fvwm3/issues/390)
- EdgeScroll does not work [\#381](https://github.com/fvwmorg/fvwm3/issues/381)
- libbson detection fails in Linux. [\#375](https://github.com/fvwmorg/fvwm3/issues/375)
- SkipMapping disables StartsOnPage/StartsOnDesk [\#373](https://github.com/fvwmorg/fvwm3/issues/373)
- Pager: don't restrict new\_desk to monitor boundaries [\#434](https://github.com/fvwmorg/fvwm3/pull/434) ([ThomasAdam](https://github.com/ThomasAdam))
- Recapture: fix erroneous maximizing of windows [\#504](https://github.com/fvwmorg/fvwm3/pull/504) ([ThomasAdam](https://github.com/ThomasAdam))
- Ensure make uninstall removes default-config links. [\#496](https://github.com/fvwmorg/fvwm3/pull/496) ([somiaj](https://github.com/somiaj))
- Update manpages in default-config [\#493](https://github.com/fvwmorg/fvwm3/pull/493) ([somiaj](https://github.com/somiaj))
- Fix the pixel overflow problem and clean up the math. [\#451](https://github.com/fvwmorg/fvwm3/pull/451) ([mikeandmore](https://github.com/mikeandmore))
- fix with some pixels off for 3d buttons [\#444](https://github.com/fvwmorg/fvwm3/pull/444) ([mikeandmore](https://github.com/mikeandmore))
- Only allocate a copy of style strings if requested. [\#441](https://github.com/fvwmorg/fvwm3/pull/441) ([Quipyowert2](https://github.com/Quipyowert2))
- PanFrames: handle DesktopConfiguration changes [\#438](https://github.com/fvwmorg/fvwm3/pull/438) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix 22kb memory leak. [\#426](https://github.com/fvwmorg/fvwm3/pull/426) ([Quipyowert2](https://github.com/Quipyowert2))
- Correct menu error short option from `-t` to `-e` [\#424](https://github.com/fvwmorg/fvwm3/pull/424) ([djwf](https://github.com/djwf))
- Fix file handle leak. [\#421](https://github.com/fvwmorg/fvwm3/pull/421) ([Quipyowert2](https://github.com/Quipyowert2))
- FvwmPager: Fix division by zero [\#415](https://github.com/fvwmorg/fvwm3/pull/415) ([Quipyowert2](https://github.com/Quipyowert2))
- LocaleCharset: initialise with font [\#406](https://github.com/fvwmorg/fvwm3/pull/406) ([ThomasAdam](https://github.com/ThomasAdam))
- fvwm-root: fix Makefile [\#387](https://github.com/fvwmorg/fvwm3/pull/387) ([ThomasAdam](https://github.com/ThomasAdam))
- Remove explicit path to bson.h \(closes \#375\) [\#386](https://github.com/fvwmorg/fvwm3/pull/386) ([slazav](https://github.com/slazav))
- Fix system.fvwm2rc not found [\#382](https://github.com/fvwmorg/fvwm3/pull/382) ([phileimer](https://github.com/phileimer))
- fix error in manpage name: fvwm-config-2.6 -\> fvwm-convert-2.6 [\#377](https://github.com/fvwmorg/fvwm3/pull/377) ([slazav](https://github.com/slazav))

**Closed issues:**

- perllib: remove Tk bindings [\#501](https://github.com/fvwmorg/fvwm3/issues/501)
- Documentation: man pages should honour `program-transform-name` [\#492](https://github.com/fvwmorg/fvwm3/issues/492)

**Merged pull requests:**

- Manpages renamed by automakes renaming options. [\#500](https://github.com/fvwmorg/fvwm3/pull/500) ([somiaj](https://github.com/somiaj))
- Move locale directory to $FVWM\_DATADIR [\#499](https://github.com/fvwmorg/fvwm3/pull/499) ([somiaj](https://github.com/somiaj))
- Update configure --help to provide --enable-mandoc [\#498](https://github.com/fvwmorg/fvwm3/pull/498) ([somiaj](https://github.com/somiaj))
- fix shadow position bug [\#476](https://github.com/fvwmorg/fvwm3/pull/476) ([mikeandmore](https://github.com/mikeandmore))
- \_NET\_CURRENT\_DESKTOP: update across monitor boundaries [\#449](https://github.com/fvwmorg/fvwm3/pull/449) ([ThomasAdam](https://github.com/ThomasAdam))
- fix uninitialized value and bad free [\#447](https://github.com/fvwmorg/fvwm3/pull/447) ([mikeandmore](https://github.com/mikeandmore))
- Fix over-eager window positioning [\#445](https://github.com/fvwmorg/fvwm3/pull/445) ([ThomasAdam](https://github.com/ThomasAdam))
- PanFrames: correct right panframe location [\#437](https://github.com/fvwmorg/fvwm3/pull/437) ([ThomasAdam](https://github.com/ThomasAdam))
- Revert "Fix a 21 byte memory leak." [\#435](https://github.com/fvwmorg/fvwm3/pull/435) ([ThomasAdam](https://github.com/ThomasAdam))
- 644: libs/FImage.c [\#432](https://github.com/fvwmorg/fvwm3/pull/432) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix a 21 byte memory leak. [\#431](https://github.com/fvwmorg/fvwm3/pull/431) ([Quipyowert2](https://github.com/Quipyowert2))
- Fix double free. [\#429](https://github.com/fvwmorg/fvwm3/pull/429) ([Quipyowert2](https://github.com/Quipyowert2))
- Fix several tiny memory leaks [\#428](https://github.com/fvwmorg/fvwm3/pull/428) ([Quipyowert2](https://github.com/Quipyowert2))
- Fix returning pointer to freed memory in FCreateFImage. [\#427](https://github.com/fvwmorg/fvwm3/pull/427) ([Quipyowert2](https://github.com/Quipyowert2))
- Remove package \(libx11-dev\) already present in core dependencies [\#423](https://github.com/fvwmorg/fvwm3/pull/423) ([djwf](https://github.com/djwf))
- Fix invalid read of size 1 error from Valgrind. [\#419](https://github.com/fvwmorg/fvwm3/pull/419) ([Quipyowert2](https://github.com/Quipyowert2))
- Xft2 with fallback [\#403](https://github.com/fvwmorg/fvwm3/pull/403) ([mikeandmore](https://github.com/mikeandmore))
- move x11 headers out of config.h [\#400](https://github.com/fvwmorg/fvwm3/pull/400) ([mikeandmore](https://github.com/mikeandmore))
- Release 1.0.3 [\#508](https://github.com/fvwmorg/fvwm3/pull/508) ([ThomasAdam](https://github.com/ThomasAdam))
- Add DesktopConfigure to config [\#505](https://github.com/fvwmorg/fvwm3/pull/505) ([lgsobalvarro](https://github.com/lgsobalvarro))
- manpage: add FvwmCommand [\#503](https://github.com/fvwmorg/fvwm3/pull/503) ([ThomasAdam](https://github.com/ThomasAdam))
- Notifier: switch IRC actions [\#489](https://github.com/fvwmorg/fvwm3/pull/489) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmPrompt: add vendored libraries [\#485](https://github.com/fvwmorg/fvwm3/pull/485) ([ThomasAdam](https://github.com/ThomasAdam))
- session: don't leave debug files around [\#483](https://github.com/fvwmorg/fvwm3/pull/483) ([ThomasAdam](https://github.com/ThomasAdam))
- absolute\_geometry: clamp check to shaded windows [\#479](https://github.com/fvwmorg/fvwm3/pull/479) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/gh 477 [\#478](https://github.com/fvwmorg/fvwm3/pull/478) ([ThomasAdam](https://github.com/ThomasAdam))
- absolute geometry: update screen [\#474](https://github.com/fvwmorg/fvwm3/pull/474) ([ThomasAdam](https://github.com/ThomasAdam))
- placement: don't clobber monitor if global [\#465](https://github.com/fvwmorg/fvwm3/pull/465) ([ThomasAdam](https://github.com/ThomasAdam))
- PanFrame improvements [\#460](https://github.com/fvwmorg/fvwm3/pull/460) ([ThomasAdam](https://github.com/ThomasAdam))
- EWMH: CurrentDesktop improvements [\#458](https://github.com/fvwmorg/fvwm3/pull/458) ([ThomasAdam](https://github.com/ThomasAdam))
- Tear-off menu: don't mask pos\_hints [\#457](https://github.com/fvwmorg/fvwm3/pull/457) ([ThomasAdam](https://github.com/ThomasAdam))
- Deprecate HAVE\_XRandR/FScreenIsEnabled\(\) [\#410](https://github.com/fvwmorg/fvwm3/pull/410) ([ThomasAdam](https://github.com/ThomasAdam))
- PanFrames: restore global panframe behaviour [\#399](https://github.com/fvwmorg/fvwm3/pull/399) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmIconMan: handle resolutions for per-monitor [\#397](https://github.com/fvwmorg/fvwm3/pull/397) ([ThomasAdam](https://github.com/ThomasAdam))
- Maximizing: handle RandR screen selection better [\#395](https://github.com/fvwmorg/fvwm3/pull/395) ([ThomasAdam](https://github.com/ThomasAdam))
- fvwm2: provide compat wrapper FvwmCommandS [\#392](https://github.com/fvwmorg/fvwm3/pull/392) ([ThomasAdam](https://github.com/ThomasAdam))
- Revert "Remove SAFEFREE macro" [\#388](https://github.com/fvwmorg/fvwm3/pull/388) ([ThomasAdam](https://github.com/ThomasAdam))
- PanFrames: always keep mapped [\#384](https://github.com/fvwmorg/fvwm3/pull/384) ([ThomasAdam](https://github.com/ThomasAdam))
- update\_fvwm\_screen: don't lose desk from StartsOnScreen [\#374](https://github.com/fvwmorg/fvwm3/pull/374) ([ThomasAdam](https://github.com/ThomasAdam))

## [1.0.2](https://github.com/fvwmorg/fvwm3/tree/1.0.2) (2020-12-20)

[Full Changelog](https://github.com/fvwmorg/fvwm3/compare/1.0.1...1.0.2)

**Breaking changes:**

- Deprecate librplay support in FvwmEvent [\#316](https://github.com/fvwmorg/fvwm3/issues/316)
- documentation: remove docbook in favour of asciidoc [\#290](https://github.com/fvwmorg/fvwm3/pull/290) ([ThomasAdam](https://github.com/ThomasAdam))

**Implemented enhancements:**

- \[feature-request\] Global desktop with predefined resolutions [\#248](https://github.com/fvwmorg/fvwm3/issues/248)
- Move to Python 3 [\#233](https://github.com/fvwmorg/fvwm3/issues/233)
- Add expansion variables for a window's X/Y page [\#255](https://github.com/fvwmorg/fvwm3/issues/255)
- Fvwm should provide a Status option [\#253](https://github.com/fvwmorg/fvwm3/issues/253)

**Fixed bugs:**

- bson\_as\_relaxed\_extended\_json\(\) is not available [\#286](https://github.com/fvwmorg/fvwm3/issues/286)
- EdgeResistance command not working? [\#285](https://github.com/fvwmorg/fvwm3/issues/285)
- FvwmScript - Crashes on input to TextField widget [\#272](https://github.com/fvwmorg/fvwm3/issues/272)
- FvwmButtons Geometry - @g tag positions objects on active monitor instead of globally  [\#269](https://github.com/fvwmorg/fvwm3/issues/269)
- Maximize on second monitor gives wrong window size [\#250](https://github.com/fvwmorg/fvwm3/issues/250)
- Man page `fvwm3.1` not built by default [\#246](https://github.com/fvwmorg/fvwm3/issues/246)
- FvwmPager sometimes ignores styles [\#142](https://github.com/fvwmorg/fvwm3/issues/142)
- FvwmMFL can start many instances [\#348](https://github.com/fvwmorg/fvwm3/issues/348)
- Windows are disappearing from screen when they resized and placed again [\#338](https://github.com/fvwmorg/fvwm3/issues/338)
- FvwmBacker.c:699:7: error: format not a string literal and no format arguments \[-Werror=format-security\] [\#334](https://github.com/fvwmorg/fvwm3/issues/334)
- Status: desk tracking is broken with sticky windows [\#331](https://github.com/fvwmorg/fvwm3/issues/331)
- FvwmButtons: Title parameter doesn't allow "-" [\#313](https://github.com/fvwmorg/fvwm3/issues/313)
- Lack of FvwmCommand can break existing configuration [\#312](https://github.com/fvwmorg/fvwm3/issues/312)
- Menu placement wrong with multi monitor when position given [\#311](https://github.com/fvwmorg/fvwm3/issues/311)
- FvwmPager: pin new\_desk events to monitor instance for per-monitor mode [\#296](https://github.com/fvwmorg/fvwm3/issues/296)
- FvwmPager: windows tracked incorrectly when moving between monitors [\#294](https://github.com/fvwmorg/fvwm3/issues/294)
- Status: not updating on browser tab switching [\#274](https://github.com/fvwmorg/fvwm3/issues/274)
- EwmhStruts - Does not affect entirety of X screen, only specific monitor [\#271](https://github.com/fvwmorg/fvwm3/issues/271)
- Configuration parsing does not read FvwmPager module config line if prefixed with Test condition. [\#267](https://github.com/fvwmorg/fvwm3/issues/267)
- Style PositionPlacement ignores y percentage [\#265](https://github.com/fvwmorg/fvwm3/issues/265)
- Maximize window on primary screen gives small window [\#264](https://github.com/fvwmorg/fvwm3/issues/264)
- FvwmPager and FvwmIconMan do not update after GotoDesk [\#262](https://github.com/fvwmorg/fvwm3/issues/262)
- status:  fix bson\_t detection [\#257](https://github.com/fvwmorg/fvwm3/issues/257)
- Properties of windows are lost after a restart [\#143](https://github.com/fvwmorg/fvwm3/issues/143)
- EdgeScroll needs thinking about for per-monitor setup [\#82](https://github.com/fvwmorg/fvwm3/issues/82)
- Panframes: switching between desktops not reliable / broken [\#34](https://github.com/fvwmorg/fvwm3/issues/34)
- ewmhbasestruts: handle `0 0 0 0` when maximizing [\#345](https://github.com/fvwmorg/fvwm3/pull/345) ([ThomasAdam](https://github.com/ThomasAdam))
- Make bin/FvwmCommand.in use @PYTHON@ [\#339](https://github.com/fvwmorg/fvwm3/pull/339) ([NsCDE](https://github.com/NsCDE))
- FvwmPager: track windows assigned to pager's screen [\#295](https://github.com/fvwmorg/fvwm3/pull/295) ([ThomasAdam](https://github.com/ThomasAdam))

**Closed issues:**

- FvwmRearrange does not work on FVWM3 [\#346](https://github.com/fvwmorg/fvwm3/issues/346)
- Desktop App Menu Flickers [\#308](https://github.com/fvwmorg/fvwm3/issues/308)
- Optional dependency SVG development library missing in INSTALL.md [\#287](https://github.com/fvwmorg/fvwm3/issues/287)
- Fvwm and UI Design. [\#279](https://github.com/fvwmorg/fvwm3/issues/279)
- Q: open-desktop icon tray [\#252](https://github.com/fvwmorg/fvwm3/issues/252)
- Safe sprintf call [\#164](https://github.com/fvwmorg/fvwm3/issues/164)
- Testing notes for FVWM3-rc.X release candidate [\#65](https://github.com/fvwmorg/fvwm3/issues/65)
- FvwmScript core dump on signal 6 when called with \(LaunchScript $FOO\) from another FvwmScript [\#356](https://github.com/fvwmorg/fvwm3/issues/356)
- FvwmPager: geometry string with @monitor not taken into account [\#310](https://github.com/fvwmorg/fvwm3/issues/310)

**Merged pull requests:**

- PlaceAgain: don't clobber desk [\#341](https://github.com/fvwmorg/fvwm3/pull/341) ([ThomasAdam](https://github.com/ThomasAdam))
- Introduce Python 3 based FvwmCommand compatibility script [\#337](https://github.com/fvwmorg/fvwm3/pull/337) ([NsCDE](https://github.com/NsCDE))
- libs: remove CatString2/CatString3 [\#336](https://github.com/fvwmorg/fvwm3/pull/336) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmButtons: Allow Title to contain just "-" [\#314](https://github.com/fvwmorg/fvwm3/pull/314) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmPager: fix geometry string values when using @MONITORNAME [\#309](https://github.com/fvwmorg/fvwm3/pull/309) ([ThomasAdam](https://github.com/ThomasAdam))
- Increase memory space to avoid overflow [\#306](https://github.com/fvwmorg/fvwm3/pull/306) ([klebertarcisio](https://github.com/klebertarcisio))
- CI: additional flags [\#304](https://github.com/fvwmorg/fvwm3/pull/304) ([ThomasAdam](https://github.com/ThomasAdam))
- CI: build CHANGELOG on master only [\#302](https://github.com/fvwmorg/fvwm3/pull/302) ([ThomasAdam](https://github.com/ThomasAdam))
- CI: enable CHANGELOG generation on push/PR [\#301](https://github.com/fvwmorg/fvwm3/pull/301) ([ThomasAdam](https://github.com/ThomasAdam))
- OpenBSD/SunOS: fix compilation problems [\#300](https://github.com/fvwmorg/fvwm3/pull/300) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmPager: filter out new\_desk events per-monitor [\#297](https://github.com/fvwmorg/fvwm3/pull/297) ([ThomasAdam](https://github.com/ThomasAdam))
- clean up the headers [\#293](https://github.com/fvwmorg/fvwm3/pull/293) ([mikeandmore](https://github.com/mikeandmore))
- FvwmPrompt: add basic manpage [\#292](https://github.com/fvwmorg/fvwm3/pull/292) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmForm: use libevent for timer instead of signal [\#289](https://github.com/fvwmorg/fvwm3/pull/289) ([phileimer](https://github.com/phileimer))
- Add SVG library as an optional dependency [\#288](https://github.com/fvwmorg/fvwm3/pull/288) ([djwf](https://github.com/djwf))
- desk\_get\_fw\_count: remove debug [\#278](https://github.com/fvwmorg/fvwm3/pull/278) ([ThomasAdam](https://github.com/ThomasAdam))
- desk\_add: remove debug [\#276](https://github.com/fvwmorg/fvwm3/pull/276) ([ThomasAdam](https://github.com/ThomasAdam))
- Asterisk: expand variables in config lines [\#268](https://github.com/fvwmorg/fvwm3/pull/268) ([ThomasAdam](https://github.com/ThomasAdam))
- Division by zero in FvwmPager when desk\_h==0 or desk\_w==0 [\#261](https://github.com/fvwmorg/fvwm3/pull/261) ([schaecsn](https://github.com/schaecsn))
- update Changelog [\#259](https://github.com/fvwmorg/fvwm3/pull/259) ([ThomasAdam](https://github.com/ThomasAdam))
- Release/1.0.1 [\#245](https://github.com/fvwmorg/fvwm3/pull/245) ([ThomasAdam](https://github.com/ThomasAdam))
- Release 1.0.2 [\#367](https://github.com/fvwmorg/fvwm3/pull/367) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/distfix [\#366](https://github.com/fvwmorg/fvwm3/pull/366) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmMFL: make pid file slight more unique [\#365](https://github.com/fvwmorg/fvwm3/pull/365) ([ThomasAdam](https://github.com/ThomasAdam))
- EdgeCommands: tweak map logic [\#364](https://github.com/fvwmorg/fvwm3/pull/364) ([ThomasAdam](https://github.com/ThomasAdam))
- Edgecommands: silence warnings [\#363](https://github.com/fvwmorg/fvwm3/pull/363) ([ThomasAdam](https://github.com/ThomasAdam))
- PaneFrames: disallow Edge/Leave without direction [\#362](https://github.com/fvwmorg/fvwm3/pull/362) ([ThomasAdam](https://github.com/ThomasAdam))
- \_\_execute\_function: fix compiler warning [\#361](https://github.com/fvwmorg/fvwm3/pull/361) ([ThomasAdam](https://github.com/ThomasAdam))
- EdgeCommand: fix parsing when unsetting commands [\#360](https://github.com/fvwmorg/fvwm3/pull/360) ([ThomasAdam](https://github.com/ThomasAdam))
- repeat: don't free string [\#359](https://github.com/fvwmorg/fvwm3/pull/359) ([ThomasAdam](https://github.com/ThomasAdam))
- panframes: recheck for all monitors [\#358](https://github.com/fvwmorg/fvwm3/pull/358) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmScript: fix bogus string length [\#357](https://github.com/fvwmorg/fvwm3/pull/357) ([ThomasAdam](https://github.com/ThomasAdam))
- Startup: reinstate session functions [\#355](https://github.com/fvwmorg/fvwm3/pull/355) ([ThomasAdam](https://github.com/ThomasAdam))
- config parsing: be more tolerant when finding configs [\#353](https://github.com/fvwmorg/fvwm3/pull/353) ([ThomasAdam](https://github.com/ThomasAdam))
- \_NET\_WM\_STATE: handle HORIZ/VERT consistently [\#352](https://github.com/fvwmorg/fvwm3/pull/352) ([ThomasAdam](https://github.com/ThomasAdam))
- dev-doc: slight improvements [\#351](https://github.com/fvwmorg/fvwm3/pull/351) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmMFL: only allow one instance to run [\#349](https://github.com/fvwmorg/fvwm3/pull/349) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmRearrange: continue on unknown packet [\#347](https://github.com/fvwmorg/fvwm3/pull/347) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmConsole: add missing freetype libs/cflags [\#340](https://github.com/fvwmorg/fvwm3/pull/340) ([ThomasAdam](https://github.com/ThomasAdam))
- status: track sticky windows to current desk [\#332](https://github.com/fvwmorg/fvwm3/pull/332) ([ThomasAdam](https://github.com/ThomasAdam))
- CI: add issues script [\#327](https://github.com/fvwmorg/fvwm3/pull/327) ([ThomasAdam](https://github.com/ThomasAdam))
- freetype: don't clober CFLAGS/LDFLAGS [\#324](https://github.com/fvwmorg/fvwm3/pull/324) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmPrompt: add hint about starting FvwmMFL [\#323](https://github.com/fvwmorg/fvwm3/pull/323) ([ThomasAdam](https://github.com/ThomasAdam))
- modules: remove templated man pages [\#322](https://github.com/fvwmorg/fvwm3/pull/322) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmButtons: comply better with the GPL [\#321](https://github.com/fvwmorg/fvwm3/pull/321) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmEvent: comply better with the GPL [\#320](https://github.com/fvwmorg/fvwm3/pull/320) ([ThomasAdam](https://github.com/ThomasAdam))
- ewmh: compute workarea against all monitors [\#319](https://github.com/fvwmorg/fvwm3/pull/319) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmEvent: remove support for Rplay [\#317](https://github.com/fvwmorg/fvwm3/pull/317) ([ThomasAdam](https://github.com/ThomasAdam))
- CI: WIP CHANGELOG [\#315](https://github.com/fvwmorg/fvwm3/pull/315) ([ThomasAdam](https://github.com/ThomasAdam))
- FreeBSD: include fvwm\_x11.h for modifiers [\#307](https://github.com/fvwmorg/fvwm3/pull/307) ([ThomasAdam](https://github.com/ThomasAdam))
- Translation cleanup [\#305](https://github.com/fvwmorg/fvwm3/pull/305) ([lgsobalvarro](https://github.com/lgsobalvarro))
- CI: Tweak CHANGELOG generator [\#303](https://github.com/fvwmorg/fvwm3/pull/303) ([ThomasAdam](https://github.com/ThomasAdam))
- HandlePaging: ignore bounds check [\#298](https://github.com/fvwmorg/fvwm3/pull/298) ([ThomasAdam](https://github.com/ThomasAdam))
- PanFrames: per-monitor support [\#291](https://github.com/fvwmorg/fvwm3/pull/291) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmForm: remove useless setitimer call [\#284](https://github.com/fvwmorg/fvwm3/pull/284) ([phileimer](https://github.com/phileimer))
- Event: Echo [\#280](https://github.com/fvwmorg/fvwm3/pull/280) ([ThomasAdam](https://github.com/ThomasAdam))
- Remove SAFEFREE macro [\#277](https://github.com/fvwmorg/fvwm3/pull/277) ([tekknolagi](https://github.com/tekknolagi))
- Status: update for PropertyNotify events [\#275](https://github.com/fvwmorg/fvwm3/pull/275) ([ThomasAdam](https://github.com/ThomasAdam))
- ParseGeometry: handle meta-references to screens [\#270](https://github.com/fvwmorg/fvwm3/pull/270) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix module synchronization in goto\_desk [\#263](https://github.com/fvwmorg/fvwm3/pull/263) ([phintsan](https://github.com/phintsan))
- status: fix bson\_t detection [\#258](https://github.com/fvwmorg/fvwm3/pull/258) ([ThomasAdam](https://github.com/ThomasAdam))
- Expansion: add $\[w.pagex\] $\[w.pagey\] [\#256](https://github.com/fvwmorg/fvwm3/pull/256) ([ThomasAdam](https://github.com/ThomasAdam))
- New command:  Status [\#254](https://github.com/fvwmorg/fvwm3/pull/254) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix Maximize on monitor 2 [\#251](https://github.com/fvwmorg/fvwm3/pull/251) ([phileimer](https://github.com/phileimer))
- Revise doc/README - docs not built by default [\#247](https://github.com/fvwmorg/fvwm3/pull/247) ([djwf](https://github.com/djwf))

## [1.0.1](https://github.com/fvwmorg/fvwm3/tree/1.0.1) (2020-10-04)

[Full Changelog](https://github.com/fvwmorg/fvwm3/compare/1.0.0...1.0.1)

**Implemented enhancements:**

- fvwm3 man and default paths to config files? [\#206](https://github.com/fvwmorg/fvwm3/issues/206)

**Fixed bugs:**

- compilation fails on openbsd-current due to safemalloc.h \(va\_list\) [\#231](https://github.com/fvwmorg/fvwm3/issues/231)
- \_NET\_WM\_STATE was not updated for maximized windows [\#203](https://github.com/fvwmorg/fvwm3/issues/203)
- EwmhBaseStruts calculations don't use monitor's [\#241](https://github.com/fvwmorg/fvwm3/issues/241)
- DesktopConfiguration global inherits behaviour from per-monitor mode [\#236](https://github.com/fvwmorg/fvwm3/issues/236)
- FvwmEvent:  missing `monitor\_focus` event [\#228](https://github.com/fvwmorg/fvwm3/issues/228)
- perllib: doesn't understand MX\_MONITOR\_\* events [\#226](https://github.com/fvwmorg/fvwm3/issues/226)
- FvwmButtons subpanels not popped out on primary monitor when desk is \> 0 [\#224](https://github.com/fvwmorg/fvwm3/issues/224)
- PositionPlacement Center: fix to use current screen [\#211](https://github.com/fvwmorg/fvwm3/issues/211)
- EwmhBaseStruts missing screen info from manpage [\#208](https://github.com/fvwmorg/fvwm3/issues/208)
- "version of go" misinterpreted by configure script? [\#202](https://github.com/fvwmorg/fvwm3/issues/202)
- Unable to build 1.0, bson.h not found \[FreeBSD 12.1\] [\#200](https://github.com/fvwmorg/fvwm3/issues/200)
- EwmhBaseStrut: fix calculations for per-monitor [\#242](https://github.com/fvwmorg/fvwm3/pull/242) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix window locations in Global mode [\#237](https://github.com/fvwmorg/fvwm3/pull/237) ([ThomasAdam](https://github.com/ThomasAdam))

**Closed issues:**

- FvwmPager: show an icon shadow after move window to another screen [\#216](https://github.com/fvwmorg/fvwm3/issues/216)
- FvwmIconMan: width of the FvwmIconMan & FvwmPager [\#215](https://github.com/fvwmorg/fvwm3/issues/215)

**Merged pull requests:**

- Added CHANGELOG.md [\#244](https://github.com/fvwmorg/fvwm3/pull/244) ([ThomasAdam](https://github.com/ThomasAdam))
- EWMH area: don't crop the boundary [\#243](https://github.com/fvwmorg/fvwm3/pull/243) ([ThomasAdam](https://github.com/ThomasAdam))
- Add support for infostore in EnvIsSet Test case [\#240](https://github.com/fvwmorg/fvwm3/pull/240) ([ThomasAdam](https://github.com/ThomasAdam))
- Add variable/parameter which indicates the state of the FVWM3 logging [\#239](https://github.com/fvwmorg/fvwm3/pull/239) ([NsCDE](https://github.com/NsCDE))
- safemalloc: add stddef.h [\#235](https://github.com/fvwmorg/fvwm3/pull/235) ([ThomasAdam](https://github.com/ThomasAdam))
- OpenBSD: add missing stdarg.h include [\#232](https://github.com/fvwmorg/fvwm3/pull/232) ([ThomasAdam](https://github.com/ThomasAdam))
- sticky windows: explicitly move to desk [\#230](https://github.com/fvwmorg/fvwm3/pull/230) ([ThomasAdam](https://github.com/ThomasAdam))
- Ta/monitor focus [\#229](https://github.com/fvwmorg/fvwm3/pull/229) ([ThomasAdam](https://github.com/ThomasAdam))
- Support for setting default mouse cursor on all FvwmScript widgets [\#222](https://github.com/fvwmorg/fvwm3/pull/222) ([NsCDE](https://github.com/NsCDE))
- Add support for triangle indicator in/out sub options [\#221](https://github.com/fvwmorg/fvwm3/pull/221) ([NsCDE](https://github.com/NsCDE))
- Add WindowName option to FvwmButtons [\#219](https://github.com/fvwmorg/fvwm3/pull/219) ([NsCDE](https://github.com/NsCDE))
- FvwmMFL: remove socket before opening [\#218](https://github.com/fvwmorg/fvwm3/pull/218) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/gh 214 [\#217](https://github.com/fvwmorg/fvwm3/pull/217) ([ThomasAdam](https://github.com/ThomasAdam))
- README: update for 1.0.0 [\#213](https://github.com/fvwmorg/fvwm3/pull/213) ([ThomasAdam](https://github.com/ThomasAdam))
- PositionPlacement: include screen for Center [\#212](https://github.com/fvwmorg/fvwm3/pull/212) ([ThomasAdam](https://github.com/ThomasAdam))
- configure: default CFLAGS, add no-security guard [\#210](https://github.com/fvwmorg/fvwm3/pull/210) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmMFL: libbson: guard for FreeBSD [\#207](https://github.com/fvwmorg/fvwm3/pull/207) ([ThomasAdam](https://github.com/ThomasAdam))
- configure.ac: fix golang binary check [\#205](https://github.com/fvwmorg/fvwm3/pull/205) ([ThomasAdam](https://github.com/ThomasAdam))
- Fixed \_NET\_WM\_STATE for maximized windows [\#204](https://github.com/fvwmorg/fvwm3/pull/204) ([xuzhen](https://github.com/xuzhen))
- Ta/release 1.0.0 [\#199](https://github.com/fvwmorg/fvwm3/pull/199) ([ThomasAdam](https://github.com/ThomasAdam))
- perllib: update to include MX\_MONITOR\_\* events [\#227](https://github.com/fvwmorg/fvwm3/pull/227) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmMFL: honour TMPDIR for socket [\#220](https://github.com/fvwmorg/fvwm3/pull/220) ([ThomasAdam](https://github.com/ThomasAdam))
- doc: EwmhBaseStruts mention screen attribute [\#209](https://github.com/fvwmorg/fvwm3/pull/209) ([ThomasAdam](https://github.com/ThomasAdam))

## [1.0.0](https://github.com/fvwmorg/fvwm3/tree/1.0.0) (2020-09-03)

[Full Changelog](https://github.com/fvwmorg/fvwm3/compare/1.0.0-rc0...1.0.0)

**Fixed bugs:**

- New versioning scheme of FVWM3 RC0 break Version test condition. [\#195](https://github.com/fvwmorg/fvwm3/issues/195)

**Closed issues:**

- dynamic randr dpi configuration causes miss-configured screen dimensions  [\#52](https://github.com/fvwmorg/fvwm3/issues/52)

**Merged pull requests:**

- Update INSTALL.md [\#196](https://github.com/fvwmorg/fvwm3/pull/196) ([ThomasAdam](https://github.com/ThomasAdam))

## [1.0.0-rc0](https://github.com/fvwmorg/fvwm3/tree/1.0.0-rc0) (2020-08-31)

[Full Changelog](https://github.com/fvwmorg/fvwm3/compare/289c0e27f2438c43e66b980641561062659bd14b...1.0.0-rc0)

**Implemented enhancements:**

- Function to ignore screen boundaries in multi-monitor setups \(when maximizing/full-screening\) [\#186](https://github.com/fvwmorg/fvwm3/issues/186)
- Add a dmenu/rofi keybinding for default config [\#112](https://github.com/fvwmorg/fvwm3/issues/112)
- Support lists of fonts \(for falling back on\) [\#37](https://github.com/fvwmorg/fvwm3/issues/37)
- conky can make fvwm3 go sloppy [\#32](https://github.com/fvwmorg/fvwm3/issues/32)
- msgpack as fvwm \<-\> modules \<-\> bindings communicator [\#31](https://github.com/fvwmorg/fvwm3/issues/31)
- Proposal: FvwmEvent new events in FVWM3 [\#26](https://github.com/fvwmorg/fvwm3/issues/26)
- Segmentation fault while turning off display port cable and mouse pointer is positioned on the monitor which is going off [\#15](https://github.com/fvwmorg/fvwm3/issues/15)
- Compiler warnings in ta/desktops  [\#13](https://github.com/fvwmorg/fvwm3/issues/13)
- No .desktop file generated from make install [\#12](https://github.com/fvwmorg/fvwm3/issues/12)
- making menuitem text always vertically centered. [\#181](https://github.com/fvwmorg/fvwm3/pull/181) ([mikeandmore](https://github.com/mikeandmore))
- Add icons to the WindowOpsLong menus for default-config. [\#141](https://github.com/fvwmorg/fvwm3/pull/141) ([somiaj](https://github.com/somiaj))
- FvwmPager: per-monitor improvements [\#123](https://github.com/fvwmorg/fvwm3/pull/123) ([ThomasAdam](https://github.com/ThomasAdam))
- key binding and menu option for dmenu\_run [\#113](https://github.com/fvwmorg/fvwm3/pull/113) ([lgsobalvarro](https://github.com/lgsobalvarro))
- FvwmEvent: listen for RandR events [\#106](https://github.com/fvwmorg/fvwm3/pull/106) ([ThomasAdam](https://github.com/ThomasAdam))
- expansion: add $\[monitor.X\] namespace [\#74](https://github.com/fvwmorg/fvwm3/pull/74) ([ThomasAdam](https://github.com/ThomasAdam))

**Fixed bugs:**

- no check for libxt-dev when fribidi is enabled [\#191](https://github.com/fvwmorg/fvwm3/issues/191)
- fvwm-menu-desktop only produces half the xdg-menu [\#177](https://github.com/fvwmorg/fvwm3/issues/177)
- ModuleMFL doesn't appear to open socket [\#172](https://github.com/fvwmorg/fvwm3/issues/172)
- Typo in configure script line 535, confusing libbson error message  [\#162](https://github.com/fvwmorg/fvwm3/issues/162)
- EdgeScroll not working properly when values change via FvwmConsole [\#144](https://github.com/fvwmorg/fvwm3/issues/144)
- FvwmIconMan won't correctly apply colorsets when swallowed [\#135](https://github.com/fvwmorg/fvwm3/issues/135)
- Steam crashes on FVWM3 [\#124](https://github.com/fvwmorg/fvwm3/issues/124)
- multiple definition error when using gcc 10 [\#119](https://github.com/fvwmorg/fvwm3/issues/119)
- More PositionPlacement weirdness [\#115](https://github.com/fvwmorg/fvwm3/issues/115)
- Reproducible Builds: remove \_\_DATE\_\_ and \_\_TIME\_\_ [\#99](https://github.com/fvwmorg/fvwm3/issues/99)
- Transient windows sometimes switch desks [\#95](https://github.com/fvwmorg/fvwm3/issues/95)
- FindScreenOfXY: couldn't find screen at 555 x 134 returning first monitor.  This is a bug. [\#93](https://github.com/fvwmorg/fvwm3/issues/93)
- RaiseLower only Lowers windows in per-desktop mode in certain conditions [\#86](https://github.com/fvwmorg/fvwm3/issues/86)
- Windows open outside of screen [\#85](https://github.com/fvwmorg/fvwm3/issues/85)
- Wrong maximizing with EwmBaseStruts [\#84](https://github.com/fvwmorg/fvwm3/issues/84)
- No default panel with latest Master.  Dual Monitor of different size. [\#78](https://github.com/fvwmorg/fvwm3/issues/78)
- Unmaximizing windows can sometimes vanish [\#68](https://github.com/fvwmorg/fvwm3/issues/68)
- "ThisWindow \(Screen XY\) Sticky" broken? in DesktopConfiguration global [\#64](https://github.com/fvwmorg/fvwm3/issues/64)
- Fix snap attraction [\#61](https://github.com/fvwmorg/fvwm3/issues/61)
- FvwmButtons fails silently; Fvwm3 [\#60](https://github.com/fvwmorg/fvwm3/issues/60)
- FvwmPager segfaults on fvwm3 ta/gh-22 [\#44](https://github.com/fvwmorg/fvwm3/issues/44)
- Do we need to check the value returned from FCreateFImage? [\#42](https://github.com/fvwmorg/fvwm3/issues/42)
- StartsOnPage/StartsOnDesk ignored [\#39](https://github.com/fvwmorg/fvwm3/issues/39)
- FvwmButtons on FVWM3 [\#28](https://github.com/fvwmorg/fvwm3/issues/28)
- In global DesktopConfiguration mode, Wait XTerm fails after changing current desk from 0 0 to 0 1 [\#24](https://github.com/fvwmorg/fvwm3/issues/24)
- Page navigation and selection is incorrect after FVWM3 restart/start while two screens are enabled [\#23](https://github.com/fvwmorg/fvwm3/issues/23)
- FvwmPager is broken with RandR [\#22](https://github.com/fvwmorg/fvwm3/issues/22)
- Position of windows on screens, desks and pages is not accurate after FVWM 3 Restart [\#20](https://github.com/fvwmorg/fvwm3/issues/20)
- DesktopConfiguration per-monitor segmentation fault in certain repeatable conditions [\#19](https://github.com/fvwmorg/fvwm3/issues/19)
- Multiple Pages \(3x3\) and RandR is confusing and broken [\#17](https://github.com/fvwmorg/fvwm3/issues/17)
- X windows started on newly defined monitor doesn't accept focus [\#16](https://github.com/fvwmorg/fvwm3/issues/16)
- Logs of starting - closing fvwm3 with DesktopConfiguration set [\#14](https://github.com/fvwmorg/fvwm3/issues/14)
- if monitor name happens to get updated in ParseOptions, the rest of FvwmPager config is skipped [\#146](https://github.com/fvwmorg/fvwm3/pull/146) ([d-e-e-p](https://github.com/d-e-e-p))
- monitor: track focus event separately [\#140](https://github.com/fvwmorg/fvwm3/pull/140) ([ThomasAdam](https://github.com/ThomasAdam))
- Fixes issue with FvwmIconMan and Colorsets. [\#136](https://github.com/fvwmorg/fvwm3/pull/136) ([ThomasAdam](https://github.com/ThomasAdam))
- session: fix version check for used\_sm [\#105](https://github.com/fvwmorg/fvwm3/pull/105) ([ThomasAdam](https://github.com/ThomasAdam))
- expand: portably tokenise string using strsep [\#102](https://github.com/fvwmorg/fvwm3/pull/102) ([ThomasAdam](https://github.com/ThomasAdam))
- EWMH: AreaIntersection: fix basestrut calculation [\#94](https://github.com/fvwmorg/fvwm3/pull/94) ([ThomasAdam](https://github.com/ThomasAdam))
- configure: resurrect VERSIONINFO [\#92](https://github.com/fvwmorg/fvwm3/pull/92) ([ThomasAdam](https://github.com/ThomasAdam))
- UPDATE\_FVWM\_SCREEN: respect StartsOnDesk style [\#91](https://github.com/fvwmorg/fvwm3/pull/91) ([ThomasAdam](https://github.com/ThomasAdam))
- configure.ac: assorted fixes [\#88](https://github.com/fvwmorg/fvwm3/pull/88) ([ThomasAdam](https://github.com/ThomasAdam))
- unmaximize: use window's current screen for positioning [\#69](https://github.com/fvwmorg/fvwm3/pull/69) ([ThomasAdam](https://github.com/ThomasAdam))
- SnapAttraction: fix coord detection [\#62](https://github.com/fvwmorg/fvwm3/pull/62) ([ThomasAdam](https://github.com/ThomasAdam))
- fix broken positions when drawing 3d borders [\#48](https://github.com/fvwmorg/fvwm3/pull/48) ([mikeandmore](https://github.com/mikeandmore))
- Do we need to check the value returned from FCreateFImage? [\#43](https://github.com/fvwmorg/fvwm3/pull/43) ([klebertarcisio](https://github.com/klebertarcisio))

**Closed issues:**

- FScreenGetScrRect function [\#163](https://github.com/fvwmorg/fvwm3/issues/163)
- Core dump accessing some $\[monitor\] variables [\#101](https://github.com/fvwmorg/fvwm3/issues/101)
- Capture: force NormalState despite current desk [\#97](https://github.com/fvwmorg/fvwm3/issues/97)
- MoveToPage not working right [\#83](https://github.com/fvwmorg/fvwm3/issues/83)
- Better logging required [\#77](https://github.com/fvwmorg/fvwm3/issues/77)
- FVWM3 on Kubuntu: unknown type name ‘RROutput’ [\#76](https://github.com/fvwmorg/fvwm3/issues/76)
- Remove win\_count functionality [\#70](https://github.com/fvwmorg/fvwm3/issues/70)
- Pager problems in gh-28 [\#56](https://github.com/fvwmorg/fvwm3/issues/56)
- Segmentation fault while using StartsOnScreen and/or StartsOnPage [\#51](https://github.com/fvwmorg/fvwm3/issues/51)
- UI freeze [\#50](https://github.com/fvwmorg/fvwm3/issues/50)
- FvwmEvent does not contain the event stick and destick [\#47](https://github.com/fvwmorg/fvwm3/issues/47)
- The restart process does not restore custom window colorsets [\#46](https://github.com/fvwmorg/fvwm3/issues/46)
- DesktopSize 1x1 is not respected [\#45](https://github.com/fvwmorg/fvwm3/issues/45)
- FvwmPager divide by zero on startup - never appears [\#38](https://github.com/fvwmorg/fvwm3/issues/38)
- test [\#29](https://github.com/fvwmorg/fvwm3/issues/29)
- Theme support that integrates with Gnome, KDE and GTK [\#27](https://github.com/fvwmorg/fvwm3/issues/27)
- fvwm-menu-desktop is wrong when converting multiple image files. [\#9](https://github.com/fvwmorg/fvwm3/issues/9)
- fvwm3 test result [\#8](https://github.com/fvwmorg/fvwm3/issues/8)
- Zero-size malloc on ta/randr branch [\#5](https://github.com/fvwmorg/fvwm3/issues/5)
- feature request: global menu support [\#4](https://github.com/fvwmorg/fvwm3/issues/4)
- Add support for the XDG Base Directory Specification [\#3](https://github.com/fvwmorg/fvwm3/issues/3)

**Merged pull requests:**

- Ta/gh 143 [\#193](https://github.com/fvwmorg/fvwm3/pull/193) ([ThomasAdam](https://github.com/ThomasAdam))
- configure.ac: check for xt [\#192](https://github.com/fvwmorg/fvwm3/pull/192) ([ThomasAdam](https://github.com/ThomasAdam))
- configure.ac: look for golang [\#190](https://github.com/fvwmorg/fvwm3/pull/190) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/remove fvwm menu headlines [\#188](https://github.com/fvwmorg/fvwm3/pull/188) ([ThomasAdam](https://github.com/ThomasAdam))
- ta/remove fvwm bug [\#187](https://github.com/fvwmorg/fvwm3/pull/187) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmMFL: add connection\_profile [\#185](https://github.com/fvwmorg/fvwm3/pull/185) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmForm: change Timeout resolution to 100ms, instead of 1s [\#184](https://github.com/fvwmorg/fvwm3/pull/184) ([phileimer](https://github.com/phileimer))
- FvwmScript Comments Translation [\#183](https://github.com/fvwmorg/fvwm3/pull/183) ([phileimer](https://github.com/phileimer))
- FvwmForm: resurrect from retirement [\#182](https://github.com/fvwmorg/fvwm3/pull/182) ([ThomasAdam](https://github.com/ThomasAdam))
- catch when \_do\_check\(\) fails [\#180](https://github.com/fvwmorg/fvwm3/pull/180) ([mikeandmore](https://github.com/mikeandmore))
- Forgot to catch the conversion error exception [\#179](https://github.com/fvwmorg/fvwm3/pull/179) ([mikeandmore](https://github.com/mikeandmore))
- fix crash in the menu script; escape menuitem text [\#178](https://github.com/fvwmorg/fvwm3/pull/178) ([mikeandmore](https://github.com/mikeandmore))
- FvwmMFL: add newline to end out write buffer [\#175](https://github.com/fvwmorg/fvwm3/pull/175) ([ThomasAdam](https://github.com/ThomasAdam))
- libstroke: fix botched bindings [\#174](https://github.com/fvwmorg/fvwm3/pull/174) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmMFL: start by default [\#173](https://github.com/fvwmorg/fvwm3/pull/173) ([ThomasAdam](https://github.com/ThomasAdam))
- fix typo in error message on libbson not found [\#171](https://github.com/fvwmorg/fvwm3/pull/171) ([ThomasAdam](https://github.com/ThomasAdam))
- Ta/deep docs [\#170](https://github.com/fvwmorg/fvwm3/pull/170) ([ThomasAdam](https://github.com/ThomasAdam))
- associate wmclass/wmname and the miniicon using desktop entries [\#169](https://github.com/fvwmorg/fvwm3/pull/169) ([mikeandmore](https://github.com/mikeandmore))
- INSTALL: add version to libbson [\#168](https://github.com/fvwmorg/fvwm3/pull/168) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix compiler warnings [\#167](https://github.com/fvwmorg/fvwm3/pull/167) ([ThomasAdam](https://github.com/ThomasAdam))
- Remove support for libstroke [\#166](https://github.com/fvwmorg/fvwm3/pull/166) ([ThomasAdam](https://github.com/ThomasAdam))
- Additional FVWM3 references [\#159](https://github.com/fvwmorg/fvwm3/pull/159) ([ThomasAdam](https://github.com/ThomasAdam))
- Update DEVELOPERS.md [\#158](https://github.com/fvwmorg/fvwm3/pull/158) ([ThomasAdam](https://github.com/ThomasAdam))
- Replace calloc by fxcalloc [\#156](https://github.com/fvwmorg/fvwm3/pull/156) ([klebertarcisio](https://github.com/klebertarcisio))
- screen\_info\_new: use fxcalloc [\#154](https://github.com/fvwmorg/fvwm3/pull/154) ([ThomasAdam](https://github.com/ThomasAdam))
- FvwmMFL: Fvwm Module Front Loader [\#153](https://github.com/fvwmorg/fvwm3/pull/153) ([ThomasAdam](https://github.com/ThomasAdam))
- CI: switch to using image on Docker hub [\#150](https://github.com/fvwmorg/fvwm3/pull/150) ([ThomasAdam](https://github.com/ThomasAdam))
- Add a Codacy badge to README.md [\#149](https://github.com/fvwmorg/fvwm3/pull/149) ([codacy-badger](https://github.com/codacy-badger))
- Github shields: switch to Actions [\#148](https://github.com/fvwmorg/fvwm3/pull/148) ([ThomasAdam](https://github.com/ThomasAdam))
- Ta/add docker [\#147](https://github.com/fvwmorg/fvwm3/pull/147) ([ThomasAdam](https://github.com/ThomasAdam))
- Colorset variable expansion features. [\#139](https://github.com/fvwmorg/fvwm3/pull/139) ([somiaj](https://github.com/somiaj))
- Update to config [\#137](https://github.com/fvwmorg/fvwm3/pull/137) ([lgsobalvarro](https://github.com/lgsobalvarro))
- New colorset for cfg [\#134](https://github.com/fvwmorg/fvwm3/pull/134) ([lgsobalvarro](https://github.com/lgsobalvarro))
- better checks for icon size [\#132](https://github.com/fvwmorg/fvwm3/pull/132) ([mikeandmore](https://github.com/mikeandmore))
- ta/randr by default [\#131](https://github.com/fvwmorg/fvwm3/pull/131) ([ThomasAdam](https://github.com/ThomasAdam))
- FindScreenOfXY: remove debug if no monitor found [\#128](https://github.com/fvwmorg/fvwm3/pull/128) ([ThomasAdam](https://github.com/ThomasAdam))
- Add FVWM3\_LOGDIR envvar for logging to different file [\#127](https://github.com/fvwmorg/fvwm3/pull/127) ([ThomasAdam](https://github.com/ThomasAdam))
- GCC-10: default to -fno-common by default [\#122](https://github.com/fvwmorg/fvwm3/pull/122) ([ThomasAdam](https://github.com/ThomasAdam))
- GCC-10: enable -fcommon for linking [\#121](https://github.com/fvwmorg/fvwm3/pull/121) ([ThomasAdam](https://github.com/ThomasAdam))
- setup\_window\_placement: initialise screen correctly [\#120](https://github.com/fvwmorg/fvwm3/pull/120) ([ThomasAdam](https://github.com/ThomasAdam))
- issue\_bot: add YAML config file [\#118](https://github.com/fvwmorg/fvwm3/pull/118) ([ThomasAdam](https://github.com/ThomasAdam))
- restart: LoadwindowStates: fix NULL dereference [\#117](https://github.com/fvwmorg/fvwm3/pull/117) ([ThomasAdam](https://github.com/ThomasAdam))
- Rename log filfe [\#116](https://github.com/fvwmorg/fvwm3/pull/116) ([ThomasAdam](https://github.com/ThomasAdam))
- verbose: actually open log file [\#114](https://github.com/fvwmorg/fvwm3/pull/114) ([ThomasAdam](https://github.com/ThomasAdam))
- Fix 'dist' target [\#111](https://github.com/fvwmorg/fvwm3/pull/111) ([v1cont](https://github.com/v1cont))
- Windows cannot be moved to desktop/workspace 0 [\#110](https://github.com/fvwmorg/fvwm3/pull/110) ([v1cont](https://github.com/v1cont))
- logging: don't send fvwm3's usage output to log file [\#103](https://github.com/fvwmorg/fvwm3/pull/103) ([ThomasAdam](https://github.com/ThomasAdam))
- Reproducable builds: remove \_\_DATE\_\_/\_\_TIME\_\_ [\#100](https://github.com/fvwmorg/fvwm3/pull/100) ([ThomasAdam](https://github.com/ThomasAdam))
- Capture: force NormalState despite current desk [\#98](https://github.com/fvwmorg/fvwm3/pull/98) ([ThomasAdam](https://github.com/ThomasAdam))
- place\_window: don't switch desk for transient windows [\#96](https://github.com/fvwmorg/fvwm3/pull/96) ([ThomasAdam](https://github.com/ThomasAdam))
- remove dependency on Perl4::CoreLibs::getcwd \(fvwm3\) [\#90](https://github.com/fvwmorg/fvwm3/pull/90) ([slazav](https://github.com/slazav))
- fvwm-version-str: fix release version [\#87](https://github.com/fvwmorg/fvwm3/pull/87) ([ThomasAdam](https://github.com/ThomasAdam))
- randr: assign one output as primary [\#81](https://github.com/fvwmorg/fvwm3/pull/81) ([ThomasAdam](https://github.com/ThomasAdam))
- GCC: fix warnings [\#80](https://github.com/fvwmorg/fvwm3/pull/80) ([ThomasAdam](https://github.com/ThomasAdam))
- logging: add fvwm\_debug infrastructure [\#79](https://github.com/fvwmorg/fvwm3/pull/79) ([ThomasAdam](https://github.com/ThomasAdam))
- BroadcastMonitorList: reorder packet logic [\#75](https://github.com/fvwmorg/fvwm3/pull/75) ([ThomasAdam](https://github.com/ThomasAdam))
- UPDATE\_FVWM\_SCREEN: remove win\_count functionality [\#72](https://github.com/fvwmorg/fvwm3/pull/72) ([ThomasAdam](https://github.com/ThomasAdam))
- gh workflows: remove sending PR messages [\#71](https://github.com/fvwmorg/fvwm3/pull/71) ([ThomasAdam](https://github.com/ThomasAdam))
- Per-monitor EWMHBaseStruts [\#67](https://github.com/fvwmorg/fvwm3/pull/67) ([ThomasAdam](https://github.com/ThomasAdam))
- Create github action script [\#63](https://github.com/fvwmorg/fvwm3/pull/63) ([ThomasAdam](https://github.com/ThomasAdam))
- MapWindow: honour iconification state [\#58](https://github.com/fvwmorg/fvwm3/pull/58) ([ThomasAdam](https://github.com/ThomasAdam))
- Document $\[monitor.page\] [\#57](https://github.com/fvwmorg/fvwm3/pull/57) ([ThomasAdam](https://github.com/ThomasAdam))
- Ta/gh 28 [\#55](https://github.com/fvwmorg/fvwm3/pull/55) ([ThomasAdam](https://github.com/ThomasAdam))
- WorkArea: use screen dimensions to compute area [\#54](https://github.com/fvwmorg/fvwm3/pull/54) ([ThomasAdam](https://github.com/ThomasAdam))
- FParseGeoemtry: fix negative offsets [\#53](https://github.com/fvwmorg/fvwm3/pull/53) ([ThomasAdam](https://github.com/ThomasAdam))
- should not compare menu positions with screen width/height. [\#36](https://github.com/fvwmorg/fvwm3/pull/36) ([mikeandmore](https://github.com/mikeandmore))
- Ta/shields [\#35](https://github.com/fvwmorg/fvwm3/pull/35) ([ThomasAdam](https://github.com/ThomasAdam))
- fix minor typos [\#33](https://github.com/fvwmorg/fvwm3/pull/33) ([topcat001](https://github.com/topcat001))
- editorconfig: add default options file [\#30](https://github.com/fvwmorg/fvwm3/pull/30) ([ThomasAdam](https://github.com/ThomasAdam))
- Fixed a typo [\#21](https://github.com/fvwmorg/fvwm3/pull/21) ([zielaj](https://github.com/zielaj))
- Fix converting of multi-images icon files. [\#11](https://github.com/fvwmorg/fvwm3/pull/11) ([domichel](https://github.com/domichel))
- Use the correct travis-ci project status on readme [\#7](https://github.com/fvwmorg/fvwm3/pull/7) ([Hattshire](https://github.com/Hattshire))
- Fix uninitialized variable in FvwmIconMan colorset loop. [\#6](https://github.com/fvwmorg/fvwm3/pull/6) ([cyberbisson](https://github.com/cyberbisson))



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
