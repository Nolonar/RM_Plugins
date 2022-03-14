# RPG Maker plugins
This page lists all RPG Maker plugins made by Nolonar.

| Project                                            | Description                                                 | Latest release                           |
| -------------------------------------------------- | ----------------------------------------------------------- | ---------------------------------------- |
|                                                    | **Compatible with MV and MZ**                               |                                          |
| [N_AutoTextReplace][N_AutoTextReplace]             | Automatically replaces some text with some other text.      | [1.0.0][N_AutoTextReplace_release]       |
| [N_HideIdleMouse][N_HideIdleMouse]                 | Hides the mouse cursor if it hasn't been moved for a while. | [1.0.0][N_HideIdleMouse_release]         |
| [N_Pixelate][N_Pixelate]                           | Disables smoothing to make graphics look pixelated.         | [1.1.0][N_Pixelate_release]              |
| [N_StartFullscreen][N_StartFullscreen]             | Automatically launches the game in fullscreen mode.         | [1.2.2][N_StartFullscreen_release]       |
| [N_TitleMap][N_TitleMap]                           | Renders an ingame map (including events) as title screen.   | [1.0.3][N_TitleMap_release]              |
|                                                    | **Compatible with MZ only**                                 |                                          |
| [N_Benchmark][N_Benchmark]                         | Adds a benchmark option to the game.                        | [1.1.1][N_Benchmark_release]             |
| [N_BustDialog][N_BustDialog]                       | Lets you use busts for dialogs instead of faces.            | [1.1.0][N_BustDialog_release]            |
| [N_EnhancedAutosave][N_EnhancedAutosave]           | Adds some improvements to the existing autosave feature.    | [1.1.0][N_EnhancedAutosave_release]      |
| [N_EnhancedTouchUIButton][N_EnhancedTouchUIButton] | Adds some improvements to the existing touch UI button.     | [1.0.1][N_EnhancedTouchUIButton_release] |
| [N_Minimap][N_Minimap]                             | Adds a minimap to the game.                                 | [1.0.1][N_Minimap_release]               |
| [N_SelfSwitchControl][N_SelfSwitchControl]         | Control Self Switches from other events and maps.           | [1.1.1][N_SelfSwitchControl_release]     |
| [N_SpeechBubbles][N_SpeechBubbles]                 | Renders speech bubbles above targets.                       | [1.1.0][N_SpeechBubbles_release]         |
| [N_TestMap][N_TestMap]                             | Adds option to launch test map instead of regular game.     | [1.0.2][N_TestMap_release]               |
| [N_WeatherFog][N_WeatherFog]                       | Adds procedurally generated fog weather effect.             | [1.2.1][N_WeatherFog_release]            |


## About MV support
I am no longer supporting MV. This means:
- New plugins will be developed exclusively for MZ (unless the MV version is trivial).
- Plugins that were originally compatible with MV will no longer be tested on MV when a new version is released.
- Plugins that are not "MV compatible" ***might*** still work with MV, but have never been tested. If a plugin has the following, ***it will definitely not work with MV***:
  - Uses plugin commands. MZ Plugin command interface is incompatible to MV. Making plugins compatible to both interfaces is a significant amount of additional work.
  - Creates (custom) windows. Window creation has changed considerably from MV. Making plugins compatible to both creation procedures is a significant amount of additional work.

## About versioning
All projects are versioned using following convention: `major.minor.revision`. For example, version 3.2.5 is:
- **Major**: 3
- **Minor**: 2
- **Revision**: 5

When a higher number changes, all lower numbers are reset to 0. For example, when 3.2.5 receives a Minor update to 3, the new version number is 3.3.0. When 3.2.5 receives a Major update to 4 instead, the new version number is 4.0.0

Here's what each change means:
- **Major**: These are likely to break your project. Make sure you perform a full test of your project when you update. Possible changes may include:
  - Use of new features not supported by older versions of RPG Maker (or its underlying NW.js engine). Do ***not*** update the plugin in this case, unless you've updated RPG Maker.
  - Some plugin command has been removed.
  - Some plugin command has been renamed.
  - The structure of parameters or arguments has changed and the plugin is incompatible to the old structure.

