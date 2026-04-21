Usage:
1. Go to console.cloud.google.com and create a new project (name it anything)
2. Enable the YouTube API
3. In the search bar at the top search then enable "YouTube Data API v3"
4. Create the credential; Left sidebar → APIs & Services → Credentials, Click → Credentials → OAuth client ID. If it asks you to configure a consent screen first, click through it choose External, fill in just the app name, your email, and save
5. Back at Create OAuth client ID → Application type: Desktop app
6. Name it anything → click Create
7. Download the JSON (point to this file when script asks for client_secrets.json)

Verification Error:
1. Go to console.cloud.google.com
2. APIs & Services → OAuth consent screen
3. Find Test users → click + Add Users
4. Add your Gmail address
5. Click Save
