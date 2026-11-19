# Veya — Google Play Console answers (copy/paste)

Developer: Umar Farooq · Support email: admin@fastvpnn.pp.ua · Website: https://fastvpnn.pp.ua · Package: veyabrowser.vpn

## Store listing
**App name (max 30):** Veya – Private Browser & VPN
**Short description (max 80):** Fast private browser with ad blocker, built-in VPN, video player & downloads.

**Full description (max 4000):**
Veya is a fast, lightweight web browser for Android that keeps your browsing private. No account, no sign-up — just open it and browse.

🔒 PRIVACY & SECURITY
• Ad & tracker blocker (EasyList + EasyPrivacy) for faster, cleaner pages
• Private tabs in a separate WebView profile — cookies and site data never mix with normal tabs
• Third-party cookie blocking, Do Not Track / Global Privacy Control, clear data on exit
• Websites must ask before using your camera, microphone or location
• Optional app lock using your device screen lock

🌐 BUILT-IN VPN (OPTIONAL)
• WireGuard-based VPN inside the browser — choose a server and connect with one tap
• "Browser traffic only" mode protects Veya without routing your other apps
• Off by default; starts only after you connect and approve Android's VPN permission

🗂 ADVANCED TAB MANAGER
• Unlimited tabs, search tabs, grid or list view, swipe to close
• Tab groups (Work, Shopping, Social…) you can rename and delete without losing tabs
• Recently closed tabs and session restore
• Smart memory use: inactive tabs are unloaded and reload when you open them

🎬 VIDEO PLAYER & FLOATING WINDOW
• Built-in player for web videos (HLS and DASH supported) with gesture controls
• Floating picture-in-picture window so videos keep playing while you use other apps
• Playback speed and background audio options

⬇ DOWNLOAD MANAGER
• Fast multi-connection downloads with pause, resume and notifications
• Files saved in a "Veya" folder in Downloads

🛠 EVERYDAY TOOLS
• Search with Google, Bing, DuckDuckGo, Ecosia, Brave, Yahoo or your own engine
• QR scanner, voice search, find in page, read aloud, translate, night mode
• Customisable home page with shortcuts, bookmarks, history and wallpaper
• Set Veya as your default browser

ADS: Veya is free and shows ads from Yandex Mobile Ads after you start a download.
VPN: Veya uses Android's VpnService only for the optional VPN you turn on. We do not use it to collect or sell data, or to show ads.

Privacy Policy: https://fastvpnn.pp.ua/privacy-policy.html
Support: admin@fastvpnn.pp.ua

**Category:** Communication (or Tools) · **Tags:** Browser, VPN, Ad blocker
**Contact details:** email admin@fastvpnn.pp.ua · website https://fastvpnn.pp.ua

## App content declarations
- **Privacy policy URL:** https://fastvpnn.pp.ua/privacy-policy.html
- **Ads:** Yes, the app contains ads (Yandex Mobile Ads, interstitial after a download starts).
- **App access:** All functionality available without login / special access.
- **Target audience:** 18+ (a general-purpose browser gives open internet access; do not select under-13 groups).
- **Content rating questionnaire:** category "Utility / Browser"; the app shows user-generated and web content from third parties (select "yes, the app is a browser / allows internet access" where asked). Expect Teen/Mature-style rating depending on answers.
- **News app:** No. **Government app:** No. **Financial features:** None. **Health features:** None.
- **COVID-19 / contact tracing:** No.

## VPN service declaration (Permissions → VpnService)
- Does the app use VpnService? **Yes.**
- Core functionality? **Yes — the app's optional built-in VPN.**
- Description to paste: "Veya includes an optional VPN that creates an encrypted WireGuard tunnel between the user's device and a VPN server we operate. It starts only after the user selects a server, taps Connect and approves Android's VPN permission prompt. We do not use the VPN to collect or sell personal or sensitive user data, to show or inject ads, or to track users across apps or sites."
- Also complete the **Foreground service** declaration: type "dataSync" — used to keep user-initiated downloads running while the app is in the background (show a notification with progress).

## Data safety form
**Data collection / sharing overview:** The app collects no data itself except what the ad SDK and optional VPN process.
| Data type | Collected? | Shared? | Purpose | Notes |
|---|---|---|---|---|
| Device or other IDs (Advertising ID) | Yes | Yes (Yandex Mobile Ads) | Advertising or marketing; Fraud prevention | Ad SDK. Optional: users can reset/opt out. |
| Approximate location (derived from IP by ad SDK) | Yes | Yes (Yandex) | Advertising | From IP address only. |
| App activity / Web browsing history | **No** — stored on device only, never sent to us | — | — | Not collected. |
| Personal info (name, email, phone) | No | No | — | No accounts. |
| Financial info | No | No | — | |
| Photos/videos/audio/files | No | No | — | Camera/mic used only on user action; not stored or sent. |
| App info and performance (crash logs, diagnostics) | No | No | — | No analytics or crash SDK. |
| Network (VPN) | Public WireGuard key + chosen server sent to our control server only when the user connects; removed on disconnect | No | App functionality | Verify against your server logs — see README. |

- **Is all data encrypted in transit?** Yes (HTTPS to our API; ad SDK uses HTTPS).
- **Can users request data deletion?** Yes — https://fastvpnn.pp.ua/data-deletion.html
- **Independent security review:** No.
- **Families policy:** not applicable (not designed for children).

## Permissions justification (if Play asks)
Internet/network state — browsing, downloads, ads · Camera — QR scanning, user-approved site access · Microphone — voice search, user-approved site access · Location — user-approved site access (maps) · Notifications — download/VPN status · FOREGROUND_SERVICE + DATA_SYNC — user-initiated downloads · BIND_VPN_SERVICE — optional VPN · AD_ID — ad SDK · WRITE_EXTERNAL_STORAGE (max SDK 28) — save downloads on Android 9 and below.

## Graphic assets you still need to upload
App icon 512×512 (assets/logo.png can be resized), feature graphic 1024×500, at least 2 phone screenshots (take real screenshots: home page, tab switcher, VPN screen, video PiP).
