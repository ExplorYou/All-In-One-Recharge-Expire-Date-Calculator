# 🧮 All-in-One Calculator Suite

![Calculator Suite Banner](https://img.shields.io/badge/Calculator-Suite-blue?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)

## 📖 Overview

**All-in-One Calculator Suite** is a modern, responsive web application that combines three essential calculators in one beautiful interface:

- 📅 **Age Calculator** - Calculate exact age with precision
- 📱 **Phone Recharge Calculator** - Track recharge validity and expiry dates
- 📶 **WiFi Recharge Calculator** - Manage WiFi recharge schedules

## ✨ Features

### 🎨 Modern UI/UX
- Beautiful gradient design
- Smooth animations and transitions
- Dark/Light mode toggle
- Mobile-responsive layout
- Progressive Web App (PWA) support

### 📅 Age Calculator
- Calculate age in years, months, and days
- Total days lived
- Days until next birthday
- Real-time calculations

### 📱 Phone & WiFi Recharge Calculators
- Track multiple recharges
- Expiry date calculation
- Days remaining indicator
- Color-coded status (Active/Expiring/Expired)
- History management
- Export/Import functionality
- Local storage for data persistence

## 🚀 Live Demo

👉 **[Try it now!](https://your-username.github.io/calculator-suite)**

## 📸 Screenshots

### Age Calculator
![Age Calculator](https://via.placeholder.com/800x400/6366f1/ffffff?text=Age+Calculator)

### Recharge Calculator
![Recharge Calculator](https://via.placeholder.com/800x400/8b5cf6/ffffff?text=Recharge+Calculator)

### Dark Mode
![Dark Mode](https://via.placeholder.com/800x400/1a1a2e/ffffff?text=Dark+Mode)

## 🛠️ Installation

### Option 1: Direct Use
1. Download `index.html`
2. Open in any modern browser
3. That's it! No installation needed

### Option 2: GitHub Pages Deployment

1. **Fork this repository**
   ```bash
   Click the "Fork" button at the top right
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "main" branch
   - Click Save

3. **Access your site**
   - Your site will be live at: `https://your-username.github.io/calculator-suite`

### Option 3: Local Development

```bash
# Clone the repository
git clone https://github.com/your-username/calculator-suite.git

# Navigate to directory
cd calculator-suite

# Open in browser
# Simply double-click index.html or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

## 📱 Usage Guide

### Age Calculator
1. Click **"📅 Age"** tab
2. Enter your birth date (Day, Month, Year)
3. Click **"Calculate Age"**
4. View your exact age and additional details

### Phone/WiFi Recharge Calculator
1. Click **"📱 Phone"** or **"📶 WiFi"** tab
2. Enter name/number
3. Enter recharge date
4. Enter validity period (in days)
5. Click **"Calculate Expiry"**
6. **Save to History** to track it
7. View all saved recharges in history

### Managing History
- **Show History**: View all saved recharges
- **Export**: Download history as JSON file
- **Clear All**: Delete all history entries
- **Delete**: Remove individual entries

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `index.html`:

```css
/* Primary gradient */
background: linear-gradient(135deg, #6366f1, #8b5cf6);

/* Change to your colors */
background: linear-gradient(135deg, #YOUR_COLOR1, #YOUR_COLOR2);
```

### Adding More Features
The code is well-structured and easy to extend. Check the JavaScript section for:
- `calculateAge()` - Age calculation logic
- `calculateRecharge()` - Recharge calculation
- `saveToHistory()` - History management

## 🌐 Browser Support

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Opera (Latest)
- ✅ Mobile Browsers

## 💾 Data Storage

All data is stored locally in your browser using `localStorage`. Your data:
- ✅ Never leaves your device
- ✅ Remains private
- ✅ Persists across sessions
- ⚠️ Cleared if browser data is cleared

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Clear description
- Steps to reproduce
- Expected behavior
- Screenshots (if applicable)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- Email: your.email@example.com

## 🌟 Show Your Support

Give a ⭐️ if this project helped you!

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/your-username/calculator-suite?style=social)
![GitHub forks](https://img.shields.io/github/forks/your-username/calculator-suite?style=social)
![GitHub issues](https://img.shields.io/github/issues/your-username/calculator-suite)

## 🗺️ Roadmap

- [ ] Add more calculators (EMI, BMI, etc.)
- [ ] Multi-language support
- [ ] Cloud backup option
- [ ] Mobile app version
- [ ] Notification reminders for expiring recharges

## 💡 Tips

- Use the **Export** feature to backup your data regularly
- Enable **Dark Mode** for comfortable night-time use
- Bookmark the page for quick access
- Add to home screen on mobile for app-like experience

## 🆘 Support

Need help? 
- 📧 Email: your.email@example.com
- 💬 [Open an issue](https://github.com/your-username/calculator-suite/issues)
- 📚 [Wiki](https://github.com/your-username/calculator-suite/wiki)

---

Made with ❤️ by [Your Name](https://github.com/your-username)

**⭐ Don't forget to star this repo if you found it useful!**
