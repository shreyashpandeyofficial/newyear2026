New Year 2026 Greeting Generator
===============================

This folder contains a ready-to-upload static website for a New Year greeting card generator.
Everything runs client-side (in the browser), so you can host it on GitHub Pages for free.

Files included:
- index.html  -> Main page
- style.css   -> Styling
- script.js   -> All JS functionality (image resize, effects, download, share link)
- README.md   -> This file

How to publish on GitHub Pages
------------------------------
1. Create a new GitHub repository (e.g., newyear2026).
2. Upload all files from this ZIP into the repository root.
3. In repository Settings -> Pages -> Choose branch "main" and folder "/" -> Save.
4. After a minute, your site will be available at: https://<your-username>.github.io/<repo-name>/

Iframe code for Blogger post
----------------------------
After you publish the site, use this iframe in your Blogger post (HTML mode):

<iframe src="https://<your-username>.github.io/<repo-name>/" width="100%" height="800" style="border:0;" loading="lazy"></iframe>

Notes
-----
- The share feature encodes the card data (name + small image) into the URL hash so that opening the link reproduces the card.
- Uploaded photos are processed locally in the browser and are NOT uploaded to any server.
- If you want a custom music file, replace the audio source in index.html with your MP3 URL.
