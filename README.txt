APEX RUSH - First Playable v1

ANDROID / GITHUB PAGES SETUP
1. Extract this ZIP on your Android phone.
2. Create a new GitHub repository for this game. Keep it separate from NEET UG Pro.
3. Upload index.html (exact name) and THREE-LICENSE.txt to the repository root. Do not upload the ZIP itself.
4. Settings > Pages > Deploy from a branch > main > /(root) > Save.
5. Open the link GitHub displays once deployment succeeds, using Chrome.
6. Landscape is recommended. Tap START YOUR ENGINE. Hold GO and use left/right buttons; BRAKE slows down.
7. Steering assist is enabled by default. Auto throttle is optional on the start screen.

FEATURES
Actual Three.js/WebGL 3D scene, open-wheel car, desert oval track, 3 AI rivals, 3 laps, position, speedometer, minimap, sequential lap checkpoints, race result, saved best race time (this browser), camera switch, optional synthesized engine sound, pause/resume, car reset, multitouch controls and WASD/arrow keyboard controls.
All engine code is included in index.html; no external CDN or font is needed at runtime.

LIMITS AND VERIFICATION
This is an arcade prototype, not a production simulator. No championship, pit stops, multiplayer, monetization or Android APK is included.
Needs a browser/device with working WebGL. Performance depends on the phone; older phones require on-device testing.
Syntax checks passed. A CPU simulation using real Three.js math/scene objects with a mocked renderer completed a full three-lap assisted race and verified braking, pause/resume and reset. The preview browser lacked WebGL, so visual rendering, mobile touch behavior and device frame rate have not been verified.
If Chrome reports missing 3D support, try an updated Chrome or another compatible device. Opening local HTML from a file manager can vary by Android version; GitHub Pages is the intended route.

THIRD PARTY
Three.js 0.160.1 - MIT license. See THREE-LICENSE.txt.
