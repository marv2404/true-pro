# TruePro Investments - Complete Setup Guide

## 📁 File Structure



## 🔐 Default Admin Login
- **Email:** admin@trueproinvestments.com
- **Password:** admin123

**⚠️ CHANGE THESE CREDENTIALS IMMEDIATELY AFTER SETUP!**

## 🚀 Hostinger Setup Steps

### Step 1: Purchase Domain & Hosting
1. Go to Hostinger.com
2. Choose Premium or Business plan
3. Register domain: trueproinvestments.com

### Step 2: Upload Files to Hostinger
1. Login to Hostinger hPanel
2. Go to File Manager → public_html folder
3. Upload all HTML files to root directory
4. Create `css` folder and upload style.css
5. Create `js` folder and upload all JavaScript files

### Step 3: Set Up Professional Email
1. In Hostinger panel, go to "Emails"
2. Create these email addresses:
   - admin@trueproinvestments.com
   - support@trueproinvestments.com  
   - info@trueproinvestments.com
3. Access webmail at: webmail.hostinger.com

### Step 4: Enable SSL Certificate
1. In Hostinger panel, go to "SSL"
2. Enable free SSL certificate
3. Your site will now use HTTPS

### Step 5: Configure Smartsupp Live Chat
1. Go to https://www.smartsupp.com
2. Create free account and verify email
3. Get your unique chat key from dashboard
4. Edit `js/smartsupp.js` and replace:
   `YOUR_SMARTSUPP_KEY_HERE` with your actual key

## 🛠️ Features Included

### User Management
- User registration and login
- Account plan selection
- Balance tracking
- Transaction history

### Admin Panel Features
- View all registered users
- Add/deduct user balances
- Approve/decline deposits & withdrawals
- Payment methods management
- Financial statistics
- Export user data to CSV

### Payment Methods
- Bank transfer details
- Cryptocurrency wallets
- Custom payment methods
- Active/inactive status control

## 📊 Admin Panel Tabs

1. **User Management** - View and manage all users
2. **Pending Transactions** - Approve/decline deposits & withdrawals  
3. **Payment Methods** - Add/edit payment options
4. **Financial Tools** - Balance adjustments and reporting

## 🔒 Security Notes

- All data stored in browser localStorage
- For production, implement server-side storage
- Change default admin credentials immediately
- Regular backups recommended
- Monitor transaction approvals

## 🆘 Troubleshooting

**Website Not Loading?**
- Check files are in public_html folder
- Clear browser cache
- Verify domain propagation (24-48 hours)

**Admin Panel Access Denied?**
- Use correct admin credentials
- Check JavaScript console for errors
- Verify all JS files uploaded

**Live Chat Not Working?**
- Verify Smartsupp key is correct
- Check Smartsupp account is active
- Test on different browsers

## 📞 Support
For technical issues, contact: support@trueproinvestments.com

---
**TruePro Investments** © 2024 - Professional Trading Platform