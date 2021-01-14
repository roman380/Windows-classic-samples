# Windows Classis Samples; Windows 7 Samples; DirectShow

Some of DirectShow classic Windows SDK samples in these subdirectories are upgraded to be built with Microsoft Visual Studio 2019 Community.

To build and run the code you need:

- [Microsoft Visual Studio 2019 Community](https://visualstudio.microsoft.com/vs/community/)
- Latest [Windows 10 SDK](https://developer.microsoft.com/en-US/windows/downloads/windows-10-sdk/), Windows 10 SDK (10.0.19041.0) for Windows 10, version 2004 should be okay

Updated samples:

- [players\dshowplayer](players/dshowplayer)
- [dmo\dmodemo](dmo/dmodemo)
- [baseclasses](baseclasses)

Many samples require to link BaseClasses static library; I changed traditional llegacy ibrary naming (strmbase.lib, strbasd.lib) and placement, and these samples are updated for fresh environment and are re-refrenced to updated static library:

- [filters\ezrgb24](filters/ezrgb24)
- [filters\wavdest](filters/wavdest)

All updated projects are combined in top level [directshow.sln](directshow.sln) solution file.
