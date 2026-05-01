# Wonder Grass Initiative — Website

Static marketing website for Wonder Grass Initiative Pvt. Ltd., a bamboo design-and-build company based in Nagpur, India.

**Live site:** [wondergrass-wireframe.vercel.app](https://wondergrass-wireframe.vercel.app)  
**Hosting:** Vercel (free tier, auto-deploys on push to `main`)  
**Domain:** Custom domain via GoDaddy → pointed to Vercel

---

## Project Structure

```
wondergrass-wireframe/
│
├── index.html                          # Homepage
├── about.html                          # About Us
├── solutions.html                      # Solutions / Sectors
├── contact.html                        # Contact & Enquiry
├── bamboo-lab.html                     # Bamboo Lab
│
├── portfolio-conference-hall.html      # Portfolio: Conference Hall, Pench Tiger Resort
├── portfolio-community-space.html      # Portfolio: Community Space, Snehanchal Nagpur
├── portfolio-ziro-music-festival.html  # Portfolio: Ziro Music Festival, Arunachal Pradesh
├── portfolio-outdoor-structures.html   # Portfolio: Outdoor Structures (Machaans, Pergola)
├── portfolio-farm-house.html           # Portfolio: Farm House
├── portfolio-machaan.html              # Portfolio: Machaan
│
├── product-bamboo-building-components.html  # Product: Bamboo Panels
├── product-bamboo-farm-shed.html            # Product: Bamboo BIY Kit
├── product-bamboo-poly-shed-net.html        # Product: Bamboo Poly-Shed
├── product-eco-lite.html                    # Product: Eco-Lite
├── product-b-pod-cottages.html              # Product: Bamboo Cottage (B-POD)
│
├── _shared-header.html                 # Shared nav partial (reference only)
├── _shared-footer.html                 # Shared footer partial (reference only)
│
├── style.css                           # Global stylesheet
├── .gitignore
└── images/
    └── portfolio/
        ├── conference-hall/            # CCD project images + /process/
        ├── community-space/            # Community space images + /process/
        ├── ziro-music-festival/        # Ziro festival images + /process/
        └── outdoor-structures/         # Machaan & pergola images + /process/
```

## Naming Conventions

| Prefix | Type |
|---|---|
| *(none)* | Core site pages |
| `portfolio-` | Portfolio project pages |
| `product-` | Product pages |
| `_shared-` | Partial/template reference files |

## Image Organisation

All images live under `images/portfolio/<project-slug>/`.  
Gallery images: `<project-slug>-<section>-NN.jpg`  
Process images: `<project-slug>/process/<project-slug>-<step>-NN.jpg`  
Card thumbnails: `<project-slug>-card.jpg`

**Target size:** Under 300 KB per image (compress before pushing).

## Deployment

Push to `main` → Vercel auto-deploys within ~30 seconds.  
To force redeploy: Vercel dashboard → Deployments → Redeploy.

## Tech Stack

Pure HTML + CSS. No framework, no bundler, no JavaScript dependencies.  
All nav/interactions handled with vanilla JS inline in each page.

---

*Wonder Grass Initiative Pvt. Ltd. © 2025*
