# Wedding website — local opening fixed

Extract the whole ZIP into a folder first. Open index.html with Chrome or Edge by double-clicking it. Do not open the HTML directly inside the ZIP. The page now embeds its minified CSS and obfuscated JavaScript; it no longer relies on local external script/style loading or CORS-dependent integrity checks. Inline code is authorized by CSP hashes.

For GitHub Pages, upload all extracted contents together. The same index.html works locally and on hosting. main.js and style.css are retained as matching production files, but index.html embeds its runtime copies. Editing those separate files alone will not change the page; rebuild the embedded copies and CSP hashes.

Add BG.mp3 alongside index.html, and ten photos named picture-01.webp to picture-10.webp inside images/home/. These media files were not supplied. Until then, photo placeholders and Music unavailable are expected. The included fonts folder must remain beside index.html. Internet fonts use italic fallback when unavailable.

Included: three-second opening, curtains, English/Vietnamese romantic stories, magical letter writing, individual photo entrances, mouse dust, dynamic ten-photo collage, and music controls. Obfuscation discourages casual copying but cannot prevent browser inspection. No source maps or readable preview are included.

Use the glowing − / + controls to change auto-scroll speed from 0.25× to 4×. The speed display switches between English and Vietnamese. Pause/resume operates independently. Convert your ten photos to WebP and use picture-01.webp through picture-10.webp; do not merely rename JPG files.
