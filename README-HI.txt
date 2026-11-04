CUSTOMER SUPPORT - Android starter project

Features:
- App name: Customer Support
- Headphone support branding (emoji placeholder)
- Admin ID fixed as: admin123
- First launch asks you to create and confirm an admin password
- Login and five dashboard sections:
  1. User Management
  2. Customer Messages
  3. Support Tickets
  4. All Users Details
  5. Admin Settings

APK build (GitHub, mobile browser also works):
1. Create/sign in to a GitHub account.
2. Create a NEW repository and upload all files/folders from this ZIP.
3. Open the repository -> Actions.
4. Select "Build Customer Support APK" -> Run workflow.
5. Wait for the workflow to finish.
6. Open the completed run and download artifact "CustomerSupport-debug-apk".
7. Extract the ZIP to get app-debug.apk.

Important:
- This is a starter/demo app. Dashboard sections are placeholder screens; they do not yet connect to a server or store real users/messages/tickets.
- Login password is set locally on first launch. It is not cloud authentication and is not suitable for production admin access.
- For a real customer-support system, add a secure backend, database, HTTPS API, password reset and signed release build.
