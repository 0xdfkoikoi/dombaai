# dombaai
wisata domba ai assistant 
domba
domba is your virtual ai assistant for your web powered by gemini using gemini js sdk and gemini API

AI-Powered Website

Setup Instructions
1. Get Your Gemini API Key
Visit Google AI Studio
Sign in with your Google account
Create a new API key
Copy the API key
2. Configure the API Key
Open config.js in your project
Replace 'YOUR_API_KEY_HERE' with your actual API key:
const CONFIG = {
    GEMINI_API_KEY: 'your-actual-api-key-here',
    // ... other config
};
3. Deploy to GitHub Pages
Create a new repository on GitHub
Upload all project files to the repository
Go to repository Settings → Pages
Select "GitHub Actions" as the source
The website will be automatically deployed when you push to the main branch
File Structure
├── index.html          # Main website file
├── config.js           # Configuration file (API keys, cafe info)
├── metadata.json       # Website metadata
├── cookbook.json       # Gemini cookbook reference
├── .github/
│   └── workflows/
│       └── deploy.yml  # GitHub Pages deployment workflow
└── README.md          # This file
Customization
Cafe Information
Edit the CONFIG object in config.js to customize:

Cafe name and description
Contact information (WhatsApp, Instagram)
Operating hours
Menu items
AI assistant behavior
Styling
The website uses CSS with glassmorphism effects. You can customize:

Colors and themes
Fonts and typography
Layout and spacing
Animations and transitions
AI Assistant Features
The AI assistant is specifically trained for Wisdom Cafe and can help with:

Menu inquiries
Coffee recommendations
Reservation information
Operating hours
General cafe information
Browser Support
Chrome (recommended)
Firefox
Safari
Edge
Security Notes
Never commit your actual API key to version control
Use environment variables for production deployments
The API key is client-side, so consider rate limiting for production use
Support
For issues or questions:

Check the browser console for error messages
Verify your API key is correct
Ensure you have internet connectivity
Check GitHub Pages deployment status
License
This project is open source and available under the MIT License.
