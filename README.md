# 🕒 DeskTime Clone - Productivity Tracking App

A pixel-perfect clone of the popular DeskTime productivity tracking application, built with modern web technologies.

![DeskTime Clone](https://img.shields.io/badge/DeskTime-Clone-green.svg)
![React](https://img.shields.io/badge/React-19-blue.svg)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-blue.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## ✨ Features

### 🔐 **Authentication System**
- **Complete Sign Up/Sign In** with form validation
- **Social Login Options** (Microsoft, LinkedIn, Google, Apple)
- **User Management** with role-based access
- **Persistent Sessions** with localStorage
- **Real-time Validation** and error handling

### ⏱️ **Time Tracking**
- **Real-time Timer** with start/pause/stop functionality
- **Active Time Counter** with live updates
- **Visual Status Indicators** for tracking state
- **Time Entry Management** with project assignment

### 📊 **Dashboard & Analytics**
- **Comprehensive Dashboard** with productivity overview
- **Weekly Productivity Charts** (Bar charts, Line graphs)
- **App Usage Monitoring** with productivity classifications
- **Team Performance Metrics** with individual tracking
- **Project Progress Tracking** with circular indicators

### 👥 **Team Management**
- **Team Member Overview** with status indicators
- **Productivity Scores** and time tracking per member
- **Role-based User Management** (Admin, Manager, Employee, Developer, Designer)
- **User Registration System** with auto-generated avatars

### 🎯 **Project Management**
- **Project Cards** with progress bars and deadlines
- **Time Allocation** vs budget tracking
- **Task Management** with completion status
- **Team Assignment** and collaboration features

### ⚙️ **Settings & Configuration**
- **Tabbed Settings Interface** (Profile, Users, Notifications, Privacy, Integration)
- **Notification Preferences** with toggle switches
- **Privacy Controls** for data collection
- **Integration Panel** for third-party services

## 🚀 Demo

Check out the live demo: [DeskTime Clone Demo](#)

### Demo Accounts
- **Manager**: sarah@company.com / password123
- **Developer**: john@company.com / demo123

## 🛠️ Tech Stack

- **Frontend**: React 19 with Hooks
- **Styling**: TailwindCSS 3.4
- **Charts**: Recharts for data visualization
- **Icons**: Lucide React
- **Progress Bars**: React Circular Progressbar
- **Routing**: React Router DOM 7.5
- **Date Handling**: date-fns 4.1

## 📦 Installation

### Prerequisites
- Node.js 18+ 
- Yarn package manager

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/desktime-clone.git
   cd desktime-clone
   ```

2. **Install dependencies**
   ```bash
   cd frontend
   yarn install
   ```

3. **Start the development server**
   ```bash
   yarn start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 📂 Project Structure

```
desktime-clone/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── App.js          # Main application component
│   │   ├── components.js   # All React components
│   │   ├── App.css         # Custom styles
│   │   └── index.css       # TailwindCSS imports
│   ├── package.json
│   └── tailwind.config.js
├── README.md
└── .gitignore
```

## 🔧 Configuration

### Environment Variables
```env
REACT_APP_BACKEND_URL=your_backend_url_here
```

### TailwindCSS
The project uses TailwindCSS for styling with custom configurations for the DeskTime brand colors.

## 📸 Screenshots

### Login Page
![Login](screenshots/login.png)

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Time Tracking
![Time Tracking](screenshots/time-tracking.png)

### User Management
![User Management](screenshots/user-management.png)

## 🎨 Design System

### Colors
- **Primary Green**: #10B981 (DeskTime brand green)
- **Background**: #F9FAFB (Light gray)
- **Text**: #1F2937 (Dark gray)
- **Success**: #10B981
- **Warning**: #F59E0B
- **Error**: #EF4444

### Typography
- **Font Family**: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto
- **Headlines**: 24px-32px, font-weight: 700
- **Body Text**: 14px-16px, font-weight: 400
- **Small Text**: 12px-14px, font-weight: 400

## 🔄 State Management

The application uses React's built-in state management with:
- **useState** for component state
- **useEffect** for side effects
- **localStorage** for data persistence
- **Context API** ready for complex state needs

## 📊 Data Structure

### User Object
```javascript
{
  id: number,
  name: string,
  email: string,
  role: 'Admin' | 'Manager' | 'Employee' | 'Developer' | 'Designer',
  avatar: string,
  joinDate: string
}
```

### Project Object
```javascript
{
  id: number,
  name: string,
  client: string,
  timeSpent: string,
  budget: string,
  progress: number,
  status: 'active' | 'completed' | 'paused',
  deadline: string,
  team: string[]
}
```

## 🚀 Features Roadmap

- [ ] **Real API Integration** with DeskTime API
- [ ] **Desktop App** with Electron
- [ ] **Mobile App** with React Native
- [ ] **Dark Mode** theme support
- [ ] **Advanced Reports** with PDF export
- [ ] **Team Chat** integration
- [ ] **Calendar Integration** (Google Calendar, Outlook)
- [ ] **Screenshot Monitoring** (optional feature)
- [ ] **Offline Mode** with sync
- [ ] **Time Zone Management**

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **DeskTime** for the original design inspiration
- **TailwindCSS** for the utility-first CSS framework
- **Recharts** for beautiful data visualization
- **Lucide** for the icon library

## 📞 Support

If you have any questions or need help with setup, please open an issue or contact:

- **Email**: your.email@example.com
- **GitHub**: [@yourusername](https://github.com/yourusername)

---

**Made with ❤️ by Aditi**

*This is a clone project created for educational purposes. It is not affiliated with the official DeskTime application.*
