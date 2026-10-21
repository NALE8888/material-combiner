# Material Combiner Android PWA

This is a mobile-friendly Progressive Web App. It includes the material recipes and labels, Final1/Final2 modes, inventory fields, action plan, leftover tracking, and per-material image uploads.

## Install on Android
1. Upload all files in this folder to an HTTPS static host.
2. Open the hosted URL in Chrome on Android.
3. Choose **Install app** or Chrome menu → **Add to Home screen**.
4. Enter your inventory and tap Optimize combinations.

Opening `index.html` directly from the phone's Files app does not enable full PWA installation/offline support. HTTPS hosting is required.

## Your images
Tap **Add image** next to a material. Images are resized and stored locally in this browser on your device; they are not uploaded.

## Calculation details
Recipes are encoded in `index.html`. Final1 and Final2 are optimized together in Both mode, and no ingredient is used twice. Final1-only mode excludes production of T4BY1–T4BY4. The search has a safety cap to protect mobile browsers; if a warning says the cap was reached, the result may not be globally optimal.
