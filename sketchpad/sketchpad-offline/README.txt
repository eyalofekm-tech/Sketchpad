Sketchpad: offline version
=========================

These files are the whole app. Put them on any web host once; after you add it
to your Home Screen, it opens with no internet connection.

Free hosting with GitHub Pages (works from an iPad):
1. Sign in at github.com and create a new public repository, e.g. "sketchpad".
2. In the repository tap "Add file" > "Upload files" and upload ALL the files
   from this folder (index.html, sw.js, manifest.webmanifest, and the 3 icons).
   Tap "Commit changes".
3. Open Settings > Pages. Under "Branch" choose "main" and "/ (root)", then Save.
4. After a minute your app is at https://YOUR-NAME.github.io/sketchpad/

On the iPad:
5. Open that address in Safari, wait a few seconds for it to load fully.
6. Tap the Share button > "Add to Home Screen" > Add.
7. Open Sketchpad from its new icon once while online. From then on it works offline.

Notes
- This version keeps canvases on the iPad only (no Claude account sync).
  Use the Backup button on the home page to move your library between this
  version and the one in Claude, or to keep a safety copy in Files.
- To update the app later, upload the new files over the old ones. The app
  picks up the update the next time it opens with internet (then reopen it).
