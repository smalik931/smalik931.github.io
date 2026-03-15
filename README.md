# Dr. Sheeba Malik - Professional Researcher Website

## Live Website
- **Website:** https://smalik931.github.io/
- **Repository:** https://github.com/smalik931/sheebamalik.github.io

---

## Files in This Repository
- `index.html` — main website file
- `profile-photo.jpg` — profile image used by the website
- `README.md` — project notes and update instructions
- `.nojekyll` — keeps GitHub Pages deployment simple for this static site

---

## GitHub Pages Setup
This website is configured as a **GitHub Pages user site**.

Repository name:
```text
sheebamalik931.github.io
```

Live URL:
```text
https://smalik931.github.io/
```

GitHub Pages publishes the site directly from the `main` branch when `index.html` is present in the repository root.

---

## How to Update the Website
### Edit online on GitHub
1. Open the repository on GitHub.
2. Click `index.html` or `README.md`.
3. Click the pencil icon to edit.
4. Commit the changes to the `main` branch.
5. Refresh the website after 1–2 minutes.

### Edit locally and push
```bash
git clone https://github.com/smalik931/sheebamalik931.github.io.git
cd sheebamalik931.github.io

# edit files
git add index.html README.md profile-photo.jpg
git commit -m "Update website"
git push origin main
```

---

## Current Website Information
- **Name:** Dr. Sheeba Malik
- **Role:** Computational Biophysicist
- **Affiliation:** Max Planck Institute for Dynamics of Complex Technical Systems
- **Primary email:** malik@mpi-magdeburg.mpg.de
- **Secondary email:** malik.sheeba931@gmail.com
- **Google Scholar:** https://scholar.google.com/citations?user=YgpCteoAAAAJ&hl=en
- **ORCID:** https://orcid.org/0000-0002-9812-513X
- **GitHub:** https://github.com/smalik931

---

---

## Common Edits
### Update your photo
Replace `profile-photo.jpg` with a new image using the same filename.

### Update text content
Open `index.html` and edit the section you want to change.

### Add a new publication
Duplicate one publication card block in the `Selected Publications` section and update the title, authors, journal, and year.

### Update contact links
Search in `index.html` for:
- `mailto:`
- `scholar.google.com`
- `orcid.org`
- `github.com/smalik931`

---

## Notes
- This is a static website built with **HTML**, **Tailwind CSS**, **Font Awesome**, and a small amount of **vanilla JavaScript**.
- No backend is required.
- Any change pushed to the `main` branch will update the live site automatically after deployment completes.

---

## Local Preview
You can preview the website locally before pushing changes:

```bash
cd sheebamalik931.github.io
python -m http.server 8000
```

Then open:
```text
http://localhost:8000
```

---

## License
This website content and code are for Dr. Sheeba Malik's personal academic website.
