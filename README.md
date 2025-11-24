# ONLINE-MUSIC-PLATFORM-
This is an upgraded desktop music system built with JavaFX for UI and media playback, SQLite for persistence, and jaudiotagger to read metadata.

## Features
- Add songs (mp3, wav, m4a) and read ID3 metadata
- Play / Pause / Stop
- Seek bar (progress)
- Volume control
- Search
- Persistent library stored in `music.db`

## Requirements
- JDK 17+
- Maven

## Run (development)
From project root:
```
mvn clean javafx:run
```

## Build
```
mvn clean package
```
