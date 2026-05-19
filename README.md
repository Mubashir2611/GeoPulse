# GeoPulse

A full-stack geospatial application that combines real-time location tracking, AI-powered insights, and interactive visualization with WebSocket communication.

## 🌍 Overview

GeoPulse is a modern web application that leverages geospatial data visualization and AI technologies to provide intelligent location-based services. The project features a React-based frontend with interactive maps and 3D globe visualizations, paired with a Node.js backend powered by Express and integrated with AI services.

## ✨ Features

- **Interactive Maps**: Real-time map visualization using Leaflet and React Leaflet
- **3D Globe Visualization**: Dynamic 3D earth visualization with React Globe GL
- **Real-time Communication**: WebSocket support via Socket.IO for live updates
- **AI Integration**: Groq SDK and OpenAI integration for intelligent geospatial analysis
- **User Authentication**: Google OAuth 2.0 authentication with Passport
- **Data Persistence**: MongoDB for data storage and Redis for caching
- **Responsive UI**: Built with React, Tailwind CSS, and Radix UI components
- **Real-time Notifications**: Toast notifications using Sonner
- **Data Visualization**: Charts and graphs using Recharts
- **Form Management**: Robust form handling with React Hook Form and Zod validation

## 🛠️ Tech Stack

### Frontend
- **React 19**: Modern UI library
- **Tailwind CSS**: Utility-first CSS framework
- **Radix UI**: Accessible component library
- **React Router**: Client-side routing
- **Leaflet & React Leaflet**: Map visualization
- **React Globe GL**: 3D globe visualization
- **Recharts**: Data visualization
- **Framer Motion**: Animation library
- **Axios**: HTTP client
- **Socket.IO Client**: Real-time communication

### Backend
- **Node.js**: JavaScript runtime
- **Express 5.2**: Web framework
- **MongoDB & Mongoose**: Database and ODM
- **Redis & IORedis**: Caching layer
- **Socket.IO**: Real-time bidirectional communication
- **Passport.js**: Authentication middleware
- **Google OAuth 2.0**: Social authentication
- **Groq SDK**: AI integration for geospatial analysis
- **OpenAI**: Advanced AI capabilities
- **JWT**: Secure token-based authentication
- **Helmet**: Security middleware
- **CORS**: Cross-origin resource sharing
- **Node Cron**: Task scheduling

## 📁 Project Structure

```
GeoPulse/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── utils/
│   │   └── App.js
│   └── package.json
├── backend/
│   ├── src/
│   │   ├── server.js
│   │   ├── routes/
│   │   ├── models/
│   │   ├── middleware/
│   │   └── config/
│   └── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB instance
- Redis instance
- Google OAuth credentials
- OpenAI and Groq API keys

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mubashir2611/GeoPulse.git
   cd GeoPulse
   ```

2. **Setup Backend**
   ```bash
   cd backend
   npm install
   ```

   Create a `.env` file in the backend directory:
   ```
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/geopulse
   REDIS_URL=redis://localhost:6379
   JWT_SECRET=your_jwt_secret
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret
   OPENAI_API_KEY=your_openai_api_key
   GROQ_API_KEY=your_groq_api_key
   ```

3. **Setup Frontend**
   ```bash
   cd ../frontend
   npm install
   ```

   Create a `.env` file in the frontend directory:
   ```
   REACT_APP_API_URL=http://localhost:5000
   REACT_APP_SOCKET_URL=http://localhost:5000
   ```

### Running the Application

**Start Backend Server**
```bash
cd backend
npm run dev
```

**Start Frontend Development Server**
```bash
cd frontend
npm start
```

The application will be available at `http://localhost:3000`

## 🔄 Real-time Features

GeoPulse uses Socket.IO for real-time communication, enabling:
- Live location updates
- Instant data synchronization
- Real-time notifications
- Collaborative features

## 🔐 Authentication

The application implements secure authentication using:
- **Google OAuth 2.0**: Social login integration
- **JWT**: Token-based session management
- **Password Encryption**: Secure credential storage

## 🤖 AI Integration

GeoPulse integrates multiple AI services:
- **Groq SDK**: Fast AI inference for geospatial analysis
- **OpenAI**: Advanced natural language and analysis capabilities

## 📊 Data Visualization

- **Interactive Maps**: Leaflet-based map visualization
- **3D Globe**: Three.js powered 3D earth visualization
- **Charts & Graphs**: Recharts for data analytics
- **Force-directed Graphs**: D3-force for network visualization

## 🔄 Caching Strategy

Redis is used for:
- Session management
- API response caching
- Real-time data caching
- Rate limiting

## 📝 API Architecture

The backend follows RESTful principles with:
- Structured routing
- Middleware-based authentication
- Error handling and validation
- CORS enabled for frontend communication

## 🛡️ Security Features

- **Helmet.js**: HTTP header security
- **CORS Configuration**: Controlled cross-origin requests
- **JWT Authentication**: Secure token validation
- **Input Validation**: Zod schema validation
- **Environment Variables**: Sensitive data protection

## 🧪 Testing

```bash
# Frontend tests
cd frontend
npm test

# Backend can be extended with test scripts
cd backend
npm test
```

## 📦 Build

**Build Frontend for Production**
```bash
cd frontend
npm run build
```

**Production Backend Setup**
```bash
cd backend
npm start
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the ISC License - see the LICENSE file for details.

## 👨‍💻 Author

**Mubashir2611** - [GitHub Profile](https://github.com/Mubashir2611)

## 🙏 Acknowledgments

- React and Node.js communities
- Radix UI for accessible components
- Tailwind CSS for styling
- Leaflet for mapping
- OpenAI and Groq for AI capabilities

## 📧 Support

For support, please open an issue on the [GitHub Issues](https://github.com/Mubashir2611/GeoPulse/issues) page.

---

**Made with ❤️ by Mubashir2611**
