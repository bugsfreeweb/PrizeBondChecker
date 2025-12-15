# Prize Bond Checker

A professional web application for checking Bangladesh Prize Bond tickets against official draw results with real-time PDF processing and advanced analytics.

![Prize Bond Checker](https://img.shields.io/badge/Prize-Bond%20Checker-green)
![Version](https://img.shields.io/badge/Version-2.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen)

## 🔗 Live Demo

Visit the live application:
- **Primary and Main V-2.0**: [https://prizebondbd.netlify.app](https://prizebondbd.netlify.app)
- **Secondary V-1.0**: [https://pbchecker.netlify.app](https://pbchecker.netlify.app)

![Prize Bond Preview](https://github.com/bugsfreeweb/PrizeBondChecker/blob/main/assets/screenshot_auth.png?raw=true)

## 🌟 Features

### ✅ **Core Functionality**
- **Real-time Ticket Checking**: Instantly verify prize bond tickets against official draw results
- **PDF Processing**: Direct integration with linked PDF files and user uploads
- **CORS Proxy Support**: Multiple proxy services for accessing external PDF documents
- **Multi-language Support**: Bengali and English numeral conversion
- **Priority-based Tier Assignment**: Accurate prize tier determination
- **Firebase Authentication**: Secure Google Sign-In integration

### 📊 **Advanced Analytics**
- **Real-time Statistics**: Total checks, winners, prize amounts, and win rates
- **Historical Tracking**: Complete check history with detailed results
- **Performance Metrics**: Win rate analysis and prize distribution charts
- **Data Export/Import**: Backup and restore functionality for all data

### 🎨 **User Experience**
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Professional progress indicators with vibrant styling
- **Dark/Light Theme**: User preference-based theme switching
- **Offline Capability**: Local storage for ticket sets and check history
- **Winner Celebrations**: Animated notifications for winning tickets
- **Bangladesh Flag Theme**: Beautiful flag-inspired design elements

### 🔧 **Technical Features**
- **PDF.js Integration**: Advanced PDF text extraction and processing
- **Cross-browser Compatibility**: Works on all modern browsers
- **Progressive Web App**: Fast loading and offline functionality
- **Error Handling**: Graceful degradation with user-friendly messages
- **Data Persistence**: Local storage with backup capabilities
- **Firebase Integration**: Secure user authentication and data sync

## 🚀 Quick Start

### Option 1: Direct Usage
1. Visit the live demo links above
2. Sign in with your Google account
3. Start checking your prize bond tickets!

### Option 2: Local Development (Still Under development)
```bash
# Clone or download the project
# Navigate to the project directory
cd prize-bond-checker

# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 📱 How to Use

### 1. **Authentication**
- Click "Sign In Securely" with your Google account
- Secure authentication prevents spam and protects user data

### 2. **Enter Ticket Numbers**
- Input your prize bond ticket numbers (one per line)
- Supports 7-10 digit formats with leading zeros
- Example: `0624446`, `1234567`, `0001234`
- Use the "Save Tickets" option to store commonly used numbers

### 3. **Select Draw**
- Choose from available draw options
- Upload your own PDF draw results for custom checking
- The app automatically processes official PDF documents

### 4. **Check Tickets**
- Click "Check Tickets" for single draw verification
- Use "Check All" to verify against multiple draws
- Real-time progress indicators show processing status

### 5. **View Results**
- Detailed results with prize amounts and tiers
- Winner notifications with celebration animations
- Analytics dashboard with comprehensive statistics

### 6. **Manage Data**
- Save ticket sets for quick reuse
- Export data for backup and sharing
- Import previously saved data
- Clear history when needed

## 🎯 Prize Structure

The application supports the standard Bangladesh Prize Bond structure:

| Prize Tier | Amount | Winners | Description |
|------------|--------|---------|-------------|
| 1st Prize | ৳6,00,000 | 1 | First prize winner |
| 2nd Prize | ৳3,25,000 | 1 | Second prize winner |
| 3rd Prize | ৳1,00,000 | 2 | Third prize winners |
| 4th Prize | ৳50,000 | 2 | Fourth prize winners |
| 5th Prize | ৳10,000 | 40 | Fifth prize winners |

## 🔧 Technical Architecture

### Frontend Technologies
- **HTML5**: Modern semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, CSS Variables
- **JavaScript (ES6+)**: Modern JavaScript features and Firebase SDK
- **PDF.js**: Client-side PDF processing
- **Font Awesome**: Professional icons
- **Google Fonts**: Typography (Inter, Plus Jakarta Sans, JetBrains Mono)

### Key Components
- **PDF Processor**: Text extraction from official PDF documents
- **Tier Assignment Engine**: Priority-based prize tier determination
- **Analytics Engine**: Real-time statistics calculation
- **Data Manager**: Local storage with backup capabilities
- **Progress System**: Smooth animated feedback
- **CORS Proxy Handler**: Multiple proxy service fallbacks
- **Firebase Auth**: Secure user authentication system

### Browser Support
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Design Features

### Bangladesh Flag Theme
- **Green Background**: Represents the green field of Bangladesh flag
- **Red Circular Card**: Represents the red circle of the flag
- **Professional Typography**: Clean, readable fonts for optimal user experience
- **Responsive Layout**: Adapts beautifully to all screen sizes

### User Interface
- **Splash Screen**: Animated loading with brand logo
- **Login Screen**: Secure Google authentication with flag theme
- **Dashboard**: Clean, organized layout with statistics cards
- **Sidebar Navigation**: Easy access to all application sections
- **Results Display**: Clear, detailed results with winner highlights

## 🔒 Security & Privacy

### Data Handling
- All data stored locally in browser
- No server-side data transmission of user tickets
- User data never leaves the device
- PDF processing happens client-side
- Firebase authentication for secure access

### Privacy Features
- No tracking or analytics
- No external API calls for user data
- Offline-first architecture
- Secure Google Sign-In integration
- Local storage with user control

## 🐛 Troubleshooting

### Common Issues

**PDF Not Loading**
- Check internet connection
- Verify PDF URL accessibility
- Try manual PDF upload if CORS blocked
- The app automatically tries multiple proxy services

**Authentication Issues**
- Ensure Google account is available
- Check browser permissions for popups
- Try refreshing the page
- Clear browser cache if needed

**Tickets Not Found**
- Ensure ticket numbers are 7-10 digits
- Check for leading zeros (use full format)
- Verify ticket is from the correct draw
- Ensure PDF contains the correct draw data

**CORS Errors**
- The app automatically tries multiple proxy services
- If all fail, download and upload PDF manually
- Check browser console for specific error details

### Debug Mode
Open browser console (F12) to view detailed processing logs and error messages.

## 📈 Performance

### Optimization Features
- **Lazy Loading**: PDF processing only when needed
- **Efficient Storage**: Optimized localStorage usage
- **Smooth Animations**: 60fps CSS animations
- **Responsive Design**: Optimized for all screen sizes
- **Progressive Loading**: Content loads as needed
- **Caching**: Intelligent caching of processed data

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Setup
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

### Getting Help
- **Issues**: Report bugs and request features on GitHub
- **Documentation**: Check this README for common solutions
- **Community**: Join discussions for community support

### Feature Requests
We welcome feature requests! Please:
1. Check existing issues first
2. Describe the feature clearly
3. Explain the use case
4. Provide mockups if applicable

## 🙏 Acknowledgments

- **PDF.js Team**: For the excellent PDF processing library
- **Font Awesome**: For the comprehensive icon set
- **Google Fonts**: For beautiful typography
- **Bangladesh Bank**: For official prize bond information
- **Firebase**: For secure authentication services
- **Community Contributors**: For feedback and suggestions

## 🏗️ Development

### Setup Development Environment
```bash
# Install dependencies (if any)
npm install

# Start development server
npm start

# Build for production
npm run build
```

### Code Style
- Use modern JavaScript (ES6+)
- Follow semantic HTML5 markup
- Use CSS custom properties for theming
- Maintain responsive design principles
- Add comments for complex logic

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/username/prize-bond-checker)
![GitHub forks](https://img.shields.io/github/forks/username/prize-bond-checker)
![GitHub issues](https://img.shields.io/github/issues/username/prize-bond-checker)
![GitHub pull requests](https://img.shields.io/github/issues-pr/username/prize-bond-checker)

## 🔄 Changelog

### Version 2.0.0 (Current)
- ✨ Added Firebase Google Authentication
- 🎨 Bangladesh flag-themed login interface
- 📱 Enhanced mobile responsiveness
- 🔧 Fixed PDF progress modal functionality
- 🎯 Improved user experience flow
- 📊 Enhanced analytics dashboard
- 🔒 Added secure logout functionality

### Version 1.x
- Basic ticket checking functionality
- PDF processing capabilities
- Local data storage
- Responsive design

---

**Made with ❤️ for the Bangladesh Prize Bond community**

*Built with Passion • Powered by Open Source*

*Last updated: December 15, 2025*
