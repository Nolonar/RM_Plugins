# RPG Maker plugins
This page lists all RPG Maker plugins made by Nolonar.

| Project                                    | Description                                                                         | Latest release                       |
| ------------------------------------------ | ----------------------------------------------------------------------------------- | ------------------------------------ |
|                                            | **Compatible with MV and MZ**                                                       |                                      |
| [N_HideIdleMouse][N_HideIdleMouse]         | Hides the mouse cursor if it hasn't been moved for a while.                         | [1.0.0][N_HideIdleMouse_release]     |
| [N_StartFullscreen][N_StartFullscreen]     | Automatically launches the game in fullscreen mode.                                 | [1.1.1][N_StartFullscreen_release]   |
| [N_TitleMap][N_TitleMap]                   | Renders an ingame map (including events) as title screen instead of a static image. | [1.0.1][N_TitleMap_release]          |
|                                            | **Compatible with MZ only**                                                         |                                      |
| [N_EnhancedAutosave][N_EnhancedAutosave]   | Adds some improvements to the existing autosave feature.                            | [1.0.2][N_EnhancedAutosave_release]  |
| [N_SelfSwitchControl][N_SelfSwitchControl] | Control Self Switches from other events and maps.                                   | [1.1.0][N_SelfSwitchControl_release] |
| [N_SpeechBubbles][N_SpeechBubbles]         | Renders speech bubbles above targets.                                               | [1.0.4][N_SpeechBubbles_release]     |


## About versioning
All projects are versioned using following convention: `major.minor.revision`. For example, version 3.2.5 is:
- **Major**: 3
- **Minor**: 2
- **Revision**: 5

When a higher number changes, all lower numbers are reset to 0. For example, when 3.2.5 receives a Major update to 4, the new version number is 4.0.0

Here's what each change means:
- **Major**: These are likely to break your project. Make sure you perform a full test of your project when you update. Possible changes may include:
  - Use of new features not supported by older versions of RPG Maker (or its underlying NW.js engine). Do ***not*** update the plugin in this case.
  - Some plugin command has been removed.
  - Some plugin command has been renamed.

- **Minor**: These can change how the plugin behaves, which might affect player progression in certain circumstances. Possible changes may include:
  - Behavior of the plugin has changed, possibly through change in algorithm. Projects that rely on precise behavior may need testing.
  - Some plugin command has been added.
  - Plugin has become more customizable through additional parameters.
  - Major visual tweaks.

- **Revision**: These changes fix bugs or make minor adjustments to the code. These are unlikely to break your project or negatively affect player progression.

It is generally safe to update to a newer Revision number. When updating to a newer Minor or Major number, reading the release notes is recommended.

  [N_HideIdleMouse]: https://github.com/Nolonar/RM_Plugins-HideIdleMouse
  [N_HideIdleMouse_release]: https://github.com/Nolonar/RM_Plugins-HideIdleMouse/releases/latest/download/N_HideIdleMouse.js

  [N_StartFullscreen]: https://github.com/Nolonar/RM_Plugins-StartFullscreen
  [N_StartFullscreen_release]: https://github.com/Nolonar/RM_Plugins-StartFullscreen/releases/latest/download/N_StartFullscreen.js

  [N_TitleMap]: https://github.com/Nolonar/RM_Plugins-TitleMap
  [N_TitleMap_release]: https://github.com/Nolonar/RM_Plugins-TitleMap/releases/latest/download/N_TitleMap.js

  [N_EnhancedAutosave]: https://github.com/Nolonar/RM_Plugins-EnhancedAutosave
  [N_EnhancedAutosave_release]: https://github.com/Nolonar/RM_Plugins-EnhancedAutosave/releases/latest/download/N_EnhancedAutosave.js

  [N_SpeechBubbles]: https://github.com/Nolonar/RM_Plugins-SpeechBubbles
  [N_SpeechBubbles_release]: https://github.com/Nolonar/RM_Plugins-SpeechBubbles/releases/latest/download/N_SpeechBubbles.js
  
  [N_SelfSwitchControl]: https://github.com/Nolonar/RM_Plugins-SelfSwitchControl
  [N_SelfSwitchControl_release]: https://github.com/Nolonar/RM_Plugins-SelfSwitchControl/releases/latest/download/N_SelfSwitchControl.js
