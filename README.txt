TAMER EL ASWAD — SITE GUIDE
=============================

FILES:
  index.html    → main feed (photos + text posts)
  about.html    → about page
  contact.html  → contact page
  style.css     → all the styling (fonts, colors, spacing)
  posts/        → put your photo files in here

UPLOAD TO GITHUB:
  Upload ALL files to your repository root.
  Put photos inside the /posts/ folder.

HOW TO ADD A PHOTO POST:
  1. Put your image file in the posts/ folder (e.g. photo2.jpg)
  2. Open index.html
  3. Copy the photo post block (between the PHOTO POST comments)
  4. Paste it above the previous post
  5. Change photo1.jpg to your new filename
  6. Update the date and caption
  7. Save and re-upload index.html to GitHub

HOW TO ADD A TEXT POST:
  Same as above but copy the TEXT POST block instead.

CONTACT FORM (optional):
  To get a working contact form without a server:
  1. Go to formspree.io and sign up free
  2. Create a form and copy your form code (looks like: xrgvwkzp)
  3. In contact.html, replace the email line with the form block
     (it's already written, just uncomment it and add your code)

CHANGING YOUR EMAIL IN CONTACT:
  In contact.html, replace: your@email.com
  with your actual email address (in both the href and the text).

CHANGING ABOUT TEXT:
  Open about.html and edit the text between the <p> tags.
