# Spotify-Clone
This is a Clone project of the popular music streaming website - Spotify. Developed using HTML, CSS and JavaScript.
# 🎵 Spotify Clone

A simple Spotify clone that allows users to browse and play songs from dynamically loaded playlists.

## 🚀 Features

- 🎼 **Playlists**: Browse multiple playlists.
- 🎵 **Song Playback**: Play, pause, next, and previous controls.
- 📂 **Dynamic Playlist Addition**: Simply add a new playlist folder in `/Songs/` with a `cover.jpg` and `info.json`, and it appears automatically on the website.

## 📁 Folder Structure

```
Spotify-Clone/
│-- /Songs/
│   ├── Playlist1/
│   │   ├── cover.jpg
│   │   ├── info.json
│   │   ├── song1.mp3
│   │   ├── song2.mp3
│   ├── Playlist2/
│       ├── cover.jpg
│       ├── info.json
│       ├── song1.mp3
│       ├── song2.mp3
│-- index.html
│-- README.md
```

## 📜 Playlist Configuration

Each playlist must contain:

1. `` - A cover image for the playlist.
2. `` - A JSON file with playlist details.

### Example `info.json`

```json
{
    "title": "Chill Vibes",
    "description": "Just play and chill with your friends"
}
```

## 🛠 Installation & Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/PrajwalLad/Spotify-Clone.git
   cd spotify-clone
   ```
2. **Run the project:** (If using Live Server in VS Code)
   - Open `index.html` in Live Server.

## 🎤 Contributing

Feel free to fork the repo and submit a pull request with enhancements!

## 📜 License

MIT License

