# Galaxy Defense

C++17 tower-defense game built with SFML 3 for Windows.
Inspired by Galaxy Defense Fortress Guard (iOS).

## Build

Open the folder in Visual Studio 2022. CMake configures automatically.
Pick `GalaxyDefense.exe` as the startup item and press F5.

## Conventions

- C++17, no exceptions in gameplay code
- Prefer simple structs + free functions over deep OOP hierarchies
- Game logic in `src/`, one .cpp/.h pair per entity (tower, enemy, laser)
- SFML 3 API only — note that older tutorials use SFML 2 which differs