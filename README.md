# rio-2016-google-doodle

# 🍍 Google Doodle Fruit Games - Community Reconstruction

An unofficial reconstruction of Google's **2016 Doodle Fruit Games**, originally released for the Rio 2016 Olympics.

> ⚠️ This is a fan-made preservation/reconstruction project. It is not affiliated with or endorsed by Google.
> 

## 🎮 About

The 2016 Google Doodle Fruit Games were a collection of seven mini-games featuring the fruit characters competing in Olympic-style events.

The original games were eventually removed from Google's services, leaving the project partially lost and difficult to play.

This project aims to reconstruct the experience as faithfully as possible using recovered game data, assets, and reverse-engineered gameplay logic.

### All games are fully playable

## 📱 Current Status

**Playable reconstruction — Android**

The current build contains reconstructed versions of the original game's UI and gameplay.

### Reconstructed

- [x]  Main menu
- [x]  Game selection
- [x]  Game thumbnails
- [x]  Star ratings
- [x]  Game UI
- [x]  Gameplay systems
- [x]  Level data
- [x]  Touch controls
- [x]  Original-style visuals
- [x]  Game progression

### Work in progress

- [ ]  Perfect pixel-level visual accuracy
- [ ]  Performance optimizations
- [ ]  Full device compatibility

## 🔍 Preservation

The reconstruction was made possible through examination of recovered/decompiled Android game data.

The original application contains game logic, level definitions, sprites, UI resources, and other data that can be analyzed to understand how the original games worked.

Where possible, the reconstruction attempts to reproduce the behavior of the original rather than simply creating games inspired by it.

The original apk is the google-search.apk it has pineapple-release.jar within it. But it doesnt work as google has long since deprecated the necessary links and checks for the game to run. The original jar uses the now deprecated velour framework. The standalone apk removes the google app and the server checks

## 🛠️ Built With

- **Android Studio**
- **Java**
- Android SDK
- Decompiled/recovered game data
- Reverse engineering and manual reconstruction using Apktool and JADX

## 🚀 Building

### Requirements

- Android Studio
- Android SDK
- JDK compatible with the project's Gradle configuration

### Build

Clone the repository:

```bash
git clone <https://github.com/mokshpandey21/rio-2016-google-doodle.git>
