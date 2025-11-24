# Privacy Policy for In-Context Dictionary

**Last Updated:** November 23, 2025

## Introduction
In-Context Dictionary ("we", "our", or "us") respects your privacy. This Privacy Policy explains what data we collect, how we use it, and your rights regarding your information when you use our Chrome extension.

## Data Collection and Usage

### 1. User-Selected Text and Context
*   **What we collect:** When you explicitly interact with the extension (by clicking the lookup icon), we temporarily capture the specific text you have selected and the surrounding paragraph (context) from the active web page.
*   **How we use it:** This data is transmitted securely to our backend (hosted on Google Cloud Platform) and then to Google's Gemini API. The sole purpose of this processing is to generate a context-aware definition of the selected word.
*   **Retention:** We do **not** store, log, or share your selected text or context. The data is processed transiently and discarded immediately after the definition is returned to you.

### 2. Language Preferences
*   **What we collect:** We store your preferred output language (e.g., English, Chinese, Japanese).
*   **How we use it:** This preference is stored locally in your browser using Chrome's `storage` API. It is used solely to display definitions in your chosen language.
*   **Retention:** This data remains on your device until you uninstall the extension or clear your browsing data. We do not have access to this data.

## Third-Party Services
We use the following third-party services to provide the extension's functionality:
*   **Google Cloud Platform:** Hosts our serverless backend functions. [Google Cloud Privacy Notice](https://cloud.google.com/terms/cloud-privacy-notice)
*   **Google Gemini API:** Provides the AI-powered definitions. [Google Privacy Policy](https://policies.google.com/privacy)

## Permissions
The extension requests the following permissions for specific purposes:
*   **`storage`**: To save your language preferences locally.
*   **Host Permissions**: To communicate securely with our backend API for core functionality.

## Data Security
We implement appropriate technical measures to protect your data during transmission. All communication between the extension, our backend, and the Gemini API occurs over encrypted HTTPS connections.

## Changes to This Policy
We may update this Privacy Policy from time to time. We will notify you of any significant changes by updating the "Last Updated" date at the top of this policy.
