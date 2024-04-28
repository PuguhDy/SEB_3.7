# SEB_3.7

## Changes
- Added Indonesian translation.
- Fixed bug with registry data access.
- Implemented always on configuration for display and system.
- Implemented configuration values for critical and low battery charge thresholds.
- Implemented configuration value for lock screen on user session change.
- Fixed issue with registry monitoring and minor improvements (#747, #777).
- Increased spacing between lock screen options.
- Ensured pinch zooming also respects the zooming configuration value.
- Implemented cross-window sharing of clipboard content for isolated clipboard policy (#764).
- Added new configuration keys to allow down- and uploads separately and disabled down- and uploads by default.
- Introduced new configuration key to control verification of cursor configuration (#755).
- Added missing indirect wired video output technology.
- Updated browser engine to version 121.3.130 (Chromium version 121.0.6167.184).

The following optional features and changes are disabled by default and need to be configured individually:
- Disabled video proctoring with Jitsi Meet and Zoom as the functionality is deprecated and will be removed in a subsequent release.
- Revised proctoring architecture to allow for simultaneous activation of different implementations.
- Implemented screen proctoring functionality including metadata collection and network redundancy.

Requirements

- SEB 3.7.0 requires the prerequisites listed below in order to work correctly. These are automatically installed with the setup bundle and need only be manually installed when using the MSI packages.
- NET Framework 4.8 Runtime: https://dotnet.microsoft.com/download/dotnet-framework/net48
- Microsoft Edge WebView2 Runtime: https://go.microsoft.com/fwlink/p/?LinkId=2124703
- Visual C++ 2015-2019 Redistributable: https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads
  
## Untuk link download SEB bisa disini [SEB](https://github.com/SafeExamBrowser/seb-win-refactoring/releases)
