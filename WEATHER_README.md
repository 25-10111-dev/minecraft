# ⛅ Weather Dashboard

A beautiful, real-time weather dashboard that fetches data from the OpenWeatherMap API. Check current weather conditions and 5-day forecasts for any city in the world!

## Features

🌍 **Global Weather Data**
- Real-time weather information for any city
- OpenWeatherMap API integration (free tier)
- 40,000+ cities supported

📊 **Current Weather Display**
- Current temperature and "feels like" temperature
- Weather description and icon
- Humidity, wind speed, pressure, visibility
- Min/max temperatures

📈 **5-Day Forecast**
- Daily weather predictions
- Temperature trends
- Weather condition icons
- Responsive card layout

🎨 **Beautiful UI**
- Modern gradient design
- Responsive layout (desktop, tablet, mobile)
- Smooth animations and transitions
- Font Awesome weather icons

💾 **Smart Features**
- Auto-save recent searches (localStorage)
- Auto-load last searched city
- Auto-refresh every 10 minutes
- 8 preset cities for quick access
- Enter key support for search

## How to Use

1. **Open** `weather.html` in your browser
2. **Search** for any city name
3. **View** current weather and forecast
4. **Quick search** using preset city buttons

### Quick Preset Cities
- London
- New York
- Tokyo
- Paris
- Dubai
- Sydney
- Seoul
- Singapore

## API Information

**API Used:** OpenWeatherMap API (Free Tier)
- Endpoint: api.openweathermap.org
- Current Weather: /data/2.5/weather
- Forecast: /data/2.5/forecast
- Units: Metric (°C, km/h, hPa)

## Data Displayed

### Current Weather
- 🌡️ Current temperature
- 🤔 Feels like temperature
- 📝 Weather description
- 💧 Humidity percentage
- 💨 Wind speed (km/h)
- 🎯 Atmospheric pressure (hPa)
- 👁️ Visibility (km)
- 🌡️ Max/Min temperatures

### 5-Day Forecast
- Date
- Weather condition
- Temperature
- Weather icon

## Technical Stack

- **HTML5** - Structure and markup
- **CSS3** - Modern styling with gradients
- **JavaScript (ES6)** - API integration and logic
- **Font Awesome** - Beautiful weather icons
- **OpenWeatherMap API** - Weather data
- **localStorage API** - Persistent storage

## Features Explained

### Real-time Updates
- Fetches current weather instantly
- Auto-refresh every 10 minutes
- Manual refresh by searching

### Smart Search
- Instant validation
- Case-insensitive city search
- Error handling for invalid cities
- Enter key support

### Responsive Design
- Works on all devices
- Mobile-optimized layout
- Touch-friendly buttons
- Flexible grid system

### Data Persistence
- Saves recent searches
- Auto-loads last searched city
- localStorage (no server needed)

## File Structure

```
minecraft/
├── weather.html          # Main weather dashboard page
├── js/
│   └── weather.js        # API logic and functionality
└── README.md            # This file
```

## Browser Support

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Full support

## Getting Started

### Option 1: GitHub Pages
Visit: `https://25-10111-dev.github.io/minecraft/weather.html`

### Option 2: Local Server
```bash
# Clone the repository
git clone https://github.com/25-10111-dev/minecraft.git
cd minecraft

# Run a local server
python -m http.server 8000

# Open in browser
http://localhost:8000/weather.html
```

### Option 3: Direct Open
- Simply open `weather.html` directly in your browser (may have CORS issues)

## API Key

The dashboard uses a free OpenWeatherMap API key for demonstration. For production:
1. Get your own API key from https://openweathermap.org/api
2. Replace the API_KEY in `js/weather.js`

## Tips & Tricks

- 💡 Try searching for different cities to build a collection
- 🔄 Data auto-refreshes every 10 minutes
- 📱 Works great on mobile devices
- ⌨️ Use Enter key for faster searching
- 💾 Last searched city loads automatically

## Common Questions

**Q: Is the API key free?**
A: Yes! OpenWeatherMap offers a free tier with up to 1000 calls/day.

**Q: What's the update frequency?**
A: Data auto-updates every 10 minutes, or manually on search.

**Q: Which cities are supported?**
A: Over 40,000 cities worldwide are supported.

**Q: How accurate is the forecast?**
A: Provided by OpenWeatherMap, accuracy varies by location.

## Future Enhancements

- [ ] Multiple city comparison
- [ ] Weather alerts and notifications
- [ ] Historical weather data
- [ ] Air quality index (AQI)
- [ ] UV index display
- [ ] Hourly forecast
- [ ] Weather maps
- [ ] Multiple language support
- [ ] Theme switching (dark/light mode)
- [ ] Export weather data

## License

MIT

## Credits

- Weather data: [OpenWeatherMap](https://openweathermap.org/)
- Icons: [Font Awesome](https://fontawesome.com/)
- Design inspiration: Modern web design best practices

---

**Enjoy checking the weather! 🌤️** Feel free to explore different cities and find the perfect weather information for your needs!
