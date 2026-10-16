JARVIS PHONE STARTER
====================

What's included:
- Dark JARVIS-style interface
- Browser speech input (if supported)
- Spoken replies
- Local time command
- Save Dad's number locally and open the dialer
- Best-effort attempt to launch Mobile Legends
- PWA manifest and service worker

Important limits:
- This is a starter web app, not a native Android app.
- Browser speech recognition may need internet and will not reliably work with screen off.
- Opening another app is restricted by Android/browser; the MLBB intent may not work on every device/browser.
- Real AI conversations are not connected yet. A secure backend is needed; never put a private API key in client-side HTML.
- Flashlight, reliable app control, offline speech recognition, and always-on “Hey Jarvis” require native Android functionality and permissions.

PHONE-ONLY TESTING:
1. Extract the ZIP on your phone.
2. Open index.html in Chrome. Some browsers restrict speech recognition for local files.
3. For best results, host the files on an HTTPS static host (for example GitHub Pages) using your phone browser.
4. Open the hosted page in Chrome and use the browser menu > Add to Home screen / Install app if offered.
5. Test typing first, then microphone permission, then commands.
6. For calls, enter Dad's number in Quick setup and save it. Call command opens the dialer; confirm manually.

Next build stage:
Connect a secure AI backend, then build native Android integration for wake-word detection and background service.
