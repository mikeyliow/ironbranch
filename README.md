# Chat Interface

A simple web-based chat interface that connects to a Railway.app backend.

## Quick Start

### Local Development
1. Simply open `index.html` in your web browser
   - Double-click the file
   - Or drag it into your browser window

### Required Fields
- User ID: Your unique identifier (default: 0167668686)
- Username: Your authentication username
- Password: Your authentication password

## Deployment Options

### 1. GitHub Pages (Free)
1. Create a new GitHub repository
2. Push the `index.html` file to the repository
3. Go to repository Settings > Pages
4. Enable GitHub Pages
5. Your site will be available at `https://[username].github.io/[repository-name]`

### 2. Netlify (Free)
1. Create a Netlify account
2. Go to [Netlify Drop](https://app.netlify.com/drop)
3. Drag and drop the `index.html` file
4. Get your site URL instantly

### 3. Vercel (Free)
1. Create a Vercel account
2. Install Vercel CLI: `npm i -g vercel`
3. Run `vercel` in the project directory
4. Follow the prompts to deploy

### 4. Firebase Hosting (Free)
1. Create a Firebase project
2. Install Firebase CLI: `npm install -g firebase-tools`
3. Run `firebase init`
4. Run `firebase deploy`

## Backend Connection
The chat interface connects to:
```
https://heir8oom-willy-production.up.railway.app/chat
```

## Notes
- Make sure you have valid credentials (username/password) before using the chat
- The interface uses Basic Authentication
- All messages are sent over HTTPS 