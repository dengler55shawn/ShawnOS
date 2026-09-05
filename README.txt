SHAWN_OS v2.0 — DEPLOYMENT README
==================================

FILES
-----
Keep this structure:

SHAWN_OS_DEPLOY/
├── index.html
├── README.txt
├── iris.mp3
├── final-video.mp4
└── photos/
    ├── first-date-1.jpg
    ├── first-date-2.jpg
    ├── ...
    ├── porch-1.jpg
    ├── porch-2.jpg
    ├── porch-1.mp4
    └── ...

The current package includes the supplied photo/video files in photos/ and the final 2:57 video as final-video.mp4.
iris.mp3 is NOT included because no Iris audio file was supplied in this upload. Add it beside index.html before publishing.

ADDING PHOTOS
-------------
Photos are named by memory and number:

first-date-1.jpg through first-date-6.jpg
good-friday-1.jpg through good-friday-6.jpg
jellyfish-theory-1.jpg through jellyfish-theory-6.jpg
backyard-grand-prix-1.jpg through backyard-grand-prix-6.jpg
george-bush-1.jpg through george-bush-6.jpg
starved-rock-1.jpg through starved-rock-6.jpg
jam-in-pants-1.jpg through jam-in-pants-6.jpg
beach-1.jpg through beach-6.jpg
first-homecoming-1.jpg through first-homecoming-6.jpg
conjuring-1.jpg through conjuring-6.jpg
six-flags-1.jpg through six-flags-6.jpg
porch-1.jpg through porch-6.jpg

If a media file is missing, the website automatically hides that slot.
You do not need to edit index.html to add another photo if you use the naming pattern.

ADDING VIDEOS
-------------
Videos use the same pattern:

photos/porch-1.mp4
photos/porch-2.mp4
...
photos/beach-1.mp4

Missing/unsupported videos are automatically hidden.

IRIS AUDIO
----------
Put:

iris.mp3

beside index.html.

The website references it as "iris.mp3".
The PLAY button starts the audio, so there is no autoplay.
The audio continues through Act III and fades out when CONTINUE is pressed.

FINAL VIDEO
-----------
Put:

final-video.mp4

beside index.html.

The final screen references it as "final-video.mp4".
It uses normal HTML5 controls and playsinline for mobile.

GITHUB PAGES
------------
Upload/replace index.html and upload the photos folder contents.
Keep iris.mp3 and final-video.mp4 beside index.html in the repository.

Then use:
Settings → Pages → Deploy from a branch → main → / (root) → Save.

TESTING
-------
For local testing on a computer:

python3 -m http.server 8000

Then open:
http://localhost:8000

Windows may use:
py -m http.server 8000

ChatGPT's built-in HTML preview may not execute JavaScript exactly like a normal hosted webpage. Test the published site in Safari or Chrome.

NO EXTERNAL DEPENDENCIES
------------------------
No external libraries, frameworks, CDNs, APIs, or external fonts are required.

IMPORTANT
---------
Keep filenames and folder paths exactly as shown. GitHub Pages paths are case-sensitive.
