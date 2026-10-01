# Avinash Sunil Shinde - Personal Portfolio Website

A responsive, static portfolio website built with plain HTML, CSS and JavaScript.

## Folder structure

```text
avinash-profile-website/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── assets/
    ├── images/
    │   ├── profile.jpg
    │   └── projects/
    │       ├── genpin.jpg
    │       ├── android-auto.jpg
    │       ├── nissan-service.jpg
    │       ├── cloud-pos.jpg
    │       ├── komatsu.jpg
    │       ├── quantified-self.jpg
    │       ├── max-total-security.jpg
    │       └── bank-domain.jpg
    │
    └── resume/
        └── Avinash_Sunil_Shinde_Resume.pdf
```

## Add your images

1. Put your profile photo here:
   `assets/images/profile.jpg`

2. Put project screenshots here:
   `assets/images/projects/`

3. Keep the filenames used in `index.html`, or change the `src` values.

Recommended:
- Profile photo: 800x800 or larger, square
- Project screenshots: 1200x750 or similar landscape ratio
- JPG/WebP/PNG are supported

## Add LinkedIn and GitHub

Open `index.html` and replace the two placeholder links near the Contact section:

```html
<a class="text-link" href="#" ...>LinkedIn ↗</a>
<a class="text-link" href="#" ...>GitHub ↗</a>
```

with your real profile URLs.

## Run locally

You can double-click `index.html`, but using a local server is better.

### VS Code

Install the "Live Server" extension and right-click `index.html` -> **Open with Live Server**.

### Python

From the website folder:

```bash
python -m http.server 5500
```

Then open:

http://localhost:5500

## Publish online

### GitHub Pages
1. Create a GitHub repository, for example:
   `avinash-shinde-portfolio`
2. Upload all files and folders.
3. Go to Settings -> Pages.
4. Select the main branch and `/root`.
5. GitHub will give you a public website URL.

Typical format:

`https://YOUR-GITHUB-USERNAME.github.io/avinash-shinde-portfolio/`

### Netlify
1. Create an account.
2. Choose **Add new site** -> **Deploy manually**.
3. Drag the entire `avinash-profile-website` folder into Netlify.
4. Netlify generates a public URL.

### Custom domain
After publishing, you can connect a domain such as:

`www.avinashshinde.dev`

or

`www.avinashshinde.com`

Availability and pricing depend on the domain registrar.

## Important

The website only includes technologies and experience supported by the resume information. Add any additional technologies, social links, project URLs, or certifications only after confirming them.
