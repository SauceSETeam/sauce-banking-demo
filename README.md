## 🎬 Sauce Banking Demo

**Interactive demo for showcasing Sauce Labs testing capabilities with a modern banking application**

This repository contains a comprehensive, mobile-first HTML-based banking demo that simulates a full-featured banking experience similar to major banks like Wells Fargo, TD, and Chase. Perfect for demonstrating Sauce Labs testing capabilities on real devices.

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

### Quick Demo (2-3 minutes)
1. **Login** - Use biometric login or demo/demo123 credentials
2. **Dashboard** - Show account balances, switch between accounts
3. **Transfer Money** - Quick P2P transfer or Zelle payment
4. **Mobile Deposit** - Demonstrate check capture simulation
5. **View Features** - Quick tour of cards, investments, budgeting

### Comprehensive Demo (5-7 minutes)

#### Authentication & Security (1 minute)
- Show biometric login options (Face ID/Touch ID)
- Use credentials: `demo` / `demo123`
- Mention 2FA options and security features
- Point out session management and timeout policies

#### Account Overview (1 minute)
- Navigate dashboard showing all accounts
- Switch between Checking ($8,450), Savings ($4,000), Credit accounts
- Show recent transactions with merchant logos
- Demonstrate quick balance view and account details

#### Transfers & Payments (1.5 minutes)
- **P2P Transfer**: Send money to a contact
- **Zelle Integration**: Instant transfers with email/phone
- **Wire Transfer**: For larger amounts with verification
- **Bill Pay**: Schedule and manage recurring payments
- Show success confirmations with transaction IDs

#### Mobile Check Deposit (1 minute)
- Click "Deposit Check" from dashboard
- Show camera simulation for front/back capture
- Demonstrate amount verification and confirmation
- Explain hold policies and availability

#### Cards & Credit (1 minute)
- View credit cards with balances and limits
- Show rewards points and cashback
- Demonstrate card controls (freeze/unfreeze)
- Virtual card numbers for online shopping

#### Investments & Planning (30 seconds)
- Portfolio overview with holdings
- Performance charts and gains/losses
- Trade simulation capabilities
- Financial wellness score

#### Advanced Features (1 minute)
- **QR Payments**: Scan to pay or receive
- **ATM Locator**: Find nearby locations
- **Budgeting**: Spending categories and limits
- **Credit Score**: View score and factors
- **Settings**: Security, privacy, notifications

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

### Core Banking Features
- ✅ **Authentication Flow** - Secure login with biometric simulation (Face ID/Touch ID)
- ✅ **Account Management** - Multiple accounts (Checking, Savings, Credit) with real-time balances
- ✅ **Money Transfers** - P2P transfers, Zelle integration, wire transfers
- ✅ **Bill Payment** - Schedule payments, manage payees, payment history
- ✅ **Mobile Check Deposit** - Camera simulation for front/back check capture
- ✅ **ATM/Branch Locator** - Find nearby ATMs and branches with map view

### Advanced Features
- ✅ **Credit Cards** - View cards, manage limits, track rewards, virtual card numbers
- ✅ **Investment Portfolio** - Stock holdings, performance charts, trade simulation
- ✅ **Budgeting Tools** - Spending categories, monthly budgets, financial wellness
- ✅ **QR Code Payments** - Scan to pay and receive money via QR codes
- ✅ **Transaction History** - Search, filter, categorize, and export transactions
- ✅ **Credit Score** - View score, factors, and improvement tips

### Security & Settings
- ✅ **Multi-Factor Authentication** - SMS, Email, and Authenticator app options
- ✅ **Biometric Login** - Face ID and Touch ID simulation
- ✅ **Security Settings** - Password management, security questions, login history
- ✅ **Privacy Controls** - Data sharing preferences, account visibility
- ✅ **Notifications** - Push, SMS, and email preference management
- ✅ **Dark Mode** - System-aware theme switching with persistence

### User Experience
- ✅ **Responsive Design** - Optimized for mobile, tablet, and desktop
- ✅ **Toast Notifications** - Real-time feedback for all actions
- ✅ **Bottom Navigation** - Easy access to main features
- ✅ **Progressive Disclosure** - Clean UI with expandable sections
- ✅ **Accessibility** - ARIA labels, semantic HTML, keyboard navigation

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

## 🧪 Testing with Sauce Labs

### Live Testing
1. Log into your Sauce Labs account
2. Navigate to **Live Testing** > **Cross Browser**
3. Enter URL: `https://sauceseteam.github.io/sauce-banking-demo/`
4. Select your desired device/browser combination
5. Start your interactive testing session

### Automated Testing
This demo app is perfect for showcasing:
- **Selenium/WebDriver** tests for functional validation
- **Appium** tests for mobile device testing
- **Visual Testing** to catch UI regressions
- **Performance Testing** to measure load times
- **Accessibility Testing** for WCAG compliance

### Test Scenarios to Demo
- Login flow with different credentials
- Account balance verification across devices
- Transfer money workflow end-to-end
- Mobile check deposit on real devices
- Credit card management actions
- Responsive design breakpoints
- Dark mode toggle persistence
- Form validation and error handling

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
