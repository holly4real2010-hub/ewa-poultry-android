EWA POULTRY & FARMING — ANDROID APK CLOUD BUILD

This package contains the Android app source plus a GitHub Actions workflow that builds the APK in the cloud. No Mac or Windows computer is needed, but a free GitHub account and a one-time upload of this ZIP's contents are required.

FROM AN IPHONE:
1. In Safari, open https://github.com and create/sign in to a free account.
2. Create a new repository named EWA-Poultry-Android. Set it to Private or Public; either works.
3. Open the new repository, choose Add file > Upload files.
4. In the iPhone Files app, unzip EWA_Poultry_Android_Project.zip. Upload the CONTENTS of the EWA_Poultry_Android_Project folder (including the hidden .github folder). If GitHub's mobile upload interface hides .github, use GitHub's website in Safari with Request Desktop Website, or upload the project using GitHub's web editor.
5. Commit the uploaded files to the main branch. The workflow should start automatically.
6. In the repository, open Actions > Build EWA Poultry APK > latest successful run.
7. Under Artifacts, download EWA_Poultry_App_APK. Unzip it in Files to get app-debug.apk.
8. Send app-debug.apk to an Android phone. Android may ask to allow installation from that browser/file app. Only install APKs from a source you trust.

IMPORTANT:
- This creates a DEBUG APK for direct testing/sharing, not a Play Store release.
- The APK is not yet compiled in this package; GitHub Actions compiles it after upload.
- Keep the repository private if you prefer not to publish the source code.
- Do not share GitHub passwords or account recovery codes.
