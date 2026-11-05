BENGALI WEDDING WEBSITE UPDATE

Files
-----
index.html
    Updated website entry point.

wedding-heading.svg
    Transparent-background ornamental heading artwork used on the wedding-card page.
    Keep this file in the same folder as index.html.

Optional image assets expected by the existing website
-------------------------------------------------------
hero.jpg
story-card.jpg
family-card.jpg
wedding-card.jpg
gaye-holud.jpg
wedding-ceremony.jpg
reception.jpg
prewedding-1.jpg
prewedding-2.jpg
prewedding-3.jpg
story-page.jpg
groom-family.jpg
bride-family.jpg
wedding-song.mp3

Wedding card image for all visitors:
    Add your final card image to the same folder as index.html and name it:
    wedding-card-final.jpg

Family photo upload:
    The family upload control currently creates a browser-local preview only.
    To make a chosen family photograph visible to every visitor, add it to the
    site folder and update the appropriate image source to that asset filename.
    The existing groom-family.jpg and bride-family.jpg paths are retained.

Important upload note
---------------------
Images selected through either upload control are local previews in that
visitor's browser. They are not uploaded to Vercel or shared with other visitors.
The wedding-card download button downloads the selected local preview when one
has been selected; otherwise it downloads wedding-card-final.jpg from the site.

Deploy to Vercel
----------------
1. Keep index.html and wedding-heading.svg together in the project root.
2. Add your existing image and music assets to that same root folder.
3. Add wedding-card-final.jpg when your final invitation card is ready.
4. In Vercel, deploy the project folder (or commit the files to the connected
   Git repository and push the changes).
5. Open the deployed site on an Android phone and test page navigation,
   uploads, the download button, music, countdown, RSVP, gallery and map link.

Notes
-----
Only index.html was supplied in this chat. The two reference screenshots
mentioned in the request were not present, so the revised page compositions
follow the written requirements rather than a pixel-by-pixel screenshot match.
