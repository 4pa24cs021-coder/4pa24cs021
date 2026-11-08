# Personal portfolio, resume, and bio-data

A small, responsive, multi-page personal website built with semantic HTML, CSS, and vanilla JavaScript.

## Pages

- `index.html` — portfolio introduction and links to the profile pages.
- `resume.html` — professional profile, experience, education, projects, and skills.
- `biodata.html` — personal profile, optional family background, qualifications, and interests.

The pages are personalized with the details provided in Deekshitha S's resume. Date of birth and family background are omitted because they were not provided. Review the public contact information before publishing. The resume and bio-data pages include a **Print / save as PDF** button; use the browser print dialog to save either page as a PDF.

## Preview locally

Open `index.html` in a browser, or run a static HTTP server from the repository root:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

The workflow in `.github/workflows/deploy-pages.yml` builds and deploys the static site to GitHub Pages whenever changes are pushed to `main`. It copies only the five website files into the Pages artifact, not other files in the repository.

1. In the GitHub repository, open **Settings → Pages**.
2. Set **Build and deployment → Source** to **GitHub Actions**.
3. Push the site files to the `main` branch.
4. Open the **Actions** tab and wait for **Deploy static website to GitHub Pages** to complete.
5. GitHub Pages will show the published URL under **Settings → Pages**. For this repository, it will normally be `https://deekshugowda19-blip.github.io/Adaptive-memory/`.

To keep personal information private, remove any details you do not want publicly available before enabling Pages.
