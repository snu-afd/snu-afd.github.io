# AFD Lab Website

Static site for snu-afd.github.io

## File structure
```
index.html              ← Homepage
publications.html       ← Publications list
members/
  template.html         ← Copy & rename for each student
css/
  style.css             ← All styles
```

## Adding a member
1. Copy `members/template.html` → `members/yourname.html`
2. Fill in name, role, bio, interests, publications
3. Add a card in `index.html` inside `.members-grid`, linking to `members/yourname.html`
4. Replace the 👤 emoji with `<img src="../photos/yourname.jpg" alt="Your Name" />` once you have a photo

## Deploying to GitHub Pages
1. Push this folder to the repo `snu-afd/snu-afd.github.io`
2. Go to repo Settings → Pages → Source: main branch / root
3. Site goes live at https://snu-afd.github.io

## Updating
Just edit files and push. GitHub Pages rebuilds automatically.
