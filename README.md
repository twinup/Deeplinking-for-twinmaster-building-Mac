# Deeplinking-for-twinmaster-building-Mac

Setup:
1. Download and install simple package installer
2. Download the twinmaster building script app

Process:
1. Export a Mac app from Unreal engine.
2. Move the exported app into the "Resources" folder inside package content of the twinmaster building script app
3. Open simple package installer app installed in setup.
4. Select the twinmaster building script app
5. Set package name "Twinmaster Building"
6. Set version
7. Set package bundle <URL Scheme> (com.twinup.building in current scenario)
8. The simple package installer will create a pkg file and open it in Finder window.
