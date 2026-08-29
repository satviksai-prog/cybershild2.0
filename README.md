🛡️ Cyber Shield

Intelligent Phishing, Scam and Cyber-Fraud Detection

Cyber Shield is a simple website that checks if a link, text message, or QR code is a scam. It gives an instant result — Safe, Be Careful, or Dangerous — along with plain-English reasons, so anyone, even non-technical users, can understand it.

Built for HackSprint 2.0, Problem Statement #5: Intelligent Phishing, Scam and Cyber-Fraud Detection.

📌 Problem

Online scams through fake links, fraud messages, and QR codes are increasing fast. Most existing tools are scattered, technical, and built for experts — leaving everyday people, especially elderly and non-tech users, unprotected.

✅ Solution

Cyber Shield brings scam detection into one simple place. Paste a link or message, or upload a QR code, and get an instant, easy-to-understand safety check — no sign-up required, no technical knowledge needed.

✨ Features
🔗 URL Scanner — checks links for fake domains, missing security (HTTPS), risky extensions, and brand impersonation
💬 Message Scanner — detects urgency language, OTP/PIN requests, prize/lottery bait, and generic greetings
📷 QR Code Scanner — decodes the hidden link inside a QR code and checks it the same way as a normal URL
🎯 Risk Score & Verdict — every scan gets a score out of 100, shown as Safe / Be Careful / Dangerous
🏦 Bank Impersonation Detector — flags fake websites pretending to be real banks or brands
🧑‍🤝‍🧑 Sender Trust Score — if multiple users report the same sender, it gets flagged for everyone
🌍 Multi-Language Support — available in English, Hindi, and Telugu
📚 Learn Section — real scam examples so users can practice spotting them
🗂️ Scan History — every check is saved automatically for later reference
🌐 Community Threat Feed — dangerous scans are shared so other users get warned too
⚙️ How It Works
User pastes a link/message or uploads a QR code, then clicks Check
If it's a QR code, the hidden link is decoded first
The content is checked against known scam patterns
Each suspicious pattern found adds points to a risk score
The total score decides the result: Safe, Be Careful, or Dangerous
Certain serious flags (like bank impersonation) can override the score and force a Dangerous result
The result and reasons are shown instantly, and saved automatically to the user's history

No human review is needed at any step — the entire process is automatic.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript
QR Decoding: jsQR
Backend: Firebase
Authentication — Google sign-in and anonymous login
Firestore — stores scan history, community reports, and sender trust data
Cloud Functions — runs detection logic securely on the server
Hosting — deploys the website
