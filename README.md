
# 🌾 Smart Agritech Crop Monitoring System

## Overview
A real-time crop monitoring dashboard that combines weather data, simulated sensor readings, and intelligent alerts to help farmers make data-driven decisions.

## 🔧 Tech Stack
- **Frontend**: React.js (Dashboard Interface)
- **Backend**: Node.js + Express
- **Database**: MongoDB (Crop logs & sensor data)
- **APIs**: OpenWeatherMap Integration
- **Security**: JWT Authentication, bcrypt
- **Deployment**: Replit

## 📊 Core Features
1. **Weather Integration**
   - Real-time weather data display
   - 5-day weather forecast
   - Historical weather patterns

2. **Crop Health Dashboard**
   - Soil moisture levels
   - Temperature readings
   - Humidity monitoring
   - pH levels tracking

3. **Smart Alerts**
   - Pest detection warnings
   - Disease probability alerts
   - Weather-based recommendations
   - Irrigation scheduling

4. **Data Management**
   - Crop history logging
   - Yield predictions
   - Growth stage tracking
   - Performance analytics

## 🏗️ Project Structure
```
smart-agritech/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── utils/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── services/
└── database/
    └── schemas/
```

## 🚀 Getting Started
1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure environment variables:
   ```env
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   WEATHER_API_KEY=your_openweathermap_key
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## 📱 API Endpoints

### Authentication
- `POST /api/auth/register` - Register new user
- `POST /api/auth/login` - User login

### Crop Monitoring
- `GET /api/crops/status` - Get current crop status
- `POST /api/crops/log` - Add new crop log
- `GET /api/weather/forecast` - Get weather forecast

### Alerts
- `GET /api/alerts` - Get active alerts
- `POST /api/alerts/settings` - Update alert preferences

## 🔒 Security Features
- JWT-based authentication
- Password hashing with bcrypt
- Rate limiting on API endpoints
- Input validation & sanitization

## 📊 Dashboard Features
- Real-time sensor data visualization
- Interactive weather maps
- Crop health indicators
- Alert management interface

## 🤝 Contributing
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open pull request

## 📝 License
MIT License
