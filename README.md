# Damascus Assembly of God - Church Management System

A Progressive Web App (PWA) for managing church members, prayer requests, sermons, and attendance.

## Features

- 📱 **Progressive Web App** - Works offline with service worker caching
- 👥 **Member Management** - Add, view, and manage church members
- 🙏 **Prayer Requests** - Submit and track prayer requests from the congregation
- 📖 **Sermon Library** - Store and organize sermon information
- 📊 **Attendance Tracking** - Log and monitor church attendance
- 💾 **Local Storage** - All data stored locally in the browser
- 🎨 **Responsive Design** - Works on mobile, tablet, and desktop

## Installation

1. Clone this repository
2. Open `index.html` in your web browser
3. Add to home screen for PWA experience (mobile devices)

## Files

- `index.html` - Main application interface
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline functionality
- `README.md` - This file

## Usage

### Dashboard
View statistics about members, prayer requests, sermons, and attendance.

### Members
Add church members with their name, email, and phone number.

### Prayer Requests
Submit prayer requests with title, description, and your name.

### Sermons
Add and track sermon details including title, preacher, date, and summary.

### Attendance
Log attendance records with date and member name.

## Data Storage
create local database in the app
All data is stored in App's local database storage:
- `members` - Church members
- `prayers` - Prayer requests
- `sermons` - Sermon records
- `attLog` - Attendance log

## Browser Support

- Chrome/Chromium 50+
- Firefox 44+
- Safari 11.1+
- Edge 15+

## License

MIT License
