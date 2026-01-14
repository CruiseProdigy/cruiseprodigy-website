# CruiseProdigy - Reorganized Project Structure

**Status:** Ready for Git initialization and development
**Last Updated:** January 14, 2026

## Folder Structure

```
CruiseProdigy/
├── index.html                      (Homepage - stays in root)
├── .gitignore                      (Git ignore rules)
│
├── css/                            (All stylesheets - TO BE EXTRACTED)
│   ├── main.css                    (Shared styles)
│   ├── homepage.css                (Homepage-specific)
│   └── dossier.css                 (Cruise line pages)
│
├── js/                             (All JavaScript - TO BE EXTRACTED)
│   ├── navigation.js               (Menu & smooth scroll)
│   ├── weather.js                  (Weather API integration)
│   └── search.js                   (Search functionality)
│
├── images/                         (All images, organized)
│   ├── cruise-lines/               (Logos & ship photos)
│   ├── ports/                      (Port images)
│   ├── icons/                      (Icons & graphics)
│   └── backgrounds/                (Hero & background images)
│
├── pages/                          (All content pages)
│   ├── cruise-lines/               (11 dossier pages)
│   │   ├── line-carnival.html
│   │   ├── line-celebrity.html
│   │   ├── line-cunard.html
│   │   ├── line-disney.html
│   │   ├── line-holland.html
│   │   ├── line-msc.html
│   │   ├── line-norwegian.html
│   │   ├── line-princess.html
│   │   ├── line-royal.html
│   │   ├── line-viking.html
│   │   └── line-virgin.html
│   │
│   ├── ports/                      (Port guides)
│   │   └── port-st-maarten.html
│   │
│   ├── blog/                       (News & articles)
│   │   ├── fieldreports.html
│   │   └── fieldreportsindex1.1.html
│   │
│   ├── tools/                      (Interactive tools - future)
│   └── legal/                      (Privacy, terms, etc. - future)
│
├── assets/                         (Other resources)
│   ├── fonts/                      (Custom fonts if self-hosting)
│   ├── downloads/                  (PDFs, printables)
│   └── docs/                       (Your notes & planning)
│
├── archive/                        (Old versions)
│   └── retiredindex.html
│
└── tests/                          (Experimental features)
    └── temp.html
```

## Current State

**✅ DONE:**
- Folder structure created
- All files moved to proper locations
- .gitignore file created
- Structure ready for Git

**⏳ TO DO (Next Session):**
- Update file paths in HTML files (links need to point to new locations)
- Extract common CSS into css/main.css
- Extract common JavaScript into js/ files
- Rename cruise line files (remove "line-" prefix)
- Initialize Git repository
- Make first commit
- Set up GitHub repository
- Enable GitHub Pages

## Important Notes

**File Paths Need Updating:**
The files have been moved, but the links inside them still point to the old locations. For example:

- Homepage links to cruise lines: Need to change from `line-royal.html` to `pages/cruise-lines/line-royal.html`
- Cruise line pages linking back: Need to use `../../index.html` instead of `index.html`

**We will update these together in the next session.**

## Next Steps

1. Download this folder structure to your computer
2. Review the organization
3. Tomorrow: Update paths, extract CSS/JS, initialize Git
4. Test everything works
5. Deploy to GitHub Pages

## Questions?

This structure is based on professional web development best practices and will scale to 500+ pages easily.
