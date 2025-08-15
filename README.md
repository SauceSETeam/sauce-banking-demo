# 🎬 Sauce Banking Demo

**Interactive demo for showcasing Sauce Labs testing capabilities with a modern banking application**

This repository contains an interactive HTML-based banking demo with a presenter view for sales demonstrations and presentations.

## 🚀 Quick Start

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

## 📱 Demo Flow

### Step 1: Login (30 seconds)
- Credentials are pre-filled: `demo_user` / `Test123!`
- Click **Sign In**
- Talk about JWT authentication, 2FA support, account lockout protection

### Step 2: Dashboard (45 seconds)
- Show account balances ($12,450 total)
- Switch between Checking and Savings accounts
- Point out real-time updates and transaction history

### Step 3: Money Transfer (45 seconds)
- Click **Transfer** button
- Amount is pre-filled ($500)
- Click **Transfer Now**
- Show success screen with receipt

### Step 4: Stripe Payment (30 seconds)
- Return to dashboard
- Click **Pay** button
- Discuss PCI-compliant payment processing

### Step 5: Advanced Features (30 seconds)
- Click **More** button
- Discuss wire transfers, bill pay, mobile deposit
- Show security notifications

## 🎯 Key Talking Points

### Why This App?
> "Unlike simple shopping cart demos, this banking application showcases enterprise-level complexity with real financial transactions, security requirements, and compliance needs."

### Security Focus
> "Multi-layered security: JWT authentication, account lockout, rate limiting, and transaction monitoring - all testable with Sauce Labs."

### Stripe Integration
> "Real payment processing demonstrates how Sauce Labs can test actual third-party integrations."

### Mobile-First Design
> "Responsive design automatically adapts from mobile to tablet to desktop - perfect for cross-device testing."

## 🎨 Features Demonstrated

- ✅ **Authentication Flow** - Secure login with validation
- ✅ **Account Management** - Multiple accounts with real-time balances
- ✅ **Money Transfers** - Complex validation and business logic
- ✅ **Payment Processing** - Stripe integration with 3D Secure
- ✅ **Notifications** - Real-time alerts and confirmations
- ✅ **Responsive Design** - Works on any device size
- ✅ **Security Features** - Rate limiting, encryption, secure sessions

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
