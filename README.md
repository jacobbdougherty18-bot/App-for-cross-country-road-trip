# Road Trip Command Center

An epic cross-country road trip planner that works as a Progressive Web App (PWA) on your iPhone!

## Features

- **Interactive Route Planning** - Add start, end, and waypoint locations
- **Smart Gas Optimizer** - Calculates optimal fuel stops based on your vehicle's MPG
- **Budget Tracker** - Estimates total trip costs (gas, food, lodging)
- **Weather Forecast** - See weather conditions along your route
- **Scenic Attractions** - Discover interesting stops along the way
- **Photo Journal** - Save trip memories with captions
- **Emergency Services** - Quick access to 911, hospitals, mechanics
- **Offline Support** - Works without internet connection

## Installing on iPhone

### Method 1: Add to Home Screen (Recommended)

1. Open Safari on your iPhone
2. Navigate to the app URL
3. Tap the **Share** button (the square with an arrow pointing up)
4. Scroll down and tap **"Add to Home Screen"**
5. Name it "Road Trip" and tap **Add**
6. The app icon will appear on your home screen!

### Method 2: Using a Local Server

If running locally:

```bash
# Install a simple server (if you have Python)
python3 -m http.server 8080

# Or with Node.js
npx serve
```

Then open `http://your-computer-ip:8080` on your iPhone's Safari.

## Generating App Icons

1. Open `generate-icons.html` in a browser
2. Click "Generate & Download All Icons"
3. Move the downloaded PNG files to the `icons/` folder

## Files

- `index.html` - Main application
- `manifest.json` - PWA manifest for installation
- `service-worker.js` - Enables offline functionality
- `generate-icons.html` - Tool to generate app icons
- `icons/` - App icons for various sizes

## Usage

1. Enter your starting location (e.g., "New York")
2. Enter your destination (e.g., "Los Angeles")
3. Add waypoints like "Las Vegas" or "Grand Canyon"
4. Set your vehicle's MPG and tank size
5. Click **"Generate Epic Route"**
6. Explore attractions, gas stations, and food along your route!

## Browser Support

- Safari (iOS) - Full support with Add to Home Screen
- Chrome (Android) - Full PWA support
- Chrome/Firefox/Edge (Desktop) - Full support

Enjoy your road trip! 🚗
