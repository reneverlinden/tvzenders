# My TVCHANNELS (Mijn TV ZENDERS)

A personalized, lightweight HTML TV guide dashboard designed specifically for Android TV and Google TV web browsers (like TV Bro). It allows quick, single-click access to live Belgian television streams without getting blocked by Android local file restrictions.

## 📺 Supported Channels
- **VRT MAX:** VRT 1, VRT Canvas
- **GoPlay:** Play, Play Fictie, Play Actie, Play Reality, Play Crime
- **VTM GO:** VTM 1, VTM 2, VTM 3, VTM 4
- **RTBF Auvio:** La Une, Tipik, La Trois

## 🚀 How It Works
1. The dashboard is hosted completely free via **GitHub Pages**.
2. Instead of standard Android Intents (which are often blocked by TV browsers), this project uses **Deep Links (Direct App URLs)** and official web streaming links.
3. When clicked inside a TV browser, it seamlessly opens the corresponding live stream or triggers the native TV app.

## ⚙️ TV Setup Optimization (One-time setup)
To ensure the links open directly inside your official TV apps instead of loading the desktop websites, configure your Google TV Streamer as follows:
1. Go to **Settings** -> **Apps** -> **Default apps** (or **Special app access**).
2. Select **Opening links**.
3. Find **VTM GO**, **GoPlay**, or **VRT MAX** in the list and set **Open supported links** to **Always open in this app**.

## 🛠️ Customization
To add or remove channels, simply edit the `index.html` file in this repository. 
