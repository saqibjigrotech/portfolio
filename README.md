# Sofiya Bano | Digital Marketing Portfolio

A static website (no build step). Files:
- index.html  the whole site (HTML + CSS + JS)
- images/     your screenshots
- vercel.json Vercel settings

## Edit
1. Screenshots: add files to images/ with these names (.jpg/.png/.webp):
   seo-sheet, jt-1, jt-2, jt-3, static-1, static-2, slide-1, slide-2, slide-3, slide-4
   They replace the illustrated placeholders automatically.
2. Contact: in index.html find `const EMAIL='',PHONE='';` and fill both.
3. Text/links: everything is plain text in index.html. Project cards and link rows are the `P` and `R` lists near the bottom.
4. Preview: double-click index.html.

## Publish on Vercel (free)
Option A: drag and drop
1. Sign in at vercel.com, go to Add New > Project, then use the drag-and-drop / "deploy a folder" option (or install the CLI below).
Option B: CLI
1. Install Node.js, then run: npm i -g vercel
2. In this folder run: vercel   (follow prompts, framework: Other)
3. Go live with: vercel --prod
Option C: GitHub
1. Push this folder to a GitHub repo. In Vercel, Add New > Project > import the repo > Deploy.
Redeploy after any edit (git push, or `vercel --prod`).
