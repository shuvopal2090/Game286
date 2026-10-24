SPOT THE DIFFERENCE - APK BUILD PROJECT

1. On github.com create a NEW repository.
2. Upload these files to the repository root: index.html, package.json,
   capacitor.config.json  (drag them in: Add file > Upload files > Commit).
3. Create the build script: Add file > Create new file, name it exactly
      .github/workflows/build-apk.yml
   and paste the full content of the file build-apk.yml. Commit.
   (If the .github folder uploaded fine with the zip contents, skip this.)
4. Open the Actions tab. "Build APK" runs by itself (or Run workflow). Wait 5-8 min for the green check.
5. Open the finished run > Artifacts > download SpotTheDifference-APK, unzip to get app-debug.apk.
6. Copy the APK to your phone and install it (allow "Install unknown apps").

The game needs internet only for the title font; everything else works offline.
