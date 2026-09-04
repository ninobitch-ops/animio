ANIMIO-STRIMER
ANIMIO-STRIMER is a feature-rich, single-page web application designed for streaming and downloading movies, music, TV shows, dramas, anime, and live sports events like football matches. It offers resolution-based video downloads, bitrate-customized audio downloads, multi-cloud storage integration, a PIN-protected private vault, and deep application preferences.

Key Features
Authentication Gateway: Forced login/sign-in modal before entry to secure user access.

Home Page Dashboard: Showcases featured matches of the day, new movie releases, and trending music tracks.

In-App Video Streaming: Integrated modal player capable of streaming public MP4 files directly within the application.

Custom Download Engine:

Video Resolution Options: 1080p, 720p, 480p, 360p.

Audio Bitrate Options: 320 kbps, 256 kbps, 128 kbps, 64 kbps.

Target Destinations: Local Device Storage, Google Drive, or Dropbox.

Live Sports & Football: Dedicated live video streams, external channel links (FIFA+, Sky Sports), and game highlights.

Private Vault: Secure section locked behind PIN authentication with + file addition controls.

Connected Stores Manager: Link external cloud platforms (Google Drive, Dropbox, OneDrive) to sync local and cloud downloads.

P2P & Cloud Sharing: Instant modal to copy links or dispatch files to connected stores.

Advanced Settings Suite:

Profile management.

Smart Muxer toggle (optimizes speed & storage usage).

Auto-resume & Download Complete notifications.

Clipboard link detection trigger.

Wi-Fi only download restriction.

Direct .apk download via auto-generated QR code.

File Structure
Plaintext
├── index.html         # Main standalone HTML file containing structure, styling, and JS logic
└── README.md          # Project documentation
Dependencies & CDNs Used
The project runs directly in the browser using the following CDN links (no npm install required):

Tailwind CSS (v3.x): Dynamic utility-first UI styling.

Font Awesome (v6.4.0): Icon suite for UI controls and navigation.

QRCode.js (v1.0.0): Client-side QR code generation for APK mobile downloads.

Google Fonts (Inter): Primary typography family.

Getting Started
Clone or Download the Repository:

Bash
git clone https://github.com/your-username/animio-strimer.git
cd animio-strimer
Open in Browser:

Double-click index.html to open it in Chrome, Firefox, Edge, or Safari.

Alternatively, use VS Code's Live Server extension to launch locally.

Login Credentials:

Pre-filled default credentials (user@animio.app) can be used to bypass the authentication gate immediately.

Usage Guide
Watch Media: Hover over any movie card and click the green Play button to launch the full-screen player modal.

Download Media: Click the red Download button on any item, pick your resolution (or kbps) and target store, then execute the task.

Unlock Vault: Navigate to the Private Section in the sidebar and enter any PIN to open your secured files.

Detect Links: Click Detect Link in the top navigation bar to trigger automated clipboard stream detection.
