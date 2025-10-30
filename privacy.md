# Privacy Policy for Clarity Events AI

**Last Updated:** October 30, 2025

## Introduction

Clarity Events AI ("we," "our," or "the app") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and protect your personal information when you use our mobile application.

## Information We Collect

### 1. Information You Provide
- **Text and Images**: When you use our AI-powered event extraction feature, you provide text or images containing event information. This data is processed to extract calendar events and reminders.
- **Calendar and Reminder Data**: When you save extracted events, we access your device's Calendar and Reminders apps (Apple) or Google Calendar and Google Tasks (if you choose Google integration) with your permission.
- **Google Account Information**: If you choose to use Google Calendar integration, we collect your email address through Google Sign-In to access your Google Calendar and Tasks.

### 2. Automatically Collected Information
- **Subscription Information**: We collect information about your subscription status through RevenueCat to manage your Pro subscription.
- **Usage Data**: We track the number of queries you make to manage your free trial limits (25 queries, 7 days).

## How We Use Your Information

We use your information to:
- Process your text and images to extract events and reminders using AI (OpenAI GPT or Google Gemini, based on your choice)
- Manage your free trial and Pro subscription
- Save events and reminders to your device's Calendar and Reminders apps (Apple) or Google Calendar and Google Tasks (Google integration)
- Authenticate your Google account if you choose Google integration
- Provide customer support

## Third-Party Services

### OpenAI
We use OpenAI's GPT API to analyze your text and images. Your data is sent to OpenAI for processing. OpenAI's data handling practices are governed by their Data Processing Addendum (DPA):
- **OpenAI DPA**: https://openai.com/enterprise-privacy
- **OpenAI Privacy Policy**: https://openai.com/privacy

**Important**: OpenAI does not use data submitted via their API to train their models. Your data is processed and then deleted according to OpenAI's data retention policy.

### Google Services
If you choose to use Google integration, we use the following Google services:

**Google Gemini API** (Alternative AI provider):
- Processes your text and images to extract events and reminders when using Google mode
- Google AI usage policies: https://ai.google.dev/gemini-api/terms
- Google Cloud Privacy Notice: https://cloud.google.com/terms/cloud-privacy-notice

**Google Calendar API and Google Tasks API**:
- Allows you to save events to Google Calendar and tasks to Google Tasks
- Required OAuth scopes:
  - `calendar` (Read/write access to Google Calendar)
  - `tasks` (Read/write access to Google Tasks)
  - `userinfo.email` (Your email for authentication)
- Google APIs Terms: https://developers.google.com/terms
- Google Privacy Policy: https://policies.google.com/privacy

**Google Sign-In**:
- Authenticates your Google account
- We only receive your email address and access tokens
- Google OAuth Privacy: https://developers.google.com/identity/protocols/oauth2

**Note**: In Google mode, AI processing switches from OpenAI GPT to Google Gemini. Switch back to Apple mode anytime in Settings.

### Supabase (Infrastructure)
We use Supabase Edge Functions as a secure proxy for AI API requests:
- Routes requests to OpenAI GPT or Google Gemini
- Stores API keys securely on server (not on your device)
- All communications use HTTPS encryption
- Supabase Privacy Policy: https://supabase.com/privacy
- No user data is stored on Supabase

### RevenueCat
We use RevenueCat to manage in-app subscriptions. RevenueCat processes your purchase information and subscription status:
- **RevenueCat Privacy Policy**: https://www.revenuecat.com/privacy
- **RevenueCat DPA**: https://www.revenuecat.com/dpa

## Data Storage and Retention

- **Local Storage**: Events, reminders, and analysis history are stored locally on your device. We do not store this data on our servers.
- **AI Processing**:
  - Text and images sent to OpenAI (Apple mode) or Google Gemini (Google mode) are processed in real-time
  - OpenAI: Deleted according to their data retention policy (typically within 30 days)
  - Google Gemini: Processed according to Google's AI data handling policies
- **Google Calendar/Tasks**: If you use Google integration, events and tasks are stored in your Google account
- **Supabase**: No user data is stored; only acts as a secure proxy for API requests
- **RevenueCat**: Subscription data is retained by RevenueCat for the duration of your subscription and as required by law

## Your Rights Under GDPR

If you are in the European Economic Area (EEA), you have the following rights:

1. **Right to Access**: You can request a copy of your personal data.
2. **Right to Deletion**: You can request deletion of your personal data by uninstalling the app.
3. **Right to Rectification**: You can correct inaccurate data directly in the app.
4. **Right to Data Portability**: You can export your calendar events and reminders from your device.
5. **Right to Object**: You can object to data processing by not using certain features.
6. **Right to Restrict Processing**: You can limit how we process your data.

## Data Security

We implement industry-standard security measures:
- All communications with OpenAI, Google, and Supabase use HTTPS encryption
- API keys are stored securely on Supabase server (not on your device)
- Google OAuth tokens are stored securely using iOS Keychain
- No user data is stored on our servers
- RevenueCat uses secure payment processing

## Children's Privacy

Clarity Events AI is not directed to children under 13 years of age. We do not knowingly collect personal information from children under 13.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by updating the "Last Updated" date at the top of this policy.

## Contact Us

If you have questions about this Privacy Policy or want to exercise your GDPR rights, please contact us:

**Email**: kettunen.miika@gmail.com

## Data Processing Addendum (DPA)

For enterprise customers or users requiring a formal DPA, please contact us at the email address above.

## Summary

- ✅ We process your data locally and via AI APIs (OpenAI GPT or Google Gemini, based on your choice)
- ✅ We do NOT store your calendar data on our servers
- ✅ We do NOT sell your data to third parties
- ✅ You can delete all your data by uninstalling the app and disconnecting Google (if used)
- ✅ OpenAI and Google do NOT use your API data to train their models
- ✅ You have full GDPR rights to access, delete, and port your data
- ✅ You control which services you use: Apple-only mode or Google integration
