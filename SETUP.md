# Environment Variables Setup

## Required Environment Variables

### 1. Firebase Configuration
- `FIREBASE_PROJECT_ID`: Your Firebase project ID
- `FIREBASE_PRIVATE_KEY`: Private key from Firebase service account
- `FIREBASE_CLIENT_EMAIL`: Client email from Firebase service account

### 2. Payment Gateway (Razorpay)
- `RAZORPAY_KEY_ID`: Your Razorpay key ID
- `RAZORPAY_KEY_SECRET`: Your Razorpay key secret

### 3. Site Configuration
- `SITE_URL`: Your deployed site URL

## Setup Steps

### For Netlify Deployment:
1. Go to your Netlify dashboard
2. Navigate to Site settings > Environment variables
3. Add each variable from `.env.example`

### For Local Development:
1. Copy `.env.example` to `.env`
2. Fill in your actual values
3. Never commit `.env` to git

## Getting Firebase Credentials:
1. Go to Firebase Console
2. Project Settings > Service Accounts
3. Generate new private key
4. Use the values in your environment variables

## Getting Razorpay Credentials:
1. Sign up at https://razorpay.com
2. Go to Dashboard > API Keys
3. Generate Test/Live keys
4. Use in environment variables

## Payment Status:
✅ Payment processing is now configured with Razorpay
✅ Environment variables template created
✅ Security measures in place (.gitignore)