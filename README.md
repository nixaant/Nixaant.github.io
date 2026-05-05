# HIRO — Manga Portfolio
**nixaant.github.io**

---

## File Structure
```
/
├── index.html          ← Home page
├── gallery.html        ← All artworks
├── characters.html     ← Character design work
├── panels.html         ← Manga panels & pages
├── process.html        ← WIPs & behind the scenes
├── commissions.html    ← Commission info & booking
├── about.html          ← About Hiro
├── style.css           ← All styles
├── main.js             ← Nav & interactions
└── img/
    ├── gallery/        ← Drop gallery images here
    ├── characters/     ← Drop character art here
    ├── panels/         ← Drop panel art here
    └── process/        ← Drop WIP/process images here
```

---

## How to Add Art

### 1. Create the img folders on GitHub
Go to your repo → Add file → Create new file → type `img/gallery/.gitkeep` → Commit.
Repeat for `img/characters/`, `img/panels/`, `img/process/`.

### 2. Upload your images
Go to the folder (e.g. `img/gallery/`) → Add file → Upload files → drag your art in → Commit.

### 3. Add it to the HTML
Open `gallery.html` and find the comment block. Copy the template and fill in your image path:

```html
<div class="gallery-item" data-category="character">
  <img src="img/gallery/my-artwork.jpg" alt="Artwork title" loading="lazy">
  <div class="gallery-overlay">
    <div>
      <div class="gallery-label">Artwork Title</div>
      <div class="gallery-sublabel">Character Design</div>
    </div>
  </div>
</div>
```

Categories: `character` | `panel` | `illustration` | `fanart`

---

## Editing Your About Page
Open `about.html` and edit the paragraph text and influence tags to match your real story and references.

---

## Updating Commission Slots
Open `commissions.html` and change the number `5` in the slots section to however many slots you currently have open.
