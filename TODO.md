# Quick Dimension - Repository Setup TODO

## ✅ Done
- [x] Repository created on GitHub
- [x] README.md added
- [x] .rbz file v1.3.1 added to downloads/
- [x] Directory structure created

## 📋 Remaining Tasks

### 1. Export Icon PNGs (5 minutes)
- [ ] Open `/Users/andidewanto/Documents/workserv/workzero/sketchup plugin/Logo/Quick Dimension.svg`
- [ ] Export as PNG:
  - Quick Dimension 1024.png
  - Quick Dimension 512.png
  - Quick Dimension 256.png (← this one goes to images/ folder as quick-dimension-icon.png)
  - Quick Dimension 128.png
- [ ] Copy 256px version to `images/quick-dimension-icon.png`

### 2. Get Brand Logo
- [ ] Copy `brand-andidewanto.png` from any other extension repo (simple-bevel, mapeasy, zone-stretch)
- [ ] Add to `images/` folder

### 3. Take Screenshots (15 minutes)
Create these in SketchUp:
- [ ] `images/quick-dimension-before-after.png` - Model before/after clicking with dimensions
- [ ] `images/quick-dimension-modes.png` - Three modes side-by-side
- [ ] `images/quick-dimension-export.png` - Export dialog and result

**Specs**: 1600px max width, PNG, < 400 KB each

### 4. Create How-to Video (30 minutes)
- [ ] Record: `videos/quick-dimension-how-to.mp4`
- [ ] Create poster: `videos/quick-dimension-how-to-poster.jpg`

**Specs**: ≤90s, 1280×800 (16:10), H.264 MP4, English captions

### 5. Build HTML Pages (1-2 hours)
Use content from: `/Users/andidewanto/Documents/workserv/workzero/sketchup plugin/EW Listing/Quick Dimension/content-structure.md`

- [ ] Create `index.html` (detail page)
  - Hero section
  - 6 feature cards
  - How it works (5 steps)
  - Install instructions
  - 6 FAQ items
  - Version history
  - Coffee section
  - Footer

- [ ] Create `tutorial.html`
  - 6 tasks with step-by-step instructions
  - Tips for each task
  - Navigation back to index

**Reference**: Copy structure from simple-bevel, mapeasy, or zone-stretch repos

### 6. Push to GitHub
```bash
cd ~/Documents/quick-dimension-repo
git add .
git commit -m "Initial commit: Quick Dimension v1.3.1

- Extension package (.rbz)
- README (EN + ID)
- Directory structure for assets

Co-Authored-By: Claude Sonnet 5.5 <noreply@anthropic.com>"
git push -u origin main
```

### 7. Update Hub Page
Clone and update `andidewanto/sketchup-extensions`:
- [ ] Add Quick Dimension card to index.html
- [ ] Copy icon to hub's images folder
- [ ] Test all links
- [ ] Push changes

### 8. Extension Warehouse
Use: `/Users/andidewanto/Documents/workserv/workzero/sketchup plugin/EW Listing/Quick Dimension/listing.md`
- [ ] Upload unsigned .rbz
- [ ] Upload icon 1024.png
- [ ] Upload screenshots
- [ ] Add video link
- [ ] Submit for review

---

## 📂 Current Files

```
~/Documents/quick-dimension-repo/
├── README.md ✓
├── TODO.md (this file)
├── downloads/
│   └── ad_quick_dimension-1.3.1.rbz ✓
├── images/
│   └── .gitkeep (placeholder)
└── videos/
    └── .gitkeep (placeholder)
```

## 🔗 Useful Links

- Repository: https://github.com/andidewanto/quick-dimension
- Content source: `/Users/andidewanto/Documents/workserv/workzero/sketchup plugin/EW Listing/Quick Dimension/`
- Icon source: `/Users/andidewanto/Documents/workserv/workzero/sketchup plugin/Logo/Quick Dimension.svg`
- Reference repos: 
  - https://github.com/andidewanto/simple-bevel
  - https://github.com/andidewanto/mapeasy
  - https://github.com/andidewanto/zone-stretch
