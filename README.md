# Adeep Kujur — Portfolio Website

A responsive personal portfolio for Adeep Kujur, a CITS Information Technology trainee. Built with HTML5, CSS3 and vanilla JavaScript. No build tools, framework, backend or database are required.

## Preview locally

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. For the closest match to GitHub Pages, use a simple local static server or the VS Code Live Server extension.

## Project structure

```text
adeep-portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   │   └── profile.jpg       # Add your own profile photo
│   └── documents/
│       └── resume.pdf        # Optional: add your resume
└── README.md
```

## Add your profile photo

Your supplied profile photo is already included as `assets/images/profile.jpg`. To change it later, replace that file while keeping the same filename. The page shows the initials `AK` if the image cannot be loaded.

The original Windows file path is not used in the website. A local path such as `C:\\Users\\...` will not work after publishing.

## Add your resume

Your resume has already been added as `assets/documents/resume.pdf`, and the hero section includes a working Download Resume link. To replace it later, upload your updated PDF using the same filename.

Your AI Literacy certificate is also included at `assets/documents/ai-literacy-ibm-skillsbuild.pdf`. The Certifications section links to the PDF and the supplied Credly verification page.

## Update your information

Open `index.html` in a text editor and update the relevant text. Add only skills, certificates, internships and project details that are accurate and that you can explain.

- **Skills:** Update the Skills section with your real skills and experience.
- **Project:** Add the actual project description, technologies, features, your contribution and a screenshot.
- **Project image:** Your supplied AI Computer Lab Assistant screenshot is included as `assets/images/project-ai-lab.png` and displayed in the project card. Replace it with another screenshot using the same filename if needed.
- **Certificate:** Your AI Literacy certificate from IBM SkillsBuild is included in the Certifications section. The PDF is stored at `assets/documents/ai-literacy-ibm-skillsbuild.pdf`; the page also links to the supplied Credly verification URL.
- **Internships:** Add an internship section only after you have verified details.

The detailed street address is not displayed in the public page; the hero shows only Jashpur, Chhattisgarh, India for privacy.

## Publish on GitHub Pages

1. Sign in to [GitHub](https://github.com/).
2. Create a new repository. For a personal site, the repository can be named `adeepkujur.github.io`. For a project site, choose any repository name.
3. Upload all files and folders from this project. Make sure `index.html` is in the repository root.
4. Open the repository's **Settings**.
5. Select **Pages** in the sidebar.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/ (root)`, then click **Save**.
8. Wait a few minutes, then open the published URL shown in the Pages settings.

For a personal repository named `adeepkujur.github.io`, the site URL is usually `https://adeepkujur.github.io/`. For a project repository, GitHub shows the exact URL in Settings → Pages.

## Updating the website

Edit the files locally, then upload/commit the changes to the same GitHub repository. GitHub Pages republishes the site automatically after a successful commit.

## Notes

- All website asset paths are relative, which supports GitHub Pages project sites.
- The contact links use `mailto:`, `tel:` and your supplied LinkedIn/GitHub URLs.
- No skill ratings, certificates, internship history or unverified project features have been invented.
- Google Fonts is loaded from an external CDN; if it is unavailable, the page uses fallback fonts.
