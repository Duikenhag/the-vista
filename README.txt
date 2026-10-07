The Vista by Mukkanni — website files
=====================================

To put this online, upload this ENTIRE folder (keep the folder structure).
index.html must sit at the top level, with img/, thumb/ and media/ beside it.

Free drag-and-drop hosting:
  app.netlify.com/drop        drag this folder onto the page
  pages.cloudflare.com        "Upload assets"
  vercel.com/new              drag the folder
  GitHub Pages                push the folder to a repo, enable Pages in Settings

After it is live, open index.html and replace the two relative paths
  <meta property="og:image" content="og.jpg">
  <meta name="twitter:image" content="og.jpg">
with the full address, e.g. https://yourdomain.com/og.jpg
so WhatsApp and Instagram show the preview picture.

Files
  index.html   the whole site (one page, three views: home, gallery, booking)
  og.jpg       the picture that shows when the link is shared
  img/         full-size photographs, the 360 panorama, leaf graphics
  thumb/       small versions used in the grids
  media/       the walkthrough film (mp4 and webm) and its poster frame
