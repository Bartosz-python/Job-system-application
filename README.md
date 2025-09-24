# CareerPilot

**Navigate your career with confidence** - An intelligent job application system that helps you find and apply to the perfect jobs.

## ✨ Features

### 🎯 **Smart Job Discovery**
- **Swipe Interface** - Tinder-like job discovery experience
- **AI-Powered Matching** - Intelligent job recommendations based on your profile
- **Real-time Job Feed** - Fresh job postings from multiple sources

### 🤖 **Automated Applications**
- **One-Click Apply** - Swipe right to automatically apply
- **CV Management** - Upload and manage your resume
- **Auto-Fill Forms** - Automated form completion for job applications
- **Application Tracking** - Monitor all your applications in one place

### 👤 **Profile Management**
- **LinkedIn Integration** - Connect your professional profile
- **Skills & Keywords** - Set preferences for better job matching
- **Progress Tracking** - Monitor your application success rates
- **Personal Dashboard** - Track your career journey

### 🎨 **User Experience**
- **Dark Mode** - Beautiful dark and light themes
- **Responsive Design** - Works perfectly on all devices
- **Modern UI** - Clean, professional interface
- **Smooth Animations** - Delightful user interactions

## 🛠️ Tech Stack

- **Frontend**: Next.js 14, TypeScript, Tailwind CSS
- **Backend**: Express.js, PostgreSQL
- **Scraping**: Playwright for job data collection
- **Automation**: Playwright for auto-applications
- **Deployment**: Docker + Docker Compose

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd careerpilot
   ```

2. **Configure environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

3. **Start the application**
   ```bash
   docker-compose up --build
   ```

4. **Access the application**
   - Frontend: [http://localhost:3000](http://localhost:3000)
   - Backend API: [http://localhost:3001](http://localhost:3001)

## 📋 Environment Variables

See `.env.example` for required configuration values including:
- Database credentials (PostgreSQL)
- API keys for job scraping
- Service endpoints
- Authentication secrets

## 🎯 How It Works

1. **Sign Up** - Create your account and complete your profile
2. **Upload CV** - Add your resume for automatic applications
3. **Set Preferences** - Add skills and keywords for better matching
4. **Swipe Jobs** - Discover and apply to jobs with simple swipes
5. **Track Progress** - Monitor your applications and success rates

## 🔧 Development

### Prerequisites
- Node.js 18+
- Docker & Docker Compose
- PostgreSQL (if running locally)

### Local Development
```bash
# Install dependencies
npm run install:all

# Start development servers
npm run dev

# Or start individual services
npm run dev:frontend
npm run dev:backend
```

## 📱 Screenshots

- **Modern Login/Register** - Clean, animated forms with dark mode support
- **Job Swiping** - Intuitive swipe interface for job discovery
- **Profile Management** - Comprehensive profile setup and management
- **Application Tracking** - Monitor all your job applications
- **Dashboard** - Overview of your career journey

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the NCM License - see the LICENSE file for details.

## 🆘 Support

For support, email support@careerpilot.com or create an issue in the repository.

