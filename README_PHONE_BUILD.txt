INFINITY Salon Bill - Android project (phone-friendly build route)

What this is:
- Android WebView app wrapper around the current HTML bill maker.
- App name: INFINITY Salon Bill.
- APK build is configured using GitHub Actions.

Important:
- This ZIP is the source project, not an installable APK.
- No APK has been compiled or signed in this workspace.
- The current HTML still uses internet-loaded libraries for Excel/PDF export.
- The current HTML does not yet save bill history persistently on the phone.
- GitHub Actions debug APK is suitable for testing/installing, but it is not a Play Store release-signed APK.

Build using only a phone:
1. Download and extract this ZIP on your phone.
2. Create/sign in to a GitHub account and create a new empty repository.
3. Upload the extracted project files to the repository root (keep the .github/workflows folder).
4. Open the repository's Actions tab and run "Build INFINITY Salon APK" (or let the first push trigger it).
5. Open the completed workflow run, download the "INFINITY-Salon-Bill-APK" artifact, extract it, and install app-debug.apk.
6. Android may ask to allow installing unknown apps for the app you used to download/open the APK. Only allow it for this file if you trust the source.

If ZIP upload on mobile is difficult, use GitHub's web upload files page and upload the extracted files/folders. Ensure .github/workflows/build-apk.yml is included.
