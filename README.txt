CRICK ON TIME — JSON CONNECTED VERSION

Files:
1. Crick On Time Connected.html
2. crick-on-time-content.json

Keep both files in the SAME folder.

The HTML loads:
- Hero eyebrow/text
- Hero CTA text and links
- Landscape and portrait hero image URLs
- Match names/details/status
- Watch / Remind Me link URLs

To add hero images, edit the JSON:
"landscapeImage": "images/hero-1-wide.jpg",
"portraitImage": "images/hero-1-phone.jpg"

If those fields are blank, the original SVG artwork remains visible.

Important:
Because the page uses fetch() to load the JSON, opening the HTML directly with file:// may be blocked by browser CORS rules. Run it from a small local web server, for example:
python -m http.server

Then open:
http://localhost:8000/Crick%20On%20Time%20Connected.html
