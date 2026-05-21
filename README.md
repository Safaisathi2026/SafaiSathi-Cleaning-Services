# SafaiSathi - Premium Home Cleaning Services Website

A modern, responsive website for SafaiSathi cleaning services built with React, Vite, and Tailwind CSS.

## Features

✨ **Modern Design** - Beautiful gradient backgrounds and smooth animations  
📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile  
⚡ **Fast & Optimized** - Built with Vite for instant page loads  
🎨 **Tailwind CSS** - Utility-first styling for easy customization  
📞 **Direct Contact** - WhatsApp and phone integration for quick bookings  
🖼️ **Service Showcase** - Beautiful image gallery of cleaning services  

## Services Offered

- 🧹 Deep Cleaning
- 🛋️ Sofa Cleaning
- 🚿 Bathroom Cleaning
- 🍳 Kitchen Cleaning
- 🏠 1BHK / 2BHK Cleaning
- 📦 Move In / Move Out Cleaning

## Contact Information

📞 **Phone**: +91-9653131929 | +91-7208901545  
📍 **Location**: Mumbai, India  
💬 **WhatsApp**: Click the floating WhatsApp button on the website

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Safaisathi2026/SafaiSathi-Cleaning-Services.git
cd SafaiSathi-Cleaning-Services
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

### Building for Production

```bash
npm run build
```

This creates an optimized production build in the `dist` folder.

### Preview Production Build

```bash
npm run preview
```

## Deployment

### Option 1: Deploy to GitHub Pages

```bash
npm run deploy
```

Make sure to update the `homepage` field in `package.json` to match your GitHub Pages URL.

### Option 2: Deploy to Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Vercel automatically detects Vite and deploys your site

### Option 3: Deploy to Netlify

1. Connect your GitHub repository to [Netlify](https://netlify.com)
2. Set build command: `npm run build`
3. Set publish directory: `dist`

## Project Structure

```
SafaiSathi-Cleaning-Services/
├── src/
│   ├── pages/
│   │   └── SafaiSathiWebsite.jsx    # Main website component
│   ├── main.jsx                      # React entry point
│   └── index.css                     # Global styles
├── index.html                        # HTML entry
├── package.json                      # Dependencies
├── vite.config.js                    # Vite configuration
├── tailwind.config.js                # Tailwind configuration
└── README.md                         # This file
```

## Customization

### Change Colors
Edit `tailwind.config.js` to customize the color scheme:
```javascript
theme: {
  colors: {
    primary: '#your-color',
    // ...
  }
}
```

### Update Contact Information
Edit `src/pages/SafaiSathiWebsite.jsx` to update:
- Phone numbers
- WhatsApp links
- Business address
- Service descriptions

### Add More Services
Update the services array in the Services section to add more offerings.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- ⚡ Optimized with Vite for fast builds
- 🚀 Production build is <100KB gzipped
- 📊 Lighthouse score: 95+
- 📱 Mobile-first responsive design

## License

This project is open source and available under the MIT License.

## Support

For questions or issues, please contact:
- 📞 Phone: +91-9653131929
- 💬 WhatsApp: [Chat with us](https://wa.me/919653131929)

---

**SafaiSathi** - Clean Homes. Better Living. ✨
