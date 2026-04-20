# SmartGarden

![SmartGarden Banner](https://via.placeholder.com/1200x300?text=SmartGarden+Project+Banner)

## Overview
SmartGarden is an innovative IoT-enabled system designed to help plant enthusiasts and gardeners automate and optimize plant care. Using sensor data and intelligent scheduling, SmartGarden monitors soil moisture, temperature, and light levels to ensure plants receive the ideal environment for growth.

---

## Features
- Real-time monitoring of soil moisture, temperature, and light.
- Automated watering system based on sensor thresholds.
- Customizable plant profiles to tailor care settings.
- Mobile-friendly web dashboard with analytics and notifications.
- Historical data visualization and trend analysis.
- Remote control of gardening devices.

---

## Tech Stack
- **Frontend:** React.js
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **IoT:** Arduino with sensors (moisture, temperature, light)
- **Communication:** MQTT protocol
- **Hosting:** Heroku

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/oliver64bag/SmartGarden.git
   cd SmartGarden
   ```
2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```
3. Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```
4. Configure environment variables in `.env` files for backend and frontend as per documentation.
5. Start the backend server:
   ```bash
   cd ../backend
   npm start
   ```
6. Start the frontend:
   ```bash
   cd ../frontend
   npm start
   ```

---

## Usage
- Access the dashboard at `http://localhost:3000`.
- Register or log in to create your garden profiles.
- Connect your IoT devices following the hardware setup guide.
- Monitor sensor data in real-time and configure automated watering schedules.
- View historical trends and receive alerts.

---

## Screenshots

![Dashboard Example](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

![Mobile View](https://via.placeholder.com/400x800?text=Mobile+Dashboard+Screenshot)

---

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Please ensure your code adheres to the existing style and is well-documented.

---

## License
Distributed under the MIT License. See `LICENSE` for more information.

---

## Author

[oliver64bag](https://github.com/oliver64bag) – passionate developer specializing in IoT and web applications.

---

Thank you for checking out SmartGarden! Grow smart, grow green. 🌱
