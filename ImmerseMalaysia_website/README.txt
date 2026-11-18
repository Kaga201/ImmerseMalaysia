Immerse Malaysia – XR app prototype (alpha)
=============================================

What is inside
  index.html            the whole app: Home hub + 5 features (Heritage Explorer, Learning Lab, Calm Space, Try-On Market, Flood Ready)
  lib/                  A-Frame (VR lab), <model-viewer> (3D + AR), models.js (embedded 3D models)
  models/               the same 3D models as .glb files (used by Android Scene Viewer for real AR)

Put it online for free so real camera AR works on your phone (about 2 minutes)
  1. Unzip this folder.
  2. Go to https://app.netlify.com/drop and drag the whole unzipped folder onto the page.
     (GitHub Pages or Vercel also work. WebXR and AR only run over HTTPS, and all three give you HTTPS.)
  3. Open the link Netlify gives you on your phone:
       - Android (Chrome): open a lesson, then tap "View in AR" to place the model on your desk.
       - iPhone (Safari): "View in AR" opens Apple Quick Look AR.
       - VR headset browser (e.g. Meta Quest): open the Lab tab and tap the goggles button.

Try it on a laptop
  Run a small local server in this folder, e.g.  python -m http.server 8000
  then open http://localhost:8000  (opening index.html by double-click may block the 3D models).

Demo class code (Learning Lab): LAB-4821
