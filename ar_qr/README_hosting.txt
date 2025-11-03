Stylopia AR package
====================

Files included:
- index.html         : AR page (marker-based using Hiro marker)
- assets/WhatsApp Image 2025-10-29 at 19.59.55.jpeg : your image
- qr_placeholder.png : QR code pointing to a placeholder hosting URL

How to make it public (3 quick options)
1) GitHub Pages (recommended)
   - Create a new GitHub repository, upload the extracted files (index.html and assets folder).
   - In repository settings -> Pages, set branch to 'main' and root folder '/' -> Save.
   - Your page will be available at https://<username>.github.io/<repo>/index.html
   - Scan the QR code (or create a new one) pointing to that URL.

2) Netlify / Vercel
   - Drag & drop the extracted folder into Netlify's 'Deploy a site' or Vercel's static site option.
   - They will give you a public URL.

3) Host on your webserver
   - Upload files to your webserver root and use https URL.

Notes:
- This AR uses a marker (Hiro). To view:
  - Open the hosted page on a mobile browser (Chrome on Android recommended).
  - Allow camera permission.
  - Point the camera at the Hiro marker image: https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/HIRO.png
  - The Stylopia 3D card will appear floating above the marker.

If you'd like a markerless (no printed marker) AR experience or automatic hosting, I can guide you step-by-step or help publish to a free host if you give me a GitHub repo name or allow me to create a GitHub Gist for you.
