# Oostende Walk - Interactive Web Map

A web application optimized for iPhone browsers that visualizes a walking route through Oostende, Belgium, connecting 5 key locations.

## Features

- **Interactive Map**: Full OpenStreetMap integration with pan and zoom
- **Route Visualization**: Blue dashed line clearly showing the walking path
- **5 Location Markers**: Numbered markers (1-5) with color coding:
  - Green: Starting point (Christinastraat)
  - Blue: Middle stops (Koninginnelaan, Langestraat, Zeedijk Oostende)
  - Orange: Final destination (Edmond Laponstraat)
- **Location Details**: Tap any marker to see location information
- **Apple Maps Integration**: "Get Directions" buttons open Apple Maps for turn-by-turn navigation
- **Route Statistics**: 6.4 km total distance, 77 minutes estimated walking time
- **Mobile Optimized**: Designed specifically for iPhone Safari browser

## The Route

The walking route connects these 5 locations in Oostende:

1. **Christinastraat** (51.229722°N, 2.918056°E) - Starting point
2. **Koninginnelaan** (51.225509°N, 2.906796°E) - Second stop
3. **Langestraat** (51.233463°N, 2.917851°E) - Third stop
4. **Zeedijk Oostende** (51.219361°N, 2.886389°E) - Seaside promenade
5. **Edmond Laponstraat** (51.225833°N, 2.907778°E) - Final destination

All coordinates are real GPS locations sourced from official mapping data.

## How to Use

### On iPhone:
1. Open the web app URL in Safari
2. View the complete route on the interactive map
3. Tap any numbered marker to see location details
4. Tap "Get Directions" to open Apple Maps for navigation
5. Use "Start Walking" button to begin from the first location

### Features:
- **Pan**: Drag the map to explore
- **Zoom**: Pinch to zoom in/out or use +/- buttons
- **Markers**: Tap to see location information
- **Route Line**: The blue dashed line shows your walking path

## Technical Details

- **Map Library**: Leaflet.js 1.9.4
- **Map Tiles**: OpenStreetMap
- **No Installation Required**: Works directly in any modern web browser
- **Responsive Design**: Optimized for mobile screens
- **Offline Capable**: Can be saved as a web app on iPhone home screen

## Files

- `index.html` - Main application file (single-page app)
- `README.md` - This documentation
- `app_info.txt` - Route information summary

## Browser Compatibility

- ✅ iPhone Safari (iOS 12+)
- ✅ Chrome Mobile
- ✅ Firefox Mobile
- ✅ Desktop browsers (Chrome, Firefox, Safari, Edge)

## Add to iPhone Home Screen

For quick access, add this web app to your iPhone home screen:

1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it "Oostende Walk"
5. Tap "Add"

The app will now appear on your home screen like a native app!

## Data Source

All location coordinates are real GPS data from:
- OpenStreetMap
- Official Belgian mapping services
- Verified property records from Realo.be

## License

This is a custom web application created for visualizing the Oostende walking route.
