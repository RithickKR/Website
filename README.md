# BRADS Aerospace - Media Assets for Cloudinary/CDN Upload

This file contains a complete inventory of all image and video files referenced by the website. **All media files should be uploaded to Cloudinary or another CDN** — do NOT commit them to Git.

---

## Directory Structure & File Inventory

### 📁 favicon / logos
- `img/favicon.png` - Site favicon (used in all pages `<head>`)
- `img/logo.svg` - Main logo
- `img/logo-t.svg` - Transparent/horizontal logo variant (header)
- `img/logo-3.jpg` - Logo variant
- `img/logo-name.svg` - Logo with name

---

### 📁 images (root)
Generic images used across the site:

`3d.jpg`, `3d1.jpg`, `4c1fced9-5a0d-4a24-ac72-155c361cc693.png`,
`7.png`, `7-1.png`, `8.png`, `8-1.png`, `8.svg`,
`9.png`, `9-1.png`,
`10.png`, `11.png`, `12.png`, `13.png`, `14.png`, `15.png`, `16.png`, `17.png`,
`agri.jpg`, `best-cut-img.jpg`,
`bg-body.svg`, `bg-cut-2.jpg`, `bg-cut-3.jpg`, `bg-cut-page.jpg`,
`Bharat Electronics Limited-01.png`, `cancel.svg`,
`Chimney-1.jpg`, `chimney.webp`, `chimney-2.webp`, `chimney-3.jpg`,
`cleaning.avif`,
`client-1.svg`, `client-2.svg`, `client-3.svg`, `client-4.svg`, `client-5.svg`, `client-6.svg`,
`colllege.jpg`, `confined.png`, `Construction.jpg`,
`drone-cut-1.png`, `energy.jpg`, `environmental.webp`,
`icon-1.svg`, `icon-2.svg`, `icon-3.png`, `icon-4.svg`,
`icon-about-1.svg`, `icon-about-2.svg`, `icon-about-3.svg`,
`icon-map.png`,
`icon-tab-1.svg`, `icon-tab-2.svg`, `icon-tab-3.svg`, `icon-tab-4.svg`, `icon-tab-5.svg`, `icon-tab-6.svg`,
`img-1.jpg`, `img-2.jpg`, `img-3.jpg`, `img-4.jpg`,
`img-about-top.jpg`, `img-contact-1.jpg`,
`img-cut-1.jpg`, `img-cut-2.jpg`, `img-cut-3.jpg`, `img-cut-4.jpg`,
`img-serv-1.jpg`, `img-serv-2.jpg`,
`inspect1.jpg`, `inspect2.webp`,
`logistics.jpg`,
`manufactoring.jpg`, `mapping.jpg`, `mines.jpg`, `mapping.jpg`,
`ndrf.png`, `NIRM.png`, `oil.webp`, `photo.jpg`, `placeholder-all.png`,
`powerline.jpg`, `powerline1.jpg`, `powerline2.jpg`, `prashant.jpg`, `public.webp`, `rpto.jpg`,
`survey.jpg`, `survey.png`, `Survey.jpeg`, `Survey1.jpeg`,
`tech.avif`, `Thermal.avif`, `thermal.webp`, `training2.jpg`, `ut.jpg`,
`wildlife2.jpg`, `wildlife2.webp`,
`windmill.jpg`, `windmill2.jpg`, `windmill3.jpg`

---

### 📁 images/dopo
Drone product images:
- `DOPO-MS-FRONT.28.png`
- `DOPO-MS-TOP.20.png`
- `Dopo-iso.png`
- `Dopo_sv_Preview-1.png`

---

### 📁 images/drones (swat)
Drone product images:
- `swat_front.Main-1.png`
- `swat_iso.png`
- `swat_side.png`
- `swat_top.png`

---

### 📁 images/drones (tavas)
Drone product images:
- `tavas_front.png`
- `TAVAS_Main.png`
- `tavas_side.png`
- `tavas_top.png`

---

### 📁 images/drones (l15 - L Series)
Drone product images:
- `L-15_front.png`
- `L-15_iso.png`
- `L-15_side.png`
- `L-15_top.png`

---

### 📁 images/drones (nimble)
Drone product images:
- `Nimble_front.png`
- `Nimble_iso.png`
- `nibmle_side.png`
- `nibmle_top.png`

---

### 📁 images/icons
Site UI icons (SVG/PNG):
- `agri.svg`, `camera.svg`, `custom.svg`, `inspection.png`, `mapping.svg`, `rpto.svg`, `specialized.png`, `videography.png`

---

### 📁 images/services
Service category thumbnail images:
- `3d-modeling.jpg`, `agricultural-spraying.jpg`, `agriculture.jpg`, `chimney.jpg`, `cleaning.jpg`,
`confined-inspection.jpg`, `emergency.jpg`, `inspections.jpg`, `mapping.jpg`, `media.jpg`,
`ndt.jpg`, `powerline.jpg`, `solar.jpg`, `survey-mapping.jpg`, `ut-measurement.jpg`,
`videography.jpg`, `visual-thermal.jpg`, `wind-turbine.jpg`, `windmill-inspection.jpg`

---

## 📁 Videos (vid/ directory)

### 📁 vid/agriculture
- `agri1.mp4`, `agri2.mp4`, `agri3.mp4`, `agri4.mp4`, `agri5.mov`

### 📁 vid/Chimney
- `Chimney1.mp4`, `Chimney2.mov`

### 📁 vid/inspection
- `inspect1.mp4`, `inspect2.mp4`, `inspect3.mp4`, `inspect4.mp4`, `inspect5.mov`
- `aerial-view-of-factory-emitting-smoke-into-...` (truncated filename)
- `river-and-bridge-aerial-shot-forwards-2023...`
- `top-view-drone-tracking-shot-of-a-twin-lng...`

### 📁 vid/Monitoring
- `monitor1.mov`, `monitor2.mov`, `monitor3.mov`, `monitor4.mov`, `monitor5.mov`

### 📁 vid/Videography
- `video1.mov`, `Video1.mp4`, `Video2.mp4`, `Video3.mp4`, `video4.mp4`

### 📁 vid/Windmill
- `windmill1.mov`, `windmill2.mp4`

### 📁 vid/ (root level)
- `Final Logo Video/Brads Aerospace Logo Video.mp4`
- `Final Logo Video/Brads LOGO Video 2.mp4`
- `Brads 1.mp4`, `Brads 2.mp4`, `Brads 3.mp4`, `Brads 4.mp4`, `Brads 5.mp4`
- `dhanushkodi1.mp4`
- `Throttle.mp4`

---

## 🔧 Instructions for Cloudinary Upload

1. **Create a free Cloudinary account** at https://cloudinary.com
2. **Upload all files above** preserving the folder structure (or organize as needed)
3. **Update HTML files** — replace all `img/filename.ext` and `vid/filename.ext` references with:
   - `https://res.cloudinary.com/YOUR_CLOUD_NAME/image/upload/folder/filename.ext`
   - `https://res.cloudinary.com/YOUR_CLOUD_NAME/video/upload/folder/filename.ext`
4. **Delete local `img/` and `vid/` directories** after verification
5. **Commit the updated HTML** with Cloudinary URLs

---

## 📝 Notes
- Total image files: ~130+ across all categories
- Total video files: ~38+ across all categories
- `.gitignore` already contains `img/`, `vid/`, and media extensions — these will NOT be tracked after this commit
- Python utility scripts (`*.py`) and reports (`report*.txt`) are also excluded from Git