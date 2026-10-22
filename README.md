# Face Motion Studio

A static HTML/CSS/JavaScript webcam demo featuring:
- Camera start/stop controls
- Visual demo overlays (neon glasses, face frame, sparkles)
- Monochrome and glow color effects
- Optional face-reference image upload
- Preview FPS and session timer
- Snapshot download

## Run locally
Camera access works on `localhost` or HTTPS:
1. Open a terminal in this folder.
2. Run `python -m http.server 8000`
3. Open `http://localhost:8000` in your browser.
4. Click **Start camera** and allow access.

Alternatively, open `index.html`, but browser camera access may be blocked for local files.

## Publish free on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under build/deployment, select **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then save.
6. Wait for the published URL and open it over HTTPS.

## Important limitations
This is a front-end prototype. Face tracking is marked as demo and effects are positioned approximately; it does not detect precise facial landmarks. Uploading a reference image does not perform a face swap. Real-time face swap requires a separate AI model/service and should only be used with informed permission from the people involved. Camera frames are not uploaded by this code.
