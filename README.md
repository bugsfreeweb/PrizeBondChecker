# Prize Bond Checker

A professional web application for checking Bangladesh Prize Bond tickets against official draw results with real-time PDF processing and advanced analytics.

![Prize Bond Checker](https://img.shields.io/badge/Prize-Bond%20Checker-green)
![Version](https://img.shields.io/badge/Version-2.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen)

## 🌟 Features

### ✅ **Core Functionality**
- **Real-time Ticket Checking**: Instantly verify prize bond tickets against official draw results
- **PDF Processing**: Direct integration with linked PDF files and user uploads
- **CORS Proxy Support**: Multiple proxy services for accessing external PDF documents
- **Multi-language Support**: Bengali and English numeral conversion
- **Priority-based Tier Assignment**: Accurate prize tier determination

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

### 🔧 **Technical Features**
- **PDF.js Integration**: Advanced PDF text extraction and processing
- **Cross-browser Compatibility**: Works on all modern browsers
- **Progressive Web App**: Fast loading and offline functionality
- **Error Handling**: Graceful degradation with user-friendly messages
- **Data Persistence**: Local storage with backup capabilities

## 🚀 Quick Start

### Option 1: Direct Usage (Under Development)
1. Download the `zip` file
2. Open it in any modern web browser
3. Start checking your prize bond tickets!

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000/index.html` in your browser.

## 📱 How to Use

### 1. **Enter Ticket Numbers**
- Input your prize bond ticket numbers (one per line)
- Supports 7-10 digit formats with leading zeros
- Example: `0624446`, `1234567`, `0001234`

### 2. **Select Draw**
- Choose from available draw options (Or User uploaded PDF draw result)
- Links to official PDF documents (User uploaded PDF draw result) are automatically processed
- CORS proxy services handle cross-origin PDF access

### 3. **Check Tickets**
- Click "Check Tickets" for single draw verification
- Use "Check All" to verify against multiple draws
- Real-time progress indicators show processing status

### 4. **View Results**
- Detailed results with prize amounts and tiers
- Winner notifications with celebration animations
- Analytics dashboard with comprehensive statistics

### 5. **Save & Export**
- Save ticket sets for quick reuse
- Export data for backup and sharing
- Import previously saved data

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
- **CSS3**: Custom properties, Grid, Flexbox
- **JavaScript (ES6+)**: Modern JavaScript features
- **PDF.js**: Client-side PDF processing
- **Font Awesome**: Professional icons
- **Google Fonts**: Typography (Inter, Plus Jakarta Sans)

### Key Components
- **PDF Processor**: Text extraction from official PDF documents
- **Tier Assignment Engine**: Priority-based prize tier determination
- **Analytics Engine**: Real-time statistics calculation
- **Data Manager**: Local storage with backup capabilities
- **Progress System**: Smooth animated feedback
- **CORS Proxy Handler**: Multiple proxy service fallbacks

### Browser Support
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🛠️ Configuration

### PDF URL Configuration
To add new draw PDFs, modify the draw selection options in the HTML:

```javascript
const drawOptions = [
    {
        value: "https://official-pdf-url.com| Draw Name|2025-01-01",
        textContent: "January 2025 Draw Results"
    }
    // Add more draws here
];
```

### CORS Proxy Services
The application includes multiple CORS proxy services for PDF access:
- allorigins.win
- corsproxy.io
- codetabs.com
- cors-anywhere.herokuapp.com

## 📊 Analytics & Reporting

### Dashboard Statistics
- **Total Checks**: Number of tickets verified
- **Winning Tickets**: Count of winning tickets
- **Total Prize Won**: Sum of all prize amounts
- **Win Rate**: Percentage of winning tickets

### Historical Data
- Complete check history with timestamps
- Detailed results for each check session
- Prize distribution analysis
- Performance trends over time

### Export Features
- JSON export for all data
- CSV export for ticket lists
- Backup/restore functionality
- Data migration tools

## 🎨 Customization

### Theme Customization
The application uses CSS custom properties for easy theming:

```css
:root {
    --primary-500: #10b981;
    --primary-600: #059669;
    --success-500: #10b981;
    --bg-card: #ffffff;
    --text-primary: #1f2937;
}
```

### Progress Colors
Customize the progress indicator colors in the CSS:

```css
.progress-fill {
    background: linear-gradient(90deg, #10b981, #059669, #047857);
}
```

## 🐛 Troubleshooting

### Common Issues

**PDF Not Loading**
- Check internet connection
- Verify PDF URL accessibility
- Try manual PDF upload if CORS blocked

**Tickets Not Found**
- Ensure ticket numbers are 7-10 digits
- Check for leading zeros (use full format)
- Verify ticket is from the correct draw

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

## 🔒 Security & Privacy

### Data Handling
- All data stored locally in browser
- No server-side data transmission
- User data never leaves the device
- PDF processing happens client-side

### Privacy Features
- No tracking or analytics
- No external API calls for user data
- Offline-first architecture
- Local storage encryption support

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Setup (Currently Private)
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

### Documentation
- [User Guide](docs/user-guide.md)
- [API Reference](docs/api-reference.md)
- [Troubleshooting Guide](docs/troubleshooting.md)

### Community
- **Issues**: Report bugs and request features
- **Discussions**: Community support and questions
- **Wiki**: Additional documentation and examples

## 🙏 Acknowledgments

- **PDF.js Team**: For the excellent PDF processing library
- **Font Awesome**: For the comprehensive icon set
- **Google Fonts**: For beautiful typography
- **Bangladesh Bank**: For official prize bond information
- **Community Contributors**: For feedback and suggestions

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/username/prize-bond-checker)
![GitHub forks](https://img.shields.io/github/forks/username/prize-bond-checker)
![GitHub issues](https://img.shields.io/github/issues/username/prize-bond-checker)
![GitHub pull requests](https://img.shields.io/github/issues-pr/username/prize-bond-checker)

---

**Made with ❤️ for the Bangladesh Prize Bond community**

*Last updated: December 2025*
