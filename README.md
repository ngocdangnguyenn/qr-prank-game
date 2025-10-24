# QR Prank Game - Educational Cybersecurity Project

## Overview
This is a small educational project designed for high school students in Vietnam as part of an Information Technology class activity to raise awareness about online scams and phishing attacks.

## Purpose
The main goal of this project is to teach students about:
- Online deception techniques and how scammers manipulate users
- Critical thinking when encountering suspicious websites and offers
- Cybersecurity awareness and recognizing red flags in digital environments
- Social engineering and understanding psychological manipulation tactics

## How It Works
1. Initial Entry: Students scan a QR code or open the website, then enter their name to participate in a game
2. Fake Loading: The website pretends to have a slow or weak connection, showing a loading bar that gets stuck at 98 percent
3. Repeated Refreshes: Students are prompted to refresh the page three times to continue loading
4. The Reveal: After the third refresh, the truth is revealed that the game never existed
5. Individual Ranking: Students see only their own ranking (e.g., "You are the 5th person pranked!")
6. Teacher Control: Teacher can reveal the full leaderboard to all students when ready
7. Real-time Updates: All changes sync instantly across all devices through Firebase

## Educational Value
This harmless prank demonstrates:
- How fake websites can appear legitimate
- The psychology behind just one more step tactics used by scammers
- Why users should be skeptical of unfamiliar websites
- The importance of verifying sources before providing personal information

## Technical Details
- Pure HTML, CSS, and JavaScript with no frameworks required
- Firebase Realtime Database for real-time data synchronization across devices
- Hosted on GitHub Pages for free and reliable hosting
- Mobile responsive design that works on all devices
- Vietnamese language support using system fonts for proper character rendering
- Real-time leaderboard updates visible to all participants simultaneously

## File Structure
```
qr-prank-game/
├── index.html
├── loading.html
├── result.html
├── leaderboard.html
└── styles.css
```

## How to Use

For Teachers:
1. Deploy the project to GitHub Pages or any web hosting service
2. Generate a QR code pointing to the deployed URL
3. Students scan the QR code or click the link to participate
4. Open leaderboard.html to monitor all participants in real-time
5. Click "Kết Thúc Trò Chơi" to reveal full rankings to all students
6. Click "Bắt Đầu Lại" to clear all data and start a new game session

For Students:
1. Scan the QR code or open the game link
2. Enter your name to begin
3. Follow the on-screen instructions and refresh prompts
4. See your individual ranking (until teacher ends the game)
5. Learn from the experience about online deception tactics

## Contact
- **Email**: [nndnguyen2016@gmail.com](mailto:nndnguyen2016@gmail.com)
- **LinkedIn**: [https://www.linkedin.com/in/ngocdangnguyenn](https://www.linkedin.com/in/ngocdangnguyenn)