# Privacy Policy for TrendRadar

**Last Updated: February 24, 2026**

## Overview

TrendRadar is a browser extension that detects emerging content trends while you browse Reddit and Twitter/X. This privacy policy explains how TrendRadar handles your data.

## Data Collection

### Data Stored Locally (On Your Device)

TrendRadar stores the following data locally in your browser using IndexedDB:

- **Content Signals**: Titles, engagement metrics (upvotes, comments, shares), and timestamps of posts you encounter while browsing supported platforms.
- **Trend Analysis Results**: AI-generated trend summaries and analysis data.
- **Settings & Preferences**: Your configuration choices, including AI provider settings.

This data never leaves your device unless you explicitly enable the Community Features described below.

### AI API Keys

If you configure AI-powered trend analysis, your API keys (for Claude, OpenAI, Gemini, or DeepSeek) are stored locally in your browser's storage. These keys are only used to communicate directly with the respective AI provider's API and are never sent to our servers.

### Community Features (Optional)

When enabled, TrendRadar can share **anonymized** signal data with our community backend:

- Signals are anonymized using SHA-256 hashing before upload.
- No personally identifiable information is collected or transmitted.
- A randomly generated device ID is used for rate limiting purposes only.
- Community data is automatically deleted after 7 days (signals) or 30 days (aggregated trends).

You can disable community features at any time in the extension settings.

## Data We Do NOT Collect

- Personal information (name, email, address)
- Browsing history beyond the supported platforms
- Login credentials or session tokens
- Private messages or direct messages
- Content of posts you author

## Third-Party Services

TrendRadar may communicate with the following third-party services based on your configuration:

- **AI Providers** (Anthropic, OpenAI, Google, DeepSeek): Only when you configure and enable AI analysis, using your own API keys.
- **Community Backend** (Azure Cloud): Only when community features are enabled, transmitting anonymized data.

## Data Retention

- **Local Data**: Stored indefinitely until you clear extension data or uninstall the extension.
- **Community Signals**: Automatically deleted after 7 days.
- **Community Trends**: Automatically deleted after 30 days.

## Your Rights

- You can disable community features at any time.
- You can clear all local data by removing the extension.
- You can view all stored data through the extension's dashboard.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last Updated" date above.

## Contact

For questions about this privacy policy, please open an issue at:
https://github.com/gavinmandias/TrendRadarPlugin/issues
