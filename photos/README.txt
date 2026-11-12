BCEC Time profile photos
========================

This folder is served on the public GitHub Pages site:
https://munfordmatt.github.io/bcec-time/

Do not put a photo here until Matt says it is OK to make it public.

How Dana can add a photo later
------------------------------
1. On the office page, open "Crew & PINs".
2. Tap "Add photo" next to the person and pick a picture.
3. The page downloads a cropped, 200-pixel file named like w31.jpg
   (David Blankenship) or w21.jpg (Gary Rimmer).
4. After Matt approves, put that file in this photos folder and republish
   the GitHub Pages site (run publish-pages.sh from the project, which
   keeps the existing backend URL in api-url.txt).

You can also list a different filename in manifest.json:
  { "w31": "w31.jpg", "w21": "gary.jpg" }

If there is no file for a person, the app shows their initials in a circle.

The office page cannot save a photo by itself. That would need a Google
Apps Script change, which has to be deployed in the browser under
matt@bluffcityelectrical.com.
