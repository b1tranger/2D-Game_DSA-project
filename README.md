  > related repo [Game-Development-Journey](https://github.com/b1tranger/Game-Development-Journey/)

[ repository created on 21st April 2025 ]

( note that further updates will be updated on https://github.com/b1tranger/Game-Development-Journey repo's Raylib_Game section, since the course is completed. )

# DSA-project
this repository will contain files for the Lab Project of Data Structures and Algorithms 1 course in UITS

demo gameplay: https://youtu.be/21WEimEq-vE

### # updates to do
- [ ] make a release version (export file, playable without dependencies)
- [ ] update game logic (broken physics, ball sticks to the paddle due to gravity)

# Note
- You must have Raylib installed before running the .exe ( DSA_Project_Game/x64/debug/*.exe )
- Guide: https://youtu.be/UiZGTIYld1M
- TLDR;

— Download https://github.com/microsoft/vcpkg .zip

— Unzip vcpkg in System Root (C drive)

— rename folder (remove "-master")

— run in powershell (type “powershell” in the explorer address bar):

	./bootstrap-vcpkg.bat
	./vcpkg integrate install
	./vcpkg install raylib:x64-windows

