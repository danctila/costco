# Costco Employee Portal - Social Engineering Demonstration

## ⚠️ EDUCATIONAL PURPOSE ONLY ⚠️

This project is created **SOLELY FOR EDUCATIONAL PURPOSES** as part of a cybersecurity class assignment. This is a **MOCK SOCIAL ENGINEERING DEMONSTRATION** and is not intended for any malicious use.

## Project Overview

This is a multi-page social engineering simulation that demonstrates how attackers might create convincing phishing sites that target employees of legitimate companies. The demonstration shows how social engineering attacks can be used to:

- Capture login credentials
- Collect sensitive personal information
- Obtain banking details through fake verification processes
- Use professional branding to increase credibility

## File Structure

```
/
├── index.html                   # Main login page (identical to real Costco styling)
├── verification-intro.html      # Congratulatory message and process overview
├── badge-verification.html      # Photo upload page for employee badges
├── account-verification.html    # Form for collecting sensitive financial data
├── confirmation.html            # Final success page with 24-hour update message
├── costco_logo.png              # Official Costco logo
└── README.md
```

## Flow Description

1. **Login Page** - Mimics the real Costco employee login form
2. **Verification Intro** - Congratulates on promotion and explains verification steps
3. **Badge Verification** - Requests photos of employee badge (front/back)
4. **Account Details** - Collects sensitive information (SSN, banking details, etc.)
5. **Confirmation** - Thanks user and states "updates will take effect within 24 hours"

## Key Features

- **Professional Branding**: Matches Costco's visual identity exactly
- **Progress Indicator**: Shows users their progress through the verification
- **Form Validation**: Includes realistic validation and formatting
- **Mobile Responsive**: Works on all device sizes
- **Console Logging**: Demonstrates what data would be captured (for educational review)

## Technical Implementation

- **Pure HTML/CSS/JS**: No external dependencies
- **Client-Side Only**: No backend
- **Form Capture**: Uses JavaScript to log form submissions in dev console (educational purposes)
- **Responsive Design**: Mobile-friendly layout
- **Cross-Browser Compatible**: Works in all modern browsers

---

**Disclaimer**: This is a mock demonstration created for educational purposes only. No real data is collected or transmitted. This project is intended to help understand social engineering tactics for defensive purposes.
