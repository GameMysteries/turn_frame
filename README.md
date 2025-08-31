# turn_frame
Card Match Prototype - Unity Game

Gameplay Preview: https://youtu.be/WVDP8qJFPIQ?si=0f_wz4dLEiMjNIcs

Created: 21-08-2004

IMPORTANT: This repository contains a complete Unity card-matching game prototype built from scratch.

Getting Started


STEP 1: Download the Game Builds

The game builds are packaged in build.zip and include:
- Windows 32-bit executable
- Windows 64-bit executable  
- Android APK

Extract build.zip and run the appropriate executable for your platform.

STEP 2: Opening the Unity Project (Optional)

If you want to examine or modify the source code:

1. Requirements: Unity 2021 LTS or compatible version
2. Open the card_game/ folder in Unity Hub
3. The project will load with all assets and scripts

What's Included


Project Structure:S
- files.txt - Contains detailed list of all project contents
- card_game/ - Complete Unity project with source code
- build.zip - Pre-built executables for Windows and Android

Game Features:
- Multiple board layouts (2x2, 2x3, 5x6, and more)
- Smooth card flip animations with continuous gameplay
- Save/Load system for progress persistence
- Scoring mechanism with combo potential
- Basic sound effects (flip, match, mismatch, game over)
- Cross-platform support (Desktop and Mobile)

Technical Implementation:
- Built from scratch in Unity 2021 LTS
- No external frameworks or purchased assets
- Optimized for performance over visual fidelity
- Clean, maintainable code architecture

Controls

- Mouse/Touch: Click or tap cards to flip
- R Key: Reset current board (desktop only)
- Esc Key: Quit game (desktop only)

Development Notes

This project demonstrates:
- Progressive Git commits from empty Unity project to final implementation
- Meaningful commit messages following team development practices
- Focus on code quality and requirement fulfillment
- Clean separation of concerns and modular design

The commit history shows the complete development process as requested in the original specification.

Platform Support

Tested and verified on:
- Windows 10/11 (32-bit and 64-bit)
- Android devices (API level 21+)

Save Data Location

Game progress is automatically saved to the platform's persistent data directory:
- Windows: %USERPROFILE%/AppData/LocalLow/[CompanyName]/[ProductName]
- Android: /storage/emulated/0/Android/data/[packagename]/files

For questions or issues, please refer to the commit history for implementation details.
