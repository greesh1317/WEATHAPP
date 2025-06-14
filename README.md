
# Weather App  
**Company:** CODTECH IT SOLUTIONS  
**Name:** SOLASA GREESHMA DIVYA SREE  
**Intern ID:** CT04DN1334  
**Domain:** MERN Stack Web Development  
**Duration:** 4 weeks  
**Mentor:** NEELA SANTHOSH  

A clean, responsive weather application that shows current conditions using your location or city search.

# view

<img width="671" alt="W1" src="https://github.com/user-attachments/assets/b8a0b627-0ec3-4741-ae28-babb920b6b9a" />

Showing live weather data with animated icons and temperature display in Celsius/Fahrenheit


## Features  
- Shows temperature, conditions, and location  
- Automatic detection using your device's GPS  
- Search any city worldwide  
- Toggle between Celsius/Fahrenheit  
- Animated weather icons  
- Works on mobile and desktop  

## How It Works  
The app uses:  
1. **OpenWeatherMap API** - Gets real-time weather data  
2. **Geolocation API** - Finds your current position  
3. **JavaScript** - Processes data and updates display  
4. **CSS Animations** - For smooth transitions  

## Setup  
1. **Get API Key**:  
   - Sign up at [OpenWeatherMap](https://openweathermap.org)  
   - Get your free API key  

2. **Configure App**:  
   - Open `app.js`  
   - Replace `const key = "82005d..."` with your key  

3. **Run**:  
   - Just open `index.html` in any browser  

## File Structure  
- `app.js` - All the app logic  
- `index.html` - Main page structure  
- `style.css` - All styling  
- `icons/` - Weather condition images  
- `font/` - Custom font files  

### Temperature Toggle  
Click the temperature to switch between Celsius and Fahrenheit.

## Troubleshooting  
- **No weather data?** Check your API key  
- **Location not working?** Allow browser permissions  
- **City not found?** Try different spellings  

## Customization  
1. **Change colors**: Edit `style.css`  
2. **Add more icons**: Add PNGs to `icons/` folder  
3. **Extend features**:  
   - Add 5-day forecast  
   - Include humidity/wind details  

## Browser Support  
Works on all modern browsers (Chrome, Firefox, Safari, Edge). For IE11, you'd need polyfills.

## Why This App?  
- Lightweight (no frameworks)  
- Fast loading  
- Easy to modify  
- Great for learning API integration  

## Next Steps  
Possible improvements:  
- Save recent searches  
- Add dark/light mode  
- Implement offline caching  





