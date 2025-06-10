# Energy Management System (EMS)

A full-stack application for monitoring and analyzing energy consumption, power factors, and peak loads in real-time.

## Project Structure

The project consists of two main components:

- `Vems client --- Frontend/`: Frontend React application
- `Energy api -- backend/`: Backend Node.js/Express API

## Features

- Real-time energy consumption monitoring
- KWH (Kilowatt-hour) tracking
- KVAH (Kilovolt-ampere-hour) monitoring
- Power factor calculations
- Monthly consumption analysis
- Peak load tracking
- Historical data visualization

## Screenshots

### Main Dashboard
![Main Dashboard](https://drive.google.com/uc?export=view&id=1RzimoGXqQc2oL4O31s17KmQLzrFEejkR)
The main dashboard provides an overview of key energy metrics and real-time monitoring.

### Power Control Center
![Power Control Center](https://drive.google.com/uc?export=view&id=1Ja0NQ1dDTq_6MMSrD5YBIJCC-9ZUQWQx)
Detailed power control center data showing power factors and consumption patterns.

### Data Records
![Data Records](https://drive.google.com/uc?export=view&id=16OTPIgs3APtq_BLq7133UrG-QkUNhz8i)
Historical data records and analytics for energy consumption.

## Getting Started

### Clone the Repository

1. Clone the repository using HTTPS:
   ```bash
   git clone https://github.com/yourusername/energy-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd energy-management-system
   ```

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Installation

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd "Energy api -- backend"
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with the following variables:
   ```
   PORT=4000
   MONGO_URL=your_mongodb_connection_string
   ```

4. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd "Vems client --- Frontend"
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## Technologies Used

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Axios
- date-fns

### Frontend
- React
- Vite
- Tailwind CSS
- Axios

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue in the repository or contact the development team. 