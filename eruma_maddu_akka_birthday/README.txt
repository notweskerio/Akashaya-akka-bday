ERUMA MADDU AKKA — BIRTHDAY SURPRISE WEBSITE
================================================

Birthday: October 27, 2026
Language: English
Hosting: GitHub Pages (free)

QUICK START
1. Extract this ZIP.
2. Open the extracted folder in VS Code.
3. Open index.html in your browser (double-click it) to preview.
4. Replace the sample gallery images and personalise the timeline and letter.
5. When ready, publish the folder using GitHub Pages (instructions below).

PERSONALISE PHOTOS
- Put your own image files in the photos folder.
- In index.html, find the three <article class="photo-card"> blocks.
- Change each image src to (for example) photos/akka1.jpg, photos/akka2.jpg, photos/akka3.jpg.
- Change the captions below each photo to your own memory captions.
- Keep filenames simple (no spaces recommended).

ADD MUSIC LATER
- Put an MP3 file in the music folder and name it birthday-song.mp3.
- The play button is already connected to music/birthday-song.mp3.
- Use a song you have permission to share. Do not rely on autoplay; visitors tap Play.

PERSONALISE THE MEMORY TIMELINE
- In index.html, find <div class="timeline">.
- Edit the three memory headings and descriptions to match real moments you shared.

PERSONALISE THE LETTER
- Find <div class="secret" id="secretMessage"> and replace the sample message.
- Keep the opening and closing tags.

CHANGE THE COUNTDOWN
- The date is currently 2026-10-27 at midnight India time.
- It is set in the JavaScript line beginning: const birthday = new Date(...)
- Format: YYYY-MM-DDTHH:MM:SS+05:30

PUBLISH FREE WITH GITHUB PAGES
1. Sign in to https://github.com (create a free account if needed).
2. Click the + menu > New repository.
3. Name it: akka-birthday (Public), then Create repository.
4. Upload the contents of this folder (index.html, photos folder, music folder) to the repository.
5. Open repository Settings > Pages.
6. Under Build and deployment, choose Deploy from a branch.
7. Select branch main and folder /(root), then Save.
8. Wait a few minutes. GitHub will show your website URL, usually:
   https://YOUR-USERNAME.github.io/akka-birthday/

IMPORTANT
- The sample gallery images currently load from Unsplash, so they need internet access.
- For a private family surprise, remember that a public GitHub Pages site can be viewed by anyone with the link (and may be discoverable). Avoid posting sensitive photos or personal information.
- The countdown uses India Standard Time (UTC+05:30).
