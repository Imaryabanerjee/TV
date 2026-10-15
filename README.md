📺 Ultimate Live TV

🚀 Modern • Mobile-Friendly • Fast • Glassmorphism Live TV Player

A modern, responsive Live TV streaming web application built with HTML, CSS and JavaScript.

Ultimate Live TV provides a premium broadcast-style interface with HLS/M3U8 playback, channel search, favorites, categories, fullscreen mode, screen rotation, quality selection and mobile-optimized controls.

---

🌐 Live Demo

▶️ "Open Ultimate Live TV" (https://YOUR-USERNAME.github.io/ultimate-live-tv/)

«Replace "YOUR-USERNAME" with your GitHub username.»

---

✨ Features

Feature| Status
📺 Live TV Player| ✅
🔎 Smart Channel Search| ✅
⭐ Favorites| ✅
🗂️ Channel Categories| ✅
📱 Mobile Responsive| ✅
🖥️ Desktop Responsive| ✅
🎬 HLS / M3U8 Playback| ✅
▶️ YouTube Playback Support| ✅
🖥️ Fullscreen Mode| ✅
🔄 Screen Rotation| ✅
📐 Aspect Ratio Control| ✅
🎚️ Video Quality Selector| ✅
🖼️ Channel Logos| ✅
📡 Satellite-Style Loading Screen| ✅
📲 Swipe Channel Drawer| ✅
💾 Local Favorites Storage| ✅
⚡ Infinite Channel Loading| ✅
🌙 Automatic Dark Mode| ✅
💎 Glassmorphism UI| ✅

---

🎨 Interface

Ultimate Live TV uses a modern glassmorphism broadcast-studio design with:

- Transparent glass cards
- Dynamic gradients
- Dark/light system theme
- Animated LIVE indicator
- Sticky video player
- Responsive channel grid
- Broadcast-style error screen
- Satellite telemetry loading animation
- Mobile swipe navigation

---

📱 Mobile Experience

Designed specifically for smartphones and tablets.

Mobile features

- 📱 Responsive two-column channel grid
- 🔍 Easy channel search
- 👆 Touch-friendly controls
- ↔️ Swipe channel navigation
- 🔄 Landscape screen rotation
- ⛶ Fullscreen playback
- 📺 Picture-in-picture support
- ⭐ Persistent favorites

---

🔎 Smart Channel Search

The built-in search engine searches channel information including:

- Channel name
- Category
- Country
- Language
- Channel ID

Example searches:

Hindi News
Tamil
Bengali
Punjabi
Sports
Music
Movies
Zee
NDTV
ABP

---

🗂️ Channel Categories

Channels are automatically classified into categories such as:

📰 News & Current Affairs
🎵 Music
🎭 General Entertainment
🎬 Movies & Cinema
🏏 Sports
🧸 Kids & Animation
🔬 Infotainment & Documentaries
✈️ Lifestyle & Travel
💰 Business & Finance
🙏 Devotional & Spiritual
🎓 Educational
🌎 Regional & Local

---

⭐ Favorites

Users can save their favorite channels.

Favorites are stored locally using:

localStorage

This means the user's favorite channels remain available when they return to the website on the same browser/device.

---

📡 Playlist Sources

The current application reads M3U/M3U8 playlist data from configured external sources.

Example:

const 
«⚠️ Playlist availability, stream availability, licensing and redistribution rights are controlled by the respective source providers. Only use streams you are legally permitted to access or redistribute.»

---

🛠️ Technology

Ultimate Live TV is built using lightweight web technologies.

Frontend

HTML5
CSS3
JavaScript

Video Player

Video.js
Video.js HTTP Streaming
Video.js YouTube Tech
Video.js Quality Levels
HLS Quality Selector

Hosting

GitHub
GitHub Pages

---

📂 Project Structure

ultimate-live-tv/
│
├── index.html
│
├── README.md
│
├── assets/
│   ├── logo.png
│   └── favicon.png
│
└── .github/
    └── workflows/
        └── pages.yml

---

🚀 Run Locally

You don't need a complicated backend to test the project.

Option 1 — Open directly

Download the repository and open:

index.html

in a modern browser.

Option 2 — Local server

Using Python:

python -m http.server 8080

Then open:

http://localhost:8080

---

🌐 Deploy with GitHub Pages

1. Create a repository

Create a public GitHub repository:

ultimate-live-tv

2. Upload the project

Upload:

index.html
README.md

3. Open repository settings

Go to:

Settings
→ Pages

4. Select deployment source

Choose:

Deploy from a branch

Then:

Branch: main
Folder: / (root)

Click:

Save

After deployment your website will be available at:

https://YOUR-USERNAME.github.io/ultimate-live-tv/

---

⚙️ How It Works

             ┌──────────────────┐
             │  External M3U    │
             │    Playlists     │
             └────────┬─────────┘
                      │
                      ▼
             ┌──────────────────┐
             │   JavaScript     │
             │ Playlist Parser  │
             └────────┬─────────┘
                      │
                      ▼
             ┌──────────────────┐
             │ Channel Database │
             │ Search + Filter  │
             └────────┬─────────┘
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
       Search      Category    Favorites
          │           │           │
          └───────────┼───────────┘
                      ▼
             ┌──────────────────┐
             │   Video.js       │
             │   HLS Player     │
             └────────┬─────────┘
                      │
                      ▼
                 📺 LIVE TV

---

📱 Supported Browsers

Ultimate Live TV is designed for modern browsers.

Recommended

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari
- Android Chrome
- iOS Safari
- Samsung Internet

Actual stream compatibility depends on the stream format and browser/device support.

---

⚠️ Important Notes

CORS

Some external playlists and streams may block browser requests using CORS policies.

Ultimate Live TV cannot override restrictions imposed by external servers.

Stream availability

A channel may disappear, stop working, or change its URL without notice.

Copyright

This project is a frontend player/interface.

Users and operators are responsible for ensuring that the streams they access, publish or redistribute comply with applicable copyright, broadcasting, licensing and other laws.

---

🔐 Privacy

Ultimate Live TV does not require an account for the basic player.

Favorites are stored locally in the user's browser using:

localStorage

No server-side account is required for this functionality.

---

🧩 Roadmap

Future improvements may include:

- [ ] Automatic playlist database
- [ ] GitHub Actions playlist updater
- [ ] Central "channels.json"
- [ ] Faster channel loading
- [ ] Better stream health detection
- [ ] EPG / TV Guide
- [ ] Program schedules
- [ ] Recently watched channels
- [ ] Continue watching
- [ ] PWA support
- [ ] Installable Android Web App
- [ ] Custom domain
- [ ] Channel status monitoring
- [ ] Automatic duplicate detection
- [ ] Advanced channel sorting
- [ ] Regional language filters
- [ ] Multi-country channel support

---

🤝 Contributing

Contributions, improvements and bug reports are welcome.

Basic workflow

git clone https://github.com/YOUR-USERNAME/ultimate-live-tv.git

cd ultimate-live-tv

Create a branch:

git checkout -b feature/my-feature

Make your changes and commit:

git add .
git commit -m "Add new feature"

Push:

git push origin feature/my-feature

Then open a Pull Request on GitHub.

---

⭐ Support the Project

If you find this project useful:

⭐ Star the repository

🍴 Fork the project

🐛 Report bugs

💡 Suggest improvements

🔧 Submit Pull Requests

---

📜 License

This project is provided for educational and development purposes.

Before redistributing playlists, logos, streams or other third-party content, verify that you have the appropriate rights and permissions.

---

👨‍💻 Developer

Arya Banerjee

Ultimate Live TV

Built with ❤️ using:

HTML • CSS • JavaScript • Video.js • GitHub

---

📊 Project

⭐ Ultimate Live TV
📺 Live Streaming Web Player
📱 Mobile Friendly
🎬 HLS / M3U8
⚡ Fast & Responsive
🌐 GitHub Pages Ready

---

🔗 Links

Live Demo

https://YOUR-USERNAME.github.io/ultimate-live-tv/

Source Code

https://github.com/YOUR-USERNAME/ultimate-live-tv

---

⭐ Star This Repository

If Ultimate Live TV helps you, consider giving the repository a ⭐

Thank you for supporting the project!
