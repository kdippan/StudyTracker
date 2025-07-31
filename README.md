# Study Points Tracker 📊

![Study Tracker Logo](https://i.postimg.cc/TP8dPLyt/2756-removebg-preview.png)

A gamified web application that helps students track study activities and stay motivated through a points-based reward system.

🌐 **Live Demo**: [https://trackstudyapp.netlify.app/](https://trackstudyapp.netlify.app/)

## Features ✨

- 🎛️ **Interactive Dashboard**
  - Real-time points tracking
  - Color-coded activity categories
- 📝 **Activity Tracking**
  - 10+ study activities with custom point values
  - Deductions for unproductive behaviors
- 📊 **Progress Visualization**
  - History log with timestamps
  - Animated feedback for actions
- 🔒 **Data Persistence**
  - Local storage saves all progress
- 📱 **Responsive Design**
  - Works on desktop, tablet, and mobile

## Points System 🏆

| Category           | Activity                     | Points  |
|--------------------|-----------------------------|---------|
| Study Activities   | Chapter reading             | +10     |
|                    | Active recall with testing  | +30     |
|                    | Practice papers             | +40     |
| Promus Activities  | 50 questions (4 quizzes)    | +4      |
|                    | Mind maps                   | +2      |
| Deductions         | Skipped studying            | -20/day |
|                    | Doom scrolling              | -50     |

## Technologies Used 💻

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
![Lordicon](https://img.shields.io/badge/Animated_Icons-FF3E00?style=for-the-badge)

## Getting Started 🚀

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge)

## Support ❤️

If you find this project useful, consider:
- [⭐ Starring the repository](https://github.com/kdippan/StudyTracker)
- [🐛 Reporting issues](https://github.com/kdippan/StudyTracker/issues)

## Future Roadmap 🗺️

- [ ] Add user accounts
- [ ] Implement weekly/monthly reports
- [ ] Dark mode support
- [ ] Mobile app version


name: Deploy to Netlify

on:
  push:
    branches: [main]

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - run: echo "Deploying to Netlify..."

## Project Structure 📂
StudyTracker/
├── main/
│   ├── index.html          # Main application file
│   ├── style.css           # CSS styles
│   ├── script.js           # JavaScript functionality
│   ├── assets/             # Additional assets
│   │   ├── images/         # Image files
│   │   └── fonts/          # Custom fonts
├── LICENSE                 # MIT License file
└── README.md               # Project documentation
