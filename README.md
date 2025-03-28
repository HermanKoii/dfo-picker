# DFO Team Picker

## 🎮 Project Overview

DFO Team Picker is a web application designed to help players of Dungeon Fighter Online (DNF/DFO) efficiently organize and distribute team members across three teams (Red, Blue, Green). The app provides an intelligent team allocation tool that considers character roles, combat power, and team balance.

### Key Features
- Character data retrieval from DFO API
- Manual character addition and management
- Automatic team classification algorithm
- Team power calculation
- Local storage of team compositions
- Interactive team assignment with color-coded teams

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+ recommended)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/dfo-picker.git
cd dfo-picker
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
Create a `.env` file in the project root and add any necessary configuration:
```
REACT_APP_API_URL=https://dfo-picker-backend.vercel.app/characters
```

4. Start the development server
```bash
npm start
```

The application will be available at `http://localhost:3000`

## 🌐 Deployment

### GitHub Pages
The project is configured for GitHub Pages deployment:
```bash
npm run deploy
```

### Alternative Deployment Options
- Vercel
- Netlify
- Docker (custom Dockerfile recommended)

## 📂 Project Structure
```
dfo-picker/
├── public/           # Static assets
├── src/              # Source code
│   ├── components/   # React components
│   ├── App.js        # Main application component
│   └── index.js      # Entry point
├── package.json      # Project dependencies and scripts
└── tailwind.config.js # Tailwind CSS configuration
```

## 🛠 Technologies Used
- React 18
- Axios (HTTP requests)
- Tailwind CSS
- LocalStorage for persistent data
- GitHub Pages for hosting

## ✨ Feature Highlights
- Character Search: Add characters by name
- Team Creation: Manually or automatically assign characters to teams
- Power Balancing: Algorithms to distribute characters across teams
- Responsive Design: Works on desktop and mobile

## 🔧 Configuration
- Customize team distribution logic in `App.js`
- Modify Tailwind configuration in `tailwind.config.js`
- Adjust API endpoints in the code

## 📄 License
This project is open-source. See the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! Please check the issues page and feel free to submit pull requests.

## 📞 Support
For issues or questions, please [open an issue](https://github.com/yourusername/dfo-picker/issues) on GitHub.