- **Minor**: These can change how the plugin behaves, which might affect player progression in certain circumstances. Possible changes may include:
  - Behavior of the plugin has changed, possibly through change in algorithm. Projects that rely on precise behavior may need testing.
  - Some plugin command has been added.
  - Plugin has become more customizable through additional parameters or arguments.
  - Major visual tweaks.

- **Revision**: These changes fix bugs or make minor adjustments to the code. These are unlikely to break your project or negatively affect player progression.

It is generally safe to update to a newer Revision number. When updating to a newer Minor or Major number, reading the release notes is recommended.

  [N_AutoTextReplace]: https://github.com/Nolonar/RM_Plugins-AutoTextReplace
  [N_AutoTextReplace_release]: https://github.com/Nolonar/RM_Plugins-AutoTextReplace/releases/latest/download/N_AutoTextReplace.js

  [N_HideIdleMouse]: https://github.com/Nolonar/RM_Plugins-HideIdleMouse
  [N_HideIdleMouse_release]: https://github.com/Nolonar/RM_Plugins-HideIdleMouse/releases/latest/download/N_HideIdleMouse.js

  [N_Pixelate]: https://github.com/Nolonar/RM_Plugins-Pixelate
  [N_Pixelate_release]: https://github.com/Nolonar/RM_Plugins-Pixelate/releases/latest/download/N_Pixelate.js

  [N_StartFullscreen]: https://github.com/Nolonar/RM_Plugins-StartFullscreen
  [N_StartFullscreen_release]: https://github.com/Nolonar/RM_Plugins-StartFullscreen/releases/latest/download/N_StartFullscreen.js

  [N_TitleMap]: https://github.com/Nolonar/RM_Plugins-TitleMap
  [N_TitleMap_release]: https://github.com/Nolonar/RM_Plugins-TitleMap/releases/latest/download/N_TitleMap.js

  [N_Benchmark]: https://github.com/Nolonar/RM_Plugins-Benchmark
  [N_Benchmark_release]: https://github.com/Nolonar/RM_Plugins-Benchmark/releases/latest/download/N_Benchmark.js

  [N_BustDialog]: https://github.com/Nolonar/RM_Plugins-BustDialog
  [N_BustDialog_release]: https://github.com/Nolonar/RM_Plugins-BustDialog/releases/latest/download/N_BustDialog.js

  [N_EnhancedAutosave]: https://github.com/Nolonar/RM_Plugins-EnhancedAutosave
  [N_EnhancedAutosave_release]: https://github.com/Nolonar/RM_Plugins-EnhancedAutosave/releases/latest/download/N_EnhancedAutosave.js

  [N_EnhancedTouchUIButton]: https://github.com/Nolonar/RM_Plugins-EnhancedTouchUIButton
  [N_EnhancedTouchUIButton_release]: https://github.com/Nolonar/RM_Plugins-EnhancedTouchUIButton/releases/latest/download/N_EnhancedTouchUIButton.js

  [N_Minimap]: https://github.com/Nolonar/RM_Plugins-Minimap
  [N_Minimap_release]: https://github.com/Nolonar/RM_Plugins-Minimap/releases/latest/download/N_Minimap.js

  [N_SpeechBubbles]: https://github.com/Nolonar/RM_Plugins-SpeechBubbles
  [N_SpeechBubbles_release]: https://github.com/Nolonar/RM_Plugins-SpeechBubbles/releases/latest/download/N_SpeechBubbles.js
  
  [N_SelfSwitchControl]: https://github.com/Nolonar/RM_Plugins-SelfSwitchControl
  [N_SelfSwitchControl_release]: https://github.com/Nolonar/RM_Plugins-SelfSwitchControl/releases/latest/download/N_SelfSwitchControl.js

  [N_TestMap]: https://github.com/Nolonar/RM_Plugins-TestMap
  [N_TestMap_release]: https://github.com/Nolonar/RM_Plugins-TestMap/releases/latest/download/N_TestMap.js

  [N_WeatherFog]: https://github.com/Nolonar/RM_Plugins-WeatherFog
  [N_WeatherFog_release]: https://github.com/Nolonar/RM_Plugins-WeatherFog/releases/latest/download/N_WeatherFog.js
