# **PojavLauncher "Dahlia" GPlay update**
- #### App now requires a premium account, otherwise installation of the game assets are denied from the launcher itself.
- #### Most languages have been added
- #### VGPU and all variants of GL4ES 1.1.5 have been removed from the launcher.
- #### GL4ES 1.1.4 was replaced with a custom fork, adding many features and bug fixes to it, such as
- #### random crashes on pre-1.13 versions without VBO enabled
- #### failure to load shaders used by Minecraft 1.17+ and some server custom resourcepacks
- #### Controls have been reworked and improved and extended, gamepad latency is frame perfect.
- #### Color selector for controls has been changed
- #### Profiles are added! Now you can keep multiple setups of the game with different selected renderers, JVMs, and game directories.
- #### Java 17 is now integrated into the launcher for running 1.17+
- #### New settings were added:
- #### "Use alternate surface rendering", which uses a different kind of rendering surface to render the game faster on some devices.
- #### "Start with virtual mouse on", which makes the game start with mouse already enabled
- #### "Enable sustained performance mode", which limits CPU/GPU usage to prevent overheating and thermal throttling
- #### Added Arc Capes support (now changed to cosmetica.gg)
- #### Fixes:
- #### Fixed a crash occurring while starting a screen recorder
- #### Fixed a NullPointerException crash when launching versions below 1.6.4
- #### In versions above 1.13, game was crashing while scrolling, that was fixed.
- #### 1.13/1.14 no longer crashes upon the first touch
- #### Fix older versions not being fullscreen at launch
- #### Fix older versions having a "halved light" on entities
- #### Fixed hotbar not registering 0-9 inputs.
- #### No more errors about a null array when loading a custom control on android 10+
- #### Now the game will resize in splitscreen/freeform mode, although not officially supported
## What's Changed
- #### Dl everything by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/1966
- #### [V2.4] Controls revision by @Mathias-Boulay in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2006
- #### Add gradlew.bat by @NekoIceCream in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2073
- #### Update README.md by @rscDMTalt in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2052
- #### [V2.5] Controls Revision by @Mathias-Boulay in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2211
- #### Small cleanup of the code structure by @Mathias-Boulay in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2267
- #### ExtraCore can now deal all kinds of values by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2315
- #### check for null value insert by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2350
- #### Upstreamify profiles by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2390
- #### Upstreamify profiles by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2472
- #### Upstreamify profiles by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2765
- #### The great refactor by @Mathias-Boulay in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2811
- #### Merge and resolve conflicts by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2917
- #### Profiles 2: Electric Boogaloo by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2535
- #### [V2.6] Controls Revision by @Mathias-Boulay in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2900
- #### Patch 1 by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3033
- #### fix virgl by @LegacyGamerHD in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3057
- #### GL4ES: HOLY EDITION by @Mathias-Boulay in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3019
- #### Color selector by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3120
- #### Add the ability to unpack .pack files by @Mathias-Boulay in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3121
- #### New drawers by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3144
- #### Change Arc Capes title to Cosmetica Capes by @itsnebulalol in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3147
- #### Updates from mainline by @khanhduytran0 in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2482
- #### Forge 1.17 wip by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3216
- #### Jre17 autounpack u by @artdeell in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3227
- #### New Crowdin updates by @khanhduytran0 in https://github.com/PojavLauncherTeam/PojavLauncher/pull/1941
## New Contributors
- #### @NekoIceCream made their first contribution in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2073
- #### @rscDMTalt made their first contribution in https://github.com/PojavLauncherTeam/PojavLauncher/pull/2052
- #### @itsnebulalol made their first contribution in https://github.com/PojavLauncherTeam/PojavLauncher/pull/3147
- #### Full Changelog: https://github.com/PojavLauncherTeam/PojavLauncher/compare/crocus...dahlia
