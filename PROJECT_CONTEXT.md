# 🏦 Sauce Banking Demo - Project Context Document

## 🎯 PROJECT OVERVIEW
This is a **mobile-first banking demo application** designed to showcase Sauce Labs testing capabilities. It's a fully interactive HTML/CSS/JavaScript web application that simulates a complete mobile banking experience.

## 📍 CURRENT STATE
- **Repository**: https://github.com/SauceSETeam/sauce-banking-demo
- **Live Demo**: https://sauceseteam.github.io/sauce-banking-demo/
- **Current Branch**: `gh-pages` (THIS IS THE ACTIVE BRANCH FOR THE WEBSITE)
- **Location**: `/Users/david.levine@saucelabs.com/sauce-banking-demo`
- **Status**: Clean working tree, deployed and live

## 📂 PROJECT STRUCTURE
```
sauce-banking-demo/
├── index.html          # Main banking app (mobile-responsive)
├── presenter.html      # Demo presenter view with talking points
├── README.md          # Project documentation
└── PROJECT_CONTEXT.md # This file - for AI context
```

## 🎨 APPLICATION FEATURES

### Main App (index.html)
The banking app includes these screens and features:

1. **Login Screen**
   - Username/Password authentication
   - Biometric login simulation
   - Demo credentials: demo/demo123

2. **Dashboard**
   - Account balance display
   - Quick actions (Transfer, Pay, Deposit, More)
   - Recent transactions list
   - Card management

3. **Money Transfer**
   - Contact selection
   - Amount input with validation
   - Real-time balance checking
   - Transaction confirmation

4. **Bill Payment**
   - Stripe integration mockup
   - Multiple payment methods
   - Saved payees
   - Scheduled payments

5. **Notifications**
   - Real-time push notifications
   - Transaction alerts
   - Security notifications
   - Promotional messages

6. **Profile/Settings**
   - Account management
   - Security settings
   - Notification preferences
   - App preferences

### Presenter View (presenter.html)
- Step-by-step demo script
- Timer for pacing
- Talking points for each feature
- Interactive step tracking
- Key points to emphasize

## 🎯 KEY TALKING POINTS FOR DEMOS

### Testing Capabilities Showcased
1. **Cross-Device Testing**: Works on iOS, Android, tablets, and desktop
2. **Real Device Testing**: Optimized for Sauce Labs Real Device Cloud
3. **Visual Testing**: UI consistency across devices
4. **Performance Testing**: Smooth animations and transitions
5. **Security Testing**: Login flows, biometric simulation
6. **Accessibility**: Screen reader support, WCAG compliance
7. **API Testing**: Simulated backend interactions

### Modern Banking Features
- Mobile-first responsive design
- Touch-optimized interface
- Native app-like experience (PWA ready)
- Real-time notifications
- Biometric authentication simulation
- Dark mode support (can be added)
- Offline capability (can be added)

## 🛠️ TECHNOLOGY STACK
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Variables, Flexbox, Grid, Animations
- **Icons**: Emoji-based (no external dependencies)
- **Responsive**: Mobile-first design (max-width: 428px for iPhone simulation)
- **Deployment**: GitHub Pages

## 🚀 HOW TO MAKE UPDATES

### Local Development
```bash
# You're already in the correct directory and branch
cd /Users/david.levine@saucelabs.com/sauce-banking-demo
git branch  # Should show * gh-pages

# Make your changes to files
# Test locally with:
python3 -m http.server 8000
# Or
npx http-server -p 8000

# View at: http://localhost:8000
```

### Deploying Updates
```bash
# After making changes:
git add .
git commit -m "Description of changes"
git push origin gh-pages

# Website updates automatically at:
# https://sauceseteam.github.io/sauce-banking-demo/
```

## 📱 TESTING ON DEVICES

### iOS Simulator (Xcode)
1. Open Xcode > Open Developer Tool > Simulator
2. In Simulator: Device > iOS > Choose device
3. Open Safari in simulator
4. Navigate to localhost:8000 or the GitHub Pages URL

### Real Devices (Sauce Labs)
1. Login to Sauce Labs
2. Go to Live > Web Testing
3. Enter URL: https://sauceseteam.github.io/sauce-banking-demo/
4. Select device and browser
5. Start session

### Browser Testing
- Chrome DevTools: Toggle device toolbar (Cmd+Shift+M)
- Safari: Develop > Enter Responsive Design Mode
- Firefox: Responsive Design Mode (Cmd+Option+M)

## 🎨 DESIGN SYSTEM

### Colors (CSS Variables)
- Primary: `#E2231A` (Sauce Labs Red)
- Secondary: `#2E2E2E` (Dark Gray)
- Success: `#4CAF50` (Green)
- Warning: `#FF9800` (Orange)
- Danger: `#F44336` (Red)
- Background: `#F5F5F5` (Light Gray)

### Typography
- Font: System fonts (-apple-system, BlinkMacSystemFont, etc.)
- Headers: Bold, varied sizes
- Body: Regular, 16px base

### Components
- Cards with shadows
- Rounded corners (12px standard)
- Smooth transitions (0.3s)
- Touch-friendly buttons (min 44px)

## 🔄 COMMON UPDATE REQUESTS

### To Add a New Feature:
1. Add HTML section in index.html
2. Add corresponding styles
3. Add JavaScript functionality
4. Update presenter.html with demo steps
5. Test on mobile viewport
6. Commit and push to gh-pages

### To Modify Existing Feature:
1. Locate the feature in index.html (search by screen ID or class)
2. Update HTML structure
3. Adjust styles if needed
4. Update JavaScript if interactive
5. Test thoroughly
6. Commit and push

### To Change Branding/Colors:
1. Update CSS variables in :root section
2. Replace logo/branding text
3. Update any hardcoded colors
4. Test full app flow
5. Commit and push

## 📝 IMPORTANT NOTES

1. **ALWAYS work on gh-pages branch** - this is what GitHub Pages uses
2. **Mobile-first**: Test primarily on mobile viewport (375-428px wide)
3. **No build process**: Direct HTML/CSS/JS - changes are immediate
4. **Keep it simple**: No frameworks needed, pure web technologies
5. **Accessibility matters**: Maintain ARIA labels and semantic HTML

## 🤖 AI ASSISTANT INSTRUCTIONS

When working on this project:
1. Check current branch is `gh-pages` before making changes
2. Understand this is a demo app for showcasing testing capabilities
3. Maintain the mobile-first, responsive design
4. Keep the Sauce Labs branding (red color scheme)
5. Ensure all features work without a backend (mock/simulate)
6. Test changes locally before committing
7. Provide clear commit messages
8. Remember this is for demos - make it impressive but realistic

## 📞 QUICK COMMANDS REFERENCE

```bash
# Check current state
git status
git branch

# Run local server
python3 -m http.server 8000

# Make changes and deploy
git add .
git commit -m "Update message"
git push origin gh-pages

# View live site
open https://sauceseteam.github.io/sauce-banking-demo/
```

---

**Last Updated**: December 2024
**Purpose**: Demo application for Sauce Labs testing capabilities
**Maintainer**: David Levine @ Sauce Labs
