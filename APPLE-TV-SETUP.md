# 📺 How to View Your Movie Collection on Apple TV

## 🚀 Quick Start (Local Network - Easiest)

### Step 1: Start the Server on Your Mac
```bash
cd /Users/punithamac/AITest
./start-server.sh
```

The script will display a URL like: `http://192.168.1.100:8000/index.html`

### Step 2: Open on Apple TV
1. On Apple TV, open **Safari** app
2. Type in the URL shown in Terminal
3. Bookmark it for easy access
4. Enjoy your collection!

**Requirements:**
- tvOS 17 or later (for Safari support)
- Mac and Apple TV on same WiFi network
- Keep Terminal window open while using

---

## 🌐 Online Hosting (Access from Anywhere)

### Method 1: GitHub Pages (Free, Recommended)

1. **Create GitHub Account**: https://github.com/signup

2. **Create New Repository**:
   - Click "+" → "New repository"
   - Name it: `movie-collection`
   - Make it Public
   - Click "Create repository"

3. **Upload Your File**:
   - Click "Add file" → "Upload files"
   - Drag `index.html` into the browser
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: "main" → "/ (root)"
   - Click "Save"

5. **Access Your Site**:
   - URL: `https://yourusername.github.io/movie-collection`
   - Open this URL on Apple TV Safari
   - Bookmark it!

### Method 2: Netlify Drop (Super Fast)

1. Go to: https://app.netlify.com/drop
2. Drag and drop your `index.html` file
3. Get instant URL (e.g., `random-name.netlify.app`)
4. Open on Apple TV Safari

---

## 📱 Alternative Access Methods

### AirPlay from iPhone/iPad/Mac
1. Open the collection on your device
2. Tap AirPlay icon
3. Select your Apple TV
4. View on TV screen

### Shortcuts App (iOS/tvOS)
Create a shortcut to quickly open your collection URL

---

## 🎮 Navigation on Apple TV

### Using Siri Remote:
- **Swipe**: Navigate between movies
- **Click**: Select/Check watched
- **Click & Hold on Movie**: View details
- **Menu Button**: Go back
- **Siri**: "Open Safari" to launch browser

### Tips for Best Experience:
- Use landscape orientation
- Bookmark the page for quick access
- Search box works with keyboard (Settings → Remotes and Devices → Remote → Text Input)
- Pair Bluetooth keyboard for easier text entry

---

## 🔧 Troubleshooting

### "Cannot Connect" Error
- Ensure Mac and Apple TV are on same WiFi
- Check Mac's firewall settings (allow incoming connections)
- Verify the IP address is correct

### Safari Not Available on Apple TV
- Update to tvOS 17 or later
- Settings → General → Software Updates

### Server Stops Working
- Keep Terminal window open
- Don't close or sleep your Mac
- Restart server script if interrupted

### Genres Not Loading
- Requires internet connection for TMDB API
- Genres are cached after first load

---

## 💡 Pro Tips

1. **Create Home Screen Shortcut**:
   - In Safari, press and hold on the page
   - Save to Home Screen (if available on tvOS)

2. **Use Siri**:
   - "Open Safari"
   - Then navigate to bookmarked collection

3. **Keep Mac Awake**:
   - System Settings → Energy Saver
   - Prevent sleep while server running

4. **Update Collection**:
   - Edit `index.html` on your Mac
   - Refresh page on Apple TV (reload in Safari)

---

## 🎯 Next Steps

- [ ] Choose hosting method (local or online)
- [ ] Set up server or upload to GitHub
- [ ] Access on Apple TV Safari
- [ ] Bookmark for easy access
- [ ] Start tracking your watched movies!

---

## Need Help?

- **Local Server Issues**: Check firewall settings, WiFi connection
- **GitHub Pages**: Follow their documentation at https://pages.github.com
- **Apple TV Safari**: Requires tvOS 17+, update in Settings

Enjoy your Apple TV-themed movie collection! 🍿
