PSYCHOMETRIC REPORT GENERATOR - ANDROID APP
============================================

OPTION A - Get a real .apk (free, no Android Studio needed)
1. Create a free account at github.com (if you do not have one).
2. Click "+" > "New repository". Name it psychometric-app, choose Private, click Create.
3. On the new repository page click "uploading an existing file".
4. Unzip this folder on your computer and drag EVERYTHING inside "PsychometricApp"
   (the .github folder, www, assets, package.json, capacitor.config.json) into the page.
   IMPORTANT: the ".github" folder must be uploaded too (if hidden, enable "show hidden files").
5. Click "Commit changes". The build starts by itself.
6. Open the "Actions" tab > click the latest run "Build Android APK" > wait about 5-8 minutes for the green tick.
7. Scroll down to "Artifacts" > download "Psychometric-Report-APK" (a zip). Unzip to get app-debug.apk.
8. Send app-debug.apk to your phone (WhatsApp / Drive / cable), open it and allow
   "Install unknown apps" when asked. The app appears as "Psychometric Report".

Where reports are saved in the app: Documents/PsychometricReports/ on the phone,
and the phone's Share sheet opens so you can send the file to WhatsApp, Drive, email etc.

If the run shows a red cross, open it and send me a screenshot of the error.

OPTION B - Installable web app (no APK)
Upload the "www" folder to any free static host (GitHub Pages, Netlify Drop, Cloudflare Pages).
Open the link in Chrome on the phone > menu > "Install app" / "Add to Home screen".
It then opens full-screen like an app and works offline.
