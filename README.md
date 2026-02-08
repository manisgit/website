# Mobile Shop Management PWA

A Progressive Web App for managing your mobile repair shop.

## 🚀 Features

- ✅ **Installable** - Works like a native app on any device
- 📱 **Offline Mode** - Access your data even without internet
- 🔒 **Pattern Lock Support** - Record device pattern locks
- 📊 **Sales Dashboard** - Track daily and monthly revenue
- 💾 **Local Storage** - Data saved in your browser
- 🎨 **Responsive Design** - Works on desktop, tablet, and mobile

## 📲 How to Install as App

### On Desktop (Chrome, Edge, Brave):
1. Open `mobile-shop-manager.html` in your browser
2. Look for the install button (➕) in the address bar
3. Click "Install" when the banner appears
4. App will appear on your desktop/start menu

### On Android:
1. Open the site in Chrome
2. Tap the menu (⋮) → "Add to Home screen"
3. The app will install like a native app

### On iPhone/iPad:
1. Open in Safari
2. Tap the Share button (□↑)
3. Scroll and tap "Add to Home Screen"
4. Tap "Add"

## 🗂️ Files Needed

To run the PWA, you need these files in the same folder:

```
mobile-shop-manager.html    (Main app file)
manifest.json               (App configuration)
service-worker.js           (Offline functionality)
icon-192.png               (Small app icon - optional)
icon-512.png               (Large app icon - optional)
```

## 📝 Usage

1. **Add Devices**: Enter customer details, fault, and pattern lock
2. **Track Status**: Update device status (Pending → In Progress → Completed → Delivered)
3. **View Sales**: Monitor daily/monthly revenue and statistics
4. **Offline Access**: All features work without internet

## 🔄 Upgrading to Real Database

Currently uses localStorage (browser storage). To upgrade:

1. Set up a backend server (PHP/Node.js)
2. Create MySQL/PostgreSQL database
3. Update the `Database` class in the HTML file to make API calls
4. Deploy to a web server

## 🌐 Deployment Options

### Free Hosting:
- **GitHub Pages** (static hosting)
- **Netlify** (free tier)
- **Vercel** (free tier)

### Paid Hosting:
- **Shared Hosting** (₹100-500/month)
- **VPS** (Contabo: ₹200-300/month)

## 🔐 Security Notes

- Data is stored locally in the browser
- For production, add user authentication
- Use HTTPS when deploying online
- Regular backups recommended

## 💡 Tips

- **Export Data**: Use browser dev tools to backup localStorage
- **Multiple Users**: Each browser/device has separate data
- **Data Sync**: Will need backend for multi-device sync

## 📞 Support

For issues or questions, check browser console (F12) for errors.

---

**Version**: 1.0  
**Last Updated**: 2026
