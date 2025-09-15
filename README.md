# 💰 Marcel Expense Tracker - Smart Financial Management
### 🚀 Professional Full-Stack Expense Management Solution

<div align="center">

![Expense Tracker](https://img.shields.io/badge/Expense-Tracker-blue?style=for-the-badge&logo=money&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Transform the way you manage expenses with AI-powered insights, real-time analytics, and seamless financial tracking.**

[🌟 Live Demo](#) | [📖 Documentation](#) | [🐛 Report Bug](#) | [💡 Request Feature](#)

</div>

---

## ✨ Why Choose Marcel Expense Tracker?

🎯 **Smart & Intuitive** - AI-powered expense categorization and insights  
📊 **Advanced Analytics** - Real-time dashboards with beautiful charts and reports  
🔐 **Enterprise Security** - JWT authentication, role-based access, audit trails  
🌍 **Location-Aware** - Google Maps integration for location-based expense tracking  
📱 **Modern UI/UX** - Responsive design that works perfectly on any device  
⚡ **Lightning Fast** - Optimized performance with React 18 and Vite  
🐳 **DevOps Ready** - Fully containerized with Docker for seamless deployment  
🔄 **Real-time Updates** - Live expense tracking and instant notifications

---

## 🏗️ Architecture Overview

A modern, scalable full-stack application built with industry best practices:

```mermaid
graph TB
    A[🌐 React Frontend] --> B[🚀 Node.js API]
    B --> C[🍃 MongoDB Atlas]
    B --> D[🗺️ Google Maps API]
    B --> E[🤖 Gemini AI API]
    F[🐳 Docker] --> A
    F --> B
    G[🔐 JWT Auth] --> B
```

### 🎨 Frontend Stack
- **React 18** - Modern UI library with hooks and concurrent features
- **Vite** - Lightning-fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework for rapid styling
- **Chart.js** - Beautiful, responsive charts and analytics
- **React Router** - Client-side routing with code splitting

### ⚡ Backend Stack
- **Node.js & Express** - High-performance server-side JavaScript
- **MongoDB Atlas** - Cloud-native NoSQL database
- **JWT Authentication** - Secure token-based authentication
- **Winston Logging** - Professional logging with multiple transports
- **Input Validation** - Comprehensive data validation and sanitization

### 🔧 DevOps & Tools
- **Docker & Docker Compose** - Containerized development and deployment
- **ESLint & Prettier** - Code quality and formatting standards
- **Environment Management** - Secure configuration management
- **CORS Protection** - Cross-origin resource sharing security

---

## 🌟 Key Features

### 💼 Expense Management
- ➕ **Quick Expense Entry** - Add expenses in seconds with smart autocomplete
- 📂 **Smart Categorization** - AI-powered automatic expense categorization
- 📸 **Receipt Scanning** - Upload and attach receipts to expenses
- 🔄 **Recurring Expenses** - Set up automatic recurring transactions
- 🏷️ **Custom Tags** - Organize expenses with flexible tagging system

### 📊 Analytics & Reporting
- 📈 **Interactive Dashboards** - Real-time expense analytics and trends
- 📅 **Time-based Reports** - Monthly, quarterly, and yearly expense summaries
- 🎯 **Budget Tracking** - Set and monitor budgets with alerts
- 💡 **Smart Insights** - AI-powered spending insights and recommendations
- 📤 **Export Options** - PDF and CSV export for accounting

### 🗺️ Location Features
- 📍 **GPS Tracking** - Automatic location tagging for expenses
- 🚗 **Mileage Calculation** - Automatic distance and cost calculation
- 🏢 **Venue Recognition** - Smart venue detection and categorization
- 🛣️ **Route Optimization** - Suggest optimal routes for business travel

### 👥 User Management
- 🔐 **Secure Authentication** - JWT-based secure login system
- 👤 **User Profiles** - Customizable user profiles and preferences
- 🎭 **Role-based Access** - Admin, manager, and user role permissions
- 🔄 **Password Recovery** - Secure password reset functionality

### 🔒 Security Features
- 🛡️ **Data Encryption** - End-to-end data encryption
- 🔑 **API Security** - Rate limiting and request validation
- 📝 **Audit Trails** - Complete activity logging and monitoring
- 🚫 **XSS Protection** - Cross-site scripting prevention

---

## � Quick Start Guide

### 📋 Prerequisites

Before you begin, ensure you have the following installed on your system:

| Tool | Purpose | Installation |
|------|---------|-------------|
| 🐳 **Docker Desktop** | Container orchestration | [Download](https://www.docker.com/products/docker-desktop/) |
| 📂 **Git** | Version control | [Download](https://git-scm.com/) |
| 💻 **VS Code** *(recommended)* | Code editor | [Download](https://code.visualstudio.com/) |

### ⚡ One-Click Setup

```bash
# 1️⃣ Clone the repository
git clone https://github.com/marcelhess/Marcel-Expense-Project.git
cd Marcel-Expense-Project

# 2️⃣ Set up environment variables
cp .env.example .env
cp frontend/.env.example frontend/.env
# Edit .env files with your API keys

# 3️⃣ Launch the application
docker compose up --build

# 🎉 That's it! Your app is running at:
# Frontend: http://localhost:5173
# Backend API: http://localhost:5000
```

### 🔑 Environment Configuration

Create your `.env` file from the template and add your API keys:

```env
# 🔐 Security
JWT_SECRET=your-super-secret-jwt-key-here
API_INTERNAL_TOKEN=your-internal-api-token

# 🗄️ Database
MONGO_URI=mongodb://localhost:27017/expenses-tracker

# 🗺️ Google Maps (for location features)
GOOGLE_MAPS_API_KEY=your-google-maps-api-key

# 🤖 AI Features (optional)
GEMINI_API_KEY=your-gemini-api-key
```

> 💡 **Pro Tip**: Get your Google Maps API key from the [Google Cloud Console](https://console.cloud.google.com/) to enable location features!
brew install git
```

### 3. Code Editor (Recommended)

- **VS Code**: `brew install --cask visual-studio-code`
- **WebStorm**: `brew install --cask webstorm`
- **Sublime Text**: `brew install --cask sublime-text`

## 🚀 How to Use - Development Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Marcel-Expense-Project
```

### 2. Environment Configuration

The project is pre-configured with a cloud MongoDB database. The `.env` file already contains the necessary configuration:

```env
# Cloud Database (Pre-configured)
MONGO_URI=mongodb+srv://malekurt53:c2W5wfGYQovils7v@attend-wise.w8wfxrd.mongodb.net/attend-wise

# Backend Configuration
PORT=5000
JWT_SECRET=your-super-secret-jwt-key-change-in-production
JWT_EXPIRE=30d

# Frontend Configuration
VITE_API_URL=http://localhost:5000/api
```

**Note**: No additional environment setup is required as the cloud database is already configured.

### 3. Build and Run the Development Environment

```bash
# Build and start all services in development mode
docker compose up --build

# Or run in detached mode (background)
docker compose up --build -d
```

### 4. Access the Application

- **Frontend (Vite Dev Server)**: http://localhost:5173
- **Backend API**: http://localhost:5000
- **Database**: Cloud MongoDB Atlas (no local access needed)

### 5. Development Features

✅ **Hot Reloading**: Both frontend and backend automatically restart when you make code changes  
✅ **Cloud Database**: No local MongoDB setup required  
✅ **Development Mode**: Optimized for development with detailed logging  
✅ **Volume Mounting**: Source code changes are immediately reflected in containers

## 🔧 Development Commands

### Running Services

```bash
# Start all services
docker compose up

# Start in background
docker compose up -d

# Rebuild and start (after code changes)
docker compose up --build

# Start specific service
docker compose up backend
docker compose up frontend
```

### Viewing Logs

```bash
# View all logs
docker compose logs

# View specific service logs
docker compose logs backend
docker compose logs frontend

# Follow logs in real-time
docker compose logs -f

# View last 50 lines
docker compose logs --tail=50
```

### Stopping Services

```bash
# Stop all services
docker compose down

# Stop and remove volumes (if needed)
docker compose down -v

# Stop and remove everything (containers, networks, images)
docker compose down --rmi all

# Force stop all services immediately
docker compose kill

# Stop specific service
docker compose stop backend
docker compose stop frontend

# Restart services
docker compose restart

# Restart specific service
docker compose restart backend
docker compose restart frontend
```

## 💻 Development Workflow

### Making Code Changes

1. **Frontend Changes**:

   - Edit files in `./frontend/src/`
   - Changes are automatically reflected (hot reloading)
   - Vite dev server rebuilds instantly

2. **Backend Changes**:

   - Edit files in `./backend/src/`
   - Nodemon automatically restarts the server
   - API changes are immediately available

3. **Testing Changes**:

   ```bash
   # Check if services are running
   docker compose ps

   # Test backend API
   curl http://localhost:5000/

   # Access frontend
   open http://localhost:5173
   ```

### Database Management

The project uses a cloud MongoDB database, so no local database management is required. The database is automatically connected when the backend starts.

## 📁 Project Structure

```
Marcel-Expense-Project/
├── backend/
│   ├── src/                    # Backend source code (Node.js/Express)
│   │   ├── controllers/        # API controllers
│   │   ├── models/            # Database models
│   │   ├── routes/            # API routes
│   │   ├── middleware/        # Custom middleware
│   │   ├── config/            # Configuration files
│   │   └── server.js          # Main server file
│   ├── Dockerfile             # Development container config
│   ├── package.json           # Backend dependencies
│   └── logs/                  # Application logs
├── frontend/
│   ├── src/                   # Frontend source code (React/Vite)
│   │   ├── components/        # React components
│   │   ├── pages/            # Page components
│   │   ├── hooks/            # Custom React hooks
│   │   ├── context/          # React context
│   │   ├── api/              # API service functions
│   │   └── App.jsx           # Main App component
│   ├── Dockerfile            # Development container config
│   ├── package.json          # Frontend dependencies
│   └── vite.config.js        # Vite configuration
├── docker-compose.yml        # Development configuration
├── .env                      # Environment variables
└── README.md                 # This documentation
```

## 🔧 Development Services

### Backend (Node.js API)

- **Framework**: Express.js with Node.js
- **Port**: 5000
- **Environment**: Development mode with nodemon
- **Features**: Hot reloading, detailed logging, cloud database connection
- **Database**: Cloud MongoDB Atlas

### Frontend (React App)

- **Framework**: React with Vite
- **Port**: 5173
- **Environment**: Development mode with Vite dev server
- **Features**: Hot module replacement (HMR), fast refresh, instant rebuilds

## 🛠️ Useful Development Commands

### Docker Management

```bash
# Stop all services
docker compose down

# Rebuild specific service
docker compose build backend
docker compose build frontend

# Rebuild everything
docker compose build --no-cache

# Execute commands in running containers
docker compose exec backend npm install
docker compose exec frontend npm install

# View container status
docker compose ps

# Remove unused Docker resources
docker system prune -a
```

### Development Helpers

```bash
# Install new backend dependencies
docker compose exec backend npm install <package-name>

# Install new frontend dependencies
docker compose exec frontend npm install <package-name>

# Run backend tests (if available)
docker compose exec backend npm test

# Run frontend tests (if available)
docker compose exec frontend npm test

# Access backend shell
docker compose exec backend sh

# Access frontend shell
docker compose exec frontend sh
```

## 🐛 Troubleshooting

### Common Issues

1. **Docker Not Running**:

   ```bash
   # Start Docker Desktop
   open /Applications/Docker.app

   # Verify Docker is running
   docker --version
   ```

2. **Port Already in Use**:

   ```bash
   # Check what's using the ports
   lsof -i :5173  # Frontend
   lsof -i :5000  # Backend

   # Kill the process
   lsof -ti:5000 | xargs kill -9
   lsof -ti:5173 | xargs kill -9
   ```

3. **Database Connection Issues**:

   ```bash
   # Check backend logs for database connection
   docker compose logs backend

   # Look for "Connected to database" message
   # If connection fails, check internet connectivity
   ```

4. **Frontend Not Loading**:

   ```bash
   # Rebuild frontend
   docker compose build --no-cache frontend
   docker compose up frontend

   # Check frontend logs
   docker compose logs frontend
   ```

5. **Backend API Not Responding**:

   ```bash
   # Check backend status
   docker compose logs backend

   # Test API endpoint
   curl http://localhost:5000/

   # Restart backend
   docker compose restart backend
   ```

6. **Code Changes Not Reflecting**:

   ```bash
   # Ensure volume mounts are working
   docker compose down
   docker compose up

   # Check if files are mounted correctly
   docker compose exec backend ls -la /app/src
   docker compose exec frontend ls -la /app/src
   ```

### Quick Health Checks

```bash
# Check all services status
docker compose ps

# Test backend API
curl http://localhost:5000/

# Test frontend
open http://localhost:5173

# Monitor resource usage
docker stats
```

### Performance Tips

```bash
# Clean up unused Docker resources
docker system prune -a

# Restart Docker Desktop if slow
# Docker Desktop > Troubleshoot > Restart

# Allocate more resources to Docker
# Docker Desktop > Settings > Resources
# Recommended: 4GB RAM, 2 CPUs minimum
```

## 📝 Environment Configuration

### Pre-configured Variables

The following variables are already set up in the `.env` file:

| Variable       | Description              | Value                                  |
| -------------- | ------------------------ | -------------------------------------- |
| `MONGO_URI`    | Cloud MongoDB connection | Pre-configured cloud database          |
| `PORT`         | Backend server port      | 5000                                   |
| `JWT_SECRET`   | JWT signing secret       | Pre-configured (change for production) |
| `JWT_EXPIRE`   | JWT expiration time      | 30d                                    |
| `VITE_API_URL` | Frontend API URL         | http://localhost:5000/api              |

### Optional Variables (Already Configured)

| Variable              | Description             | Usage                   |
| --------------------- | ----------------------- | ----------------------- |
| `GOOGLE_MAPS_API_KEY` | Google Maps integration | For location features   |
| `GEMINI_API_KEY`      | AI integration          | For AI-powered features |
| `EMAIL_*`             | Email configuration     | For notifications       |

**Note**: All essential variables are pre-configured. No manual setup required for development.

## 🚀 Getting Started Summary

### Quick Start (3 Steps)

1. **Install Docker Desktop**:

   ```bash
   brew install --cask docker
   open /Applications/Docker.app
   ```

2. **Clone and Start**:

   ```bash
   git clone <repository-url>
   cd Marcel-Expense-Project
   docker compose up --build
   ```

3. **Access Application**:
   - Frontend: http://localhost:5173
   - Backend: http://localhost:5000

### Development Features

✅ **No Database Setup**: Uses cloud MongoDB  
✅ **Hot Reloading**: Instant code changes  
✅ **Pre-configured**: Ready to use out of the box  
✅ **Modern Stack**: React + Vite + Node.js + Express  
✅ **Docker Optimized**: Fast development containers

## 🤝 Contributing & Community

We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation, your help is appreciated.

### 🌟 How to Contribute

1. 🍴 **Fork** the repository
2. 🔀 Create a feature branch: `git checkout -b feature/amazing-feature`
3. ✨ Make your changes and add tests
4. 🧪 Test with Docker: `docker compose up --build`
5. 📝 Commit your changes: `git commit -m '✨ Add amazing feature'`
6. 🚀 Push to the branch: `git push origin feature/amazing-feature`
7. 🎯 Submit a **Pull Request**

### � Development Guidelines

- Follow existing code style and conventions
- Add tests for new features
- Update documentation as needed
- Use conventional commit messages
- Ensure Docker containers build successfully

---

## 🆘 Support & Help

### 💬 Get Help

| Issue Type | Solution |
|------------|----------|
| 🐛 **Bug Reports** | [Create an Issue](../../issues) |
| 💡 **Feature Requests** | [Start a Discussion](../../discussions) |
| ❓ **Questions** | [Join our Community](../../discussions) |
| 🔧 **Development Help** | Check logs: `docker compose logs` |

### 🔍 Troubleshooting

```bash
# 🔍 Debug checklist
docker compose ps              # Check service status
docker compose logs -f         # Watch live logs
curl http://localhost:5000/    # Test API connection
docker system prune -a         # Clean up Docker
```

---

## 🎯 Roadmap & Future Features

### 🚀 Coming Soon
- [ ] 📱 Mobile app (React Native)
- [ ] 🔗 Bank API integration
- [ ] 🤖 Advanced AI expense categorization
- [ ] 📊 Advanced analytics dashboard
- [ ] 🌐 Multi-language support
- [ ] 💼 Team collaboration features

### 🌟 Have Ideas?
We'd love to hear your suggestions! [Share your ideas](../../discussions) with the community.

---

## 👨‍💻 About the Developer

**Marcel Hess** - Full-Stack Developer & Financial Technology Enthusiast

- 🌐 Portfolio: [Coming Soon]
- 💼 LinkedIn: [Connect with Marcel]
- 📧 Email: [Contact]
- 🐙 GitHub: [@marcelhess](https://github.com/marcelhess)

---

## 📜 License & Legal

This project is licensed under the **ISC License** - see the [LICENSE](LICENSE) file for details.

### 🔒 Privacy & Security
- All data is encrypted and secure
- No personal information is collected without consent
- API keys are never stored in the repository
- Follow security best practices

---

<div align="center">

### 🌟 Star this repository if you find it helpful!

**Made with ❤️ by Marcel Hess**

![Stars](https://img.shields.io/github/stars/marcelhess/Marcel-Expense-Project?style=social)
![Forks](https://img.shields.io/github/forks/marcelhess/Marcel-Expense-Project?style=social)
![Issues](https://img.shields.io/github/issues/marcelhess/Marcel-Expense-Project)
![License](https://img.shields.io/github/license/marcelhess/Marcel-Expense-Project)

[⬆️ Back to Top](#-marcel-expense-tracker---smart-financial-management)

</div>
