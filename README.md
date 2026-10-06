# AICTSS Advanced ITT MCQ Dashboard — Mobile/PWA Version

This version is designed for Android phones, iPhones, tablets and desktop browsers.

## Features
- 50 questions per practice page where available.
- Correct answer is hidden until an option is tapped.
- Selected correct answer turns green.
- Selected wrong answer turns red and the correct answer turns green.
- No Quick Explanation panel.
- Responsive touch-friendly interface.
- Installable as a PWA on supported Android/iOS browsers.
- Offline after the app assets have been cached.
- Progress, wrong answers and theme are saved locally in the browser.

## Android
Open the hosted dashboard in Chrome/Edge and use **Install app** or **Add to Home screen**.

## iPhone/iPad
Open the hosted dashboard in Safari → **Share** → **Add to Home Screen** → Add.

## Important
For PWA installation/service-worker offline support, the dashboard must be hosted over HTTPS (for example GitHub Pages, Netlify, Vercel, or a normal HTTPS web server). Opening `index.html` directly from the Files app still works for practice, but browser security prevents service workers from running from a `file://` URL.
