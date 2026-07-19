BREEZ CYCLE WORX — IMAGE GUIDE
================================
Drop photos into this /images folder using the EXACT filenames below.
The site is already wired to look for these names — no HTML editing needed.
If a file isn't here yet, that spot just shows a plain color background
(nothing looks broken, no missing-image icons).

HOW TO ADD A PHOTO
-------------------
1. Rename your photo to match the filename exactly (case-sensitive)
2. Drop it into this /images folder
3. Re-drag your whole site folder onto Netlify to redeploy
   (Netlify treats every drag-and-drop as a new deploy — takes ~10 seconds)

RECOMMENDED SIZES
-------------------
Full-width background photos (hero, CTA): 1920 x 1080px, landscape, JPG
Card / project photos: 800 x 600px, landscape, JPG
Team headshots: 500 x 500px, square, JPG
Keep file sizes under ~500KB each if possible (use tinypng.com to compress)

================================
FULL LIST OF IMAGE SLOTS
================================

HOMEPAGE (index.html)
----------------------
images/hero-trail.jpg
  → Big background photo behind the hero headline.
  → Boardwalk/trail shot works great here (like your mockup reference).

images/team-map-review.jpg
  → Dark "Bringing Professional Expertise" section, left side photo.
  → People looking at a trail map, walking a property, etc.

images/cta-mountains.jpg
  → Background behind "Let's Build Something Meaningful Together."
  → Landscape / mountain / valley view.

images/project-henderson.jpg
images/project-madisonville.jpg
images/project-hopkins-cycling.jpg
  → The 3 featured project cards on the homepage.

COMMUNITY DEVELOPMENT PAGE (community-development.html)
----------------------
images/land-assessment.jpg
  → Photo next to "Well-Built Isn't Enough" intro text.
  → A property walkthrough, undeveloped land, or trail planning photo.

PROJECTS PAGE (projects.html)
----------------------
images/project-henderson.jpg              (reused from homepage)
images/project-madisonville.jpg           (reused from homepage)
images/project-hopkins-cycling.jpg        (reused from homepage)
images/project-grapevine.jpg
images/project-regional-trails.jpg        (Ben Hawes / Harmonie / Cave Creek)
images/project-hopkins-active-living.jpg

ABOUT PAGE (about.html)
----------------------
images/team-james.jpg
images/team-stephanie.jpg
images/team-richard.jpg
  → Square headshots, same style/background if possible for consistency.

CONTACT PAGE (contact.html)
----------------------
Map — two options, pick one:

OPTION A (easiest): Google Maps Embed
  1. Go to Google Maps, search "Madisonville, KY"
  2. Click Share → Embed a map → copy the <iframe> code
  3. Replace the <div class="map-inner">...</div> block in contact.html
     with that <iframe> code directly
  This shows a real interactive map — no image file needed.

OPTION B: Static image
  Save a screenshot or graphic as images/service-area-map.jpg
  and reference it the same way as the other background images.

================================
NOTE: reused project images
================================
project-henderson.jpg, project-madisonville.jpg, and
project-hopkins-cycling.jpg each appear on BOTH the homepage and the
projects page. Add the file once here in /images — both pages point
to the same file, so you only need one copy of each.
