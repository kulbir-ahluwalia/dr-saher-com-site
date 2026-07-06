# dr-saher.github.io

Personal academic website for **Dr. Saher Ahluwalia, MBBS** live at https://dr-saher.github.io

## Structure
- `index.html` the whole site (single page, embedded CSS, no build step)
- `assets/dr-saher.jpg` hero portrait (Cleveland Clinic photo)
- `assets/Saher-Ahluwalia-CV.pdf` web CV (phone/street address deliberately omitted)
- `cv-web.md` source for the web CV; regenerate with:
  `pandoc cv-web.md -o assets/Saher-Ahluwalia-CV.pdf --pdf-engine=xelatex`

## Updating
1. Edit `index.html` (sections are labelled) and/or `cv-web.md`
2. Rebuild the CV PDF if `cv-web.md` changed (command above)
3. `git add -A && git commit -m "update" && git push`

GitHub Pages serves `main` branch root automatically for this repo name.
