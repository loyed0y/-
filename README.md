# LOYED Android

This repository packages the existing LOYED web prototype as an Android APK using Capacitor.

## Source archive required
Upload the original `LOYED (3).zip` to the repository root. Keep the filename exactly as shown. It must contain `LOYED/index.html`, `LOYED/css/`, and `LOYED/js/`.

Once uploaded, the **Build LOYED Android APK** workflow will extract the web source, generate the Android project, build a debug APK, and publish it as the `LOYED-debug-APK` artifact.

This APK wraps the current frontend prototype only. It does not add production backend services, multi-user messaging, secure owner authentication, or push notifications.
