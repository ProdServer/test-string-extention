# Text String Generator Chrome Extension

## 🛒 Install from Chrome Web Store

The extension is now available on the Chrome Web Store! [**Install it directly from here**](<https://chromewebstore.google.com/detail/test-string-generator/dncchfcbdengdgodhbjmakoaiildjigl?authuser=0&hl=tr>)

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/dncchfcbdengdgodhbjmakoaiildjigl?style=for-the-badge&logo=google-chrome)](<https://chromewebstore.google.com/detail/test-string-generator/dncchfcbdengdgodhbjmakoaiildjigl?authuser=0&hl=tr>)

> **Recommended:** For the easiest and most up-to-date experience, install via the Chrome Web Store link above.

## 🚀 Stable Release

For the most stable and fully tested version, [**download the latest release here**](https://github.com/sevilayerkan/test-string-extention/releases/tag/1.0.1).

> **Note:** The `main` branch is pre-production and may include features under development. For production use, always prefer the latest release above.

## Project Details

Text String Generator is a powerful and versatile Chrome browser extension designed to assist developers and testers by generating customizable test text data. Whether you need specific-length strings, Lorem Ipsum text, or randomized data, this tool is designed with simplicity and efficiency in mind. 

With the latest update, the extension includes a modernized, tabbed interface for seamless navigation, Dark Mode support, and a **Miscellaneous** section for generating Turkish names, addresses, and passwords. Optimized for security and memory usage, this extension ensures smooth performance without compromising functionality.

Once installed, the extension works completely offline, allowing users to continue using all features without an active internet connection.

> For quick demo please click here
<img src="https://github.com/user-attachments/assets/cdfbb4df-f148-4ab2-bc51-e5199f01368a" width="250" height="350"/>

## Installation

### Preferred: Install from Chrome Web Store

1. Go to the [Chrome Web Store listing](<CHROME_WEB_STORE_URL_PLACEHOLDER>).
2. Click "Add to Chrome" and follow the prompts.
3. The extension icon will appear in your Chrome toolbar after installation.

### Manual Installation (for development or advanced users):

1- Download the Extension Files:

- Download the HTML, CSS, JS, and manifest.json files from this repository.
- If you want to use fully stable version please download files from release - add link  https://github.com/sevilayerkan/test-string-extention/releases/tag/v0.2.0-alpha

2- Set Up the Extension:

- Create a new folder on your computer to store the extension files.
- Place the downloaded HTML, CSS, JS, and manifest.json files into the folder.

3- Load the Extension in Chrome:

- Open Google Chrome and navigate to chrome://extensions/.
- Enable "Developer mode" in the top right corner of the page.

4- Load Unpacked Extension:

- Click on the "Load unpacked" button.
- Select the folder where you saved the extension files.
- Test the Extension:

5- After loading the extension, you should see the extension icon in your Chrome toolbar.

## Usage

### Text Generation

1. Click on the extension icon to open the popup.
2. Select your desired text generation type:
   - **Lorem Ipsum**: Traditional placeholder text
   - **Alphanumerical**: Letters and numbers only (abc123)
   - **With Special Characters**: Includes symbols (,()%/+?*...)
   - **Turkish/German Letters**: Includes international characters (ö,ç,ş,ü...)
3. Enter the desired text length for generation (1-999,999 characters).
4. For Lorem Ipsum, use additional options:
   - **Remove Punctuation**: Exclude punctuation marks from the generated text.
   - **Remove Spaces**: Remove spaces between words.
5. Click "Generate Text" to create the customized text.
6. Copy the generated text to the clipboard using the "Copy to Clipboard" button.

### Additional Features

7. Use the **Character Counter** tab to see the real-time length of any text.
8. Navigate to the **Miscellaneous** tab for additional tools:
   - Generate **Turkish Names** for use in test scenarios.
   - Generate **Email Addresses** for use in test scenarios.
   - Create **Turkish Addresses** for testing localization.
   - Generate secure **Passwords** for test accounts or other needs.

### Testing

The extension includes comprehensive testing features:
- Open `test-all.html` for the complete test suite
- Open `test-generation.html` for manual testing
- Run `npm test` from command line

## Honorable Mentions

Special thanks to my friend’s repository for its inspiration and usage: 

- [Custom Turkish Data Generator](https://github.com/tw4/responserun-mock)

## Features

### Text Generation Types

- **Lorem Ipsum** - Traditional placeholder text with customizable options
  - Remove punctuation option
  - Remove spaces option

- **Alphanumerical (abc123)** - Random combination of letters and numbers
  - No spaces included
  - Perfect for testing IDs, codes, usernames

- **With Special Characters (,()%/+?*...)** - Text including special symbols
  - Includes letters, numbers, and special characters
  - Useful for testing form validation, security

- **Turkish/German Letters (ö,ç,ş,ü...)** - Text with international characters
  - Turkish characters: ç, ğ, ı, ö, ş, ü, Ç, Ğ, I, Ö, Ş, Ü
  - German characters: ä, ö, ü, ß, Ä, Ö, Ü
  - Perfect for internationalization testing

### General Features

- **Modernized UI**: Redesigned with a sleek, scalable, and responsive interface.
- **Tabbed Navigation**: Added a tabbed layout for better organization of features.
- **Miscellaneous Tools Section**: Room for future expansions and added utilities. For now it supports Turkish name, address, email, and password generation.
- **Dark Mode Support** (Upcoming): Switch between light and dark modes for a better user experience. 
- **Character Counter**: Real-time character counter to track text length dynamically.
- **Random Text Generation**: Generate customizable random strings with options for uppercase letters, numbers, and symbols.
- **Comprehensive Testing**: Includes extensive test suite for reliability
- **Offline Functionality**: Full functionality without requiring an internet or AI connection.

## Support

If you like this project and want to support its development, you can **[Buy Me a Coffee](https://buymeacoffee.com/notdepressedeveloper)**. Your support helps keep this project going and motivates me to build more awesome tools!

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Support-yellow?style=for-the-badge&logo=buy-me-a-coffee)](https://buymeacoffee.com/notdepressedeveloper)

## 🧪 Tested Platforms

- **Google Chrome:** Version 138.0.7204.101 (arm64)
- **Opera One:** Version 120.0.5543.61 (arm64)
  - Chromium version: 135.0.7049.115

## Contributing and Contact

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to:

- Open an issue or pull request in this repository.
- Reach out to me via the contact information provided in my profile.
- Contact me directly on Discord: **notdepressedeveloper**.

Thank you for your support and feedback!
