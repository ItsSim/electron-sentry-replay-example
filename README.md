# electron-sentry-replay-example
Minimal example. Steps to reproduce:
1. `npm run install`
2. Add or modify the Sentry Loader script in the app.html's \<head>
3. `npm run build-win` or `build-mac` depending on your OS.
4. Run the app (built in ./release)
5. Check Replays on Sentry - fonts and images are not loaded.
