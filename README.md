# ResumeGen 🚀

A modern, interactive Resume Builder application built with React. Create professional, customized resumes in minutes with a live preview feature.

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Chakra UI](https://img.shields.io/badge/Chakra--UI-319795?style=for-the-badge&logo=chakra-ui&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- **📝 Live Resume Editor** - Real-time preview as you type
- **🎨 Customizable Themes** - Choose from multiple color schemes
- **📸 Profile Picture Upload** - Add your professional photo
- **📄 Multiple Sections** - Build comprehensive resumes with:
  - Personal Information & Contact Details
  - Education History
  - Work Experience
  - Skills & Technologies
  - Projects Portfolio
- **💾 PDF Export** - Download your resume as a PDF
- **📱 Responsive Design** - Works seamlessly on desktop and mobile devices
- **⚡ Fast & Lightweight** - Built with modern React best practices

## 🖥️ Tech Stack

- **Frontend Framework:** React 17
- **UI Library:** Chakra UI
- **State Management:** React Context API
- **PDF Generation:** react-to-print, html2canvas, jsPDF
- **Icons:** React Icons
- **Fonts:** Google Fonts (Pacifico, Poppins)

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/resumegen.git
   cd resumegen
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```
   or
   ```bash
   yarn start
   ```

4. **Open your browser**
   - The app will automatically open at `http://localhost:3000`
   - If it doesn't, navigate to the URL manually

## 📖 Usage

1. **Fill in Your Information**
   - Navigate through the tabs: About, Education, Skills, Work, Projects
   - Enter your personal details, work experience, education, and projects

2. **Customize Your Resume**
   - Select a theme color from the theme selector
   - Upload your profile picture (optional)
   - Watch the live preview update in real-time

3. **Download Your Resume**
   - Click the "Download" button to export your resume as a PDF
   - Print directly from your browser if needed

## 📁 Project Structure

```
resumegen/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/
│   │   ├── BuildSteps/      # Form components for each section
│   │   │   ├── About.js
│   │   │   ├── Education.js
│   │   │   ├── Skills.js
│   │   │   ├── Work.js
│   │   │   └── Projects.js
│   │   ├── Layouts/         # Header, Navbar, Footer
│   │   ├── Theme/           # Theme selection components
│   │   ├── Builder.js       # Main builder component
│   │   ├── ResumePreview.js # Live preview component
│   │   └── Main.js          # Main container
│   ├── Context.js           # Global state management
│   ├── App.js               # Root component
│   └── index.js             # Entry point
├── package.json
└── README.md
```

## 🛠️ Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (irreversible)

## 🌐 Deployment

This project can be easily deployed on:
- **Netlify** (recommended for React apps)
- **Vercel**
- **GitHub Pages**
- Any static hosting service

### Deploy to Netlify

1. Build the project: `npm run build`
2. Drag and drop the `build` folder to Netlify
3. Or connect your GitHub repository for automatic deployments

