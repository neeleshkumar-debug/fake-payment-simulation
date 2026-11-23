# NSS Cyber Safety — Fake UPI Payment Awareness Demo

A single-file, mobile-first educational web app to demonstrate how fraudsters use **fake UPI payment success screens** to cheat shopkeepers.

## 📁 Files
| File | Purpose |
|------|---------|
| `index.html` | Entire app (HTML + CSS + JS, zero dependencies) |
| `vercel.json` | Static-site config for instant Vercel deployment |

## 🚀 Deploy on Vercel (< 2 minutes)
1. Install Vercel CLI: `npm i -g vercel`
2. From this folder: `vercel --prod`
3. Open the URL on your phone — done!

**Or** drag this folder into [vercel.com/new](https://vercel.com/new) for a GUI deploy.

## 📱 User Flow
1. **Setup Screen** → Enter merchant name, UPI ID, amount, optional sound
2. **Processing Screen** → 900 ms PhonePe-style purple loading
3. **Success Screen** → Animated checkmark, chime + haptic, full receipt layout
4. **Tap the ✓ circle or "View Details"** → Instant red "FAKE PAYMENT DEMO!" reveal with bilingual warning

## ⚠️ Disclaimer
For **educational/demonstration purposes only**. No real money is transferred at any point.
