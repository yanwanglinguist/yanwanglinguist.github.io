YAN WANG ACADEMIC WEBSITE — EDITING GUIDE

1. Open index.html with Safari to preview. Edit it using VS Code, then press Cmd+S and refresh Safari.
2. ABOUT PHOTO: put an actual JPG image named portrait.jpg into this folder (same folder as index.html). Nothing is written underneath the photo.
3. CV: cv.pdf is already included, copied from the CV you uploaded. Its link works immediately.
4. PRESENTATIONS: find id="presentations" in index.html. Replace the href="#" on each [slides]/[poster] link with a URL, or a PDF path such as "slides/sinfonija19.pdf". Put files in the appropriate folder. Remove data-pending="slides" or data-pending="poster" from the link when replacing href, otherwise the link will remain inactive.
5. PAPERS: find id="papers" and edit citations there.
6. GALLERY: find "const cities = [" near the bottom of index.html. Put your photos into folders such as photos/graz/photo1.jpg and list every picture there, e.g.
   { name: 'Graz', photos: ['photos/graz/photo1.jpg', 'photos/graz/photo2.jpg', 'photos/graz/photo3.jpg'] },
   { name: 'Berlin', photos: ['photos/berlin/photo1.jpg'] }
   Click a city card to see its photos. Click any photo to enlarge it; Escape to close. Browsers cannot automatically scan folders, so photos must be listed in the cities array.
7. COLORS: edit the six variables at the top of index.html in :root.
8. Upload index.html, cv.pdf and the entire photos folder to GitHub Pages to publish.
9. The subproject link points to its section on the Cyclic Optimization page, because no standalone link was supplied.
