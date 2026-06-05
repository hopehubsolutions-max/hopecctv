HOPEVISION WEBSITE — SETUP GUIDE
================================

WHAT'S IN THIS FOLDER
  index.html            -> your website
  content/site.json     -> all the words, prices and settings (the editor changes this)
  images/               -> all the photos
  admin/                -> your editor (where you log in to change things)

You will do this ONCE. After that, you just open the editor, change things, press Publish,
and your live website updates within about a minute — for everyone.


-------------------------------------------------------------
STEP 1 — Make a free GitHub account (this is where the site lives)
-------------------------------------------------------------
1. Go to github.com -> Sign up (free). 
2. Once logged in, click the "+" (top right) -> "New repository".
3. Name it:  hopevision
4. Keep it Public, click "Create repository".
5. On the new page click "uploading an existing file".
6. Drag in EVERYTHING from this folder (index.html, the content folder, the images
   folder, and the admin folder). Then click "Commit changes".


-------------------------------------------------------------
STEP 2 — Put it online with Netlify (free hosting)
-------------------------------------------------------------
1. Go to netlify.com -> Sign up -> choose "Log in with GitHub".
2. Click "Add new site" -> "Import an existing project" -> GitHub -> pick "hopevision".
3. Leave all settings as they are -> click "Deploy".
4. After a minute you get a live link like  hopevision.netlify.app  — that's your site!
   (In Site settings you can rename it, e.g. hopevision, and later add a real .com domain.)


-------------------------------------------------------------
STEP 3 — Connect the editor (so you can change things and Publish)
-------------------------------------------------------------
1. In GitHub, open the file  admin/config.yml  -> click the pencil to edit.
2. Find the line:   repo: YOUR-GITHUB-USERNAME/hopevision
   Replace YOUR-GITHUB-USERNAME with your real GitHub username. Commit the change.
3. The editor needs a "login key" so it can save your changes. This is the one
   technical step — the exact buttons change over time, so send me a message when
   you reach here and I'll walk you through it screen by screen. (It takes ~5 minutes
   and is free: you create a GitHub "OAuth app", paste two codes into Netlify.)


-------------------------------------------------------------
USING THE EDITOR (every time after setup)
-------------------------------------------------------------
1. Go to  your-site.netlify.app/admin
2. Log in with GitHub.
3. Click "Website content". Change any text, price, photo, colour, or the
   business-name size.
4. Press "Publish". Done — your live site updates in about a minute.

Tip: you can do all of this from your phone.
