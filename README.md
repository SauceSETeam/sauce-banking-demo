# 🎬 Sauce Banking Demo

**Foundation banking application for testing on Sauce Labs devices**

🌐 **Live Demo:** https://sauceseteam.github.io/sauce-banking-demo/

This repository contains a foundation banking demo with core features that can be expanded. It includes both the mobile app and a presenter view for demonstrations.

## 🎯 Testing on Sauce Labs

### How to Test This Demo:

1. **Go to Sauce Labs Web Testing**
   - Navigate to: https://app.saucelabs.com/live/web-testing
   - Select your desired device (iPhone, Android, etc.)

2. **Enter the Demo URL**
   - URL: `https://sauceseteam.github.io/sauce-banking-demo/`
   - Press Enter or click Go

3. **Test the Application**
   - Login: `demo_user` / `Test123!`
   - Try the transfer feature
   - Navigate through bottom menu
   - Test on different devices and orientations

## 🚀 Quick Start (Local Development)

### Option 1: Open directly in browser
```bash
# Open the banking app
open index.html

# Open the presenter view (in a separate window)
open presenter.html
```

### Option 2: Run with local server
```bash
# Start a simple web server
python3 -m http.server 8080

# Open http://localhost:8080 in your browser
```

### Option 3: Open in iOS Simulator
```bash
# Start iOS Simulator
open -a Simulator

# In Safari on the simulator, navigate to:
# http://localhost:8080 (if using server)
# Or drag and drop index.html into Safari
```

## 📱 Current Functionality (Foundation Version)

### Working Features:

1. **Login Screen**
   - Username: `demo_user`
   - Password: `Test123!`
   - Click "Sign In" to access dashboard

2. **Dashboard**
   - View total balance ($12,450.32)
   - Switch between Checking and Savings accounts (click account pills at top)
   - View recent transactions list

3. **Money Transfer**
   - Click "Transfer" quick action button
   - Select From account (Checking/Savings)
   - Select To account (Checking/Savings)
   - Enter amount (e.g., 100)
   - Click "Transfer Now"
   - See success toast notification

4. **Bottom Navigation**
   - Home: Returns to dashboard
   - Accounts: Shows account details
   - Cards: Card management view
   - Payments: Payment options
   - More: Additional options

5. **Modal Popups**
   - Payment, Deposit, and More options show modal dialogs
   - Currently display placeholder content
   - Foundation for future functionality

### 🔴 Note on Limited Functionality:
This is a foundation demo. Advanced features like bill pay, check deposit, and detailed payment processing are not yet fully implemented but can be added as needed.

## 🎯 Key Talking Points

### Why This App?
> "Unlike simple shopping cart demos, this banking application showcases enterprise-level complexity with real financial transactions, security requirements, and compliance needs."

### Security Focus
> "Multi-layered security: JWT authentication, account lockout, rate limiting, and transaction monitoring - all testable with Sauce Labs."

### Stripe Integration
> "Real payment processing demonstrates how Sauce Labs can test actual third-party integrations."

### Mobile-First Design
> "Responsive design automatically adapts from mobile to tablet to desktop - perfect for cross-device testing."

## 🎨 What's Currently Implemented

### ✅ Working Features:
- **Authentication** - Login screen with demo credentials
- **Account Display** - Checking and Savings account balances
- **Money Transfer** - Transfer between accounts with validation
- **Transaction History** - List of recent transactions
- **Toast Notifications** - Success/error feedback
- **Responsive Design** - Optimized for mobile devices
- **Navigation** - Bottom tab navigation system

### 🔶 Foundation Elements (Ready for Expansion):
- **Payment Modal** - Structure in place, needs implementation
- **Deposit Modal** - Structure in place, needs implementation  
- **Cards Section** - Navigation works, content needed
- **More Options** - Menu structure ready for features

## 📹 Recording Tips

1. Position windows side-by-side (app left, presenter right)
2. Use presenter view timer to pace yourself
3. Follow the numbered steps in presenter view
4. Keep demo under 5 minutes total
5. Use cursor to highlight features

## 🔧 Customization

To modify the demo:
- Edit `index.html` for app changes
- Edit `presenter.html` for talking points
- All interactions are simulated (no backend required)

## 📋 Presenter View Features

- **Step-by-step script** with talking points
- **Timer** to track demo duration
- **Progress bar** showing completion
- **Key differentiators** highlighted
- **Tech stack** display
- **Keyboard shortcuts**:
  - Arrow keys: Navigate steps
  - Spacebar: Play/pause timer

## 🌐 Browser Compatibility

Works on:
- Chrome, Safari, Firefox, Edge
- iOS Safari (iPhone/iPad)
- Android Chrome
- All modern browsers

## 📞 Support

This demo is part of the Sauce Labs SE Team toolkit. For updates or questions, contact the SE team.

---

**Note**: This is a demonstration interface. All data is simulated for demo purposes.
