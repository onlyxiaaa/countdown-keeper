# 🎯 Countdown Keeper

A beautiful, pastel-themed countdown tracker with a MacBook-style interface. Track your deadlines, stay focused with the Pomodoro timer, get motivated with daily quotes, and listen to your favorite Spotify playlists!

![Countdown Keeper](https://img.shields.io/badge/Status-Live-success)
![License](https://img.shields.io/badge/License-MIT-blue)

## ✨ Features

### 📅 **Countdown Tracker**
- Create unlimited countdowns for exams, deadlines, events, and more
- Choose from 12 fun icons (📚💼🔬💻🎨⚽🎮🎵✈️🎂💍🏆)
- Pick from 8 beautiful pastel colors
- Real-time countdown with days, hours, minutes, and seconds
- Automatically saves your countdowns

### 🍅 **Pomodoro Timer**
- Focus timer with work and break sessions
- **Customizable durations:**
  - Work sessions: 1-120 minutes (default: 25)
  - Short breaks: 1-60 minutes (default: 5)
  - Long breaks: 1-60 minutes (default: 15)
- Your settings are saved automatically
- Beautiful visual timer with controls

### 💭 **Daily Motivation**
- 20 inspiring quotes from famous figures
- Get a new quote with one click
- Beautiful gradient card design

### 🎧 **Music Player**
- **Default Music:** Calming meditation tracks built-in
- **Spotify Integration:**
  - Play your own playlists and albums
  - Works with FREE Spotify accounts
  - Just paste any Spotify link!
  - Full playback when logged into Spotify

### 💻 **MacBook Interface**
- Authentic macOS-style design
- Working menu bar with live clock
- Draggable, resizable windows
- macOS-style dock with hover effects
- Finder window to launch apps
- Beautiful pastel gradient background

## 🚀 Live Demo

Visit: `https://yourusername.github.io/countdown-keeper/`

## 📸 Screenshots

*(Add your screenshots here!)*

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
- **Vanilla JavaScript** - All functionality
- **Local Storage** - Data persistence
- **Spotify Web Player API** - Music integration

## 📦 Installation

### For Users:
Just visit the live site - no installation needed!

### For Developers:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/countdown-keeper.git
   ```

2. Open `index.html` in your browser

3. That's it! No build process required.

## 🎨 Customization

### Change Colors:
Edit the CSS variables in `styles.css`:
```css
:root {
    --pastel-pink: #FFB3D9;
    --pastel-purple: #E0BBE4;
    --pastel-blue: #B4D4FF;
    /* ... etc */
}
```

### Add More Quotes:
Edit the `quotes` array in `script.js`:
```javascript
const quotes = [
    { text: "Your quote here", author: "Author Name" },
    // Add more quotes...
];
```

### Change Default Music:
Replace the audio source in `index.html`:
```html
<audio id="bgMusic" loop>
    <source src="your-music-url.mp3" type="audio/mpeg">
</audio>
```

## 📱 Mobile Responsive

Fully responsive design that works on:
- 💻 Desktop
- 📱 Tablets
- 📱 Mobile phones

## 🌟 How to Use

### Create a Countdown:
1. Double-click "New Countdown" in Finder
2. Enter event name, date, and time
3. Choose an icon and color
4. Click "Add Countdown"

### Use Pomodoro Timer:
1. Open Pomodoro from Finder or Dock
2. Customize durations (optional)
3. Click Start to begin
4. Take breaks when timer completes

### Play Spotify Music:
1. Log into Spotify Web Player (open.spotify.com)
2. Open Music Player app
3. Switch to Spotify tab
4. Paste any playlist/album link
5. Click "Load Spotify Music"

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Inspired by macOS design language
- Fonts: Fredoka (Google Fonts)
- Icons: Emoji
- Music: Bensound.com (default track)

## 💬 Support

Having issues? 
- Check the [Deployment Guide](DEPLOYMENT_GUIDE.md)
- Open an issue on GitHub
- Contact: [your-email@example.com]

## 🎉 Enjoy!

Made with 💖 and lots of ☕

---

⭐ **Star this repo if you find it helpful!**
