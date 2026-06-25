# 🎵 Spotify Clone

A front-end clone of Spotify's Web Player, built to practice HTML, CSS, and vanilla JavaScript — including interactive UI elements like a working search filter, hover-to-play buttons, and a functional progress bar.

## 🔗 Live Demo
[View it live](https://<your-username>.github.io/spotify-clone/)

*(Replace `<your-username>` with your GitHub username once deployed)*

## 📸 Screenshot
*(Add a screenshot of your homepage here once deployed)*

```md
![Spotify Clone Screenshot](screenshot.png)
```

## ✨ Features
- Responsive sidebar navigation with library shortcuts
- Recently Played, Trending, and Featured Charts sections with dynamic card layouts
- Hover-triggered play button overlay on each card
- Functional search bar that filters playlist/song cards in real time
- Click-to-load: clicking any card loads its art and title into the bottom music player
- Draggable progress bar that updates the current playback time
- Play/pause toggle on the player controls

## 🛠️ Tech Stack
- **HTML5** — semantic structure
- **CSS3** — custom styling, flexbox-based layout
- **JavaScript (Vanilla)** — DOM manipulation, event listeners, no frameworks
- **Font Awesome** — icon library
- **Google Fonts** — Montserrat Alternates

## 📂 Project Structure
```
spotify-clone/
├── index.html          # Main HTML file
├── Project1.css         # Stylesheet
├── library_icon.png     # Sidebar icon
├── player_icon1-5.png   # Player control icons
├── backward_icon.png
├── forward_icon.png
├── logo.png              # Favicon
└── README.md
```

## 🚀 Getting Started

### Run locally
```bash
git clone https://github.com/<your-username>/spotify-clone.git
cd spotify-clone
python3 -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

Or simply double-click `index.html` to open it directly.

## 📌 What I Learned
- Structuring a multi-section layout with reusable card components
- Using CSS pseudo-classes (`:hover`) to build interactive UI without JavaScript where possible
- Handling DOM events (`click`, `input`) to build real interactivity: search, play/pause, and progress tracking
- Organizing a front-end project for deployment on GitHub Pages

## 🔮 Future Improvements
- [ ] Hook up the HTML5 `<audio>` element to play real tracks
- [ ] Add a backend (Node.js/Express) to serve song data via an API
- [ ] User authentication and custom playlists
- [ ] Dark/light theme toggle
- [ ] Mobile-responsive layout for the sidebar and player

## 👤 Author
**Saumya Yadav**
B.Tech CSE (AI & Textile Technology), NITRA Technical Campus

- GitHub: [@your-username](https://github.com/<your-username>)

## 📄 License
This project is for educational/portfolio purposes only. Spotify branding and trademarks belong to Spotify AB — this is an unaffiliated clone built for learning front-end development.
