Pharmacy Management System (Android) - by Hakim Noor

BUILD THE APK ON GITHUB (about 5-10 minutes)
1) Extract this zip first (GitHub does not unzip files).
2) On github.com create a new repository (Public or Private).
3) Click "uploading an existing file" and drag in ALL of these:
   www folder, package.json, capacitor.config.json, .gitignore, .github folder
4) If the hidden .github folder did not upload: Add file > Create new file,
   name it  .github/workflows/build.yml  and paste the content of build.yml, then Commit.
5) Open the Actions tab > Build APK. If it does not start, click Run workflow.
6) When it finishes (green check), open the run, download Artifacts > Pharmacy-APK,
   unzip it and install app-debug.apk on your phone
   (allow "Install unknown apps" if Android asks).

Login: admin / admin123 (change it in More > Settings).
