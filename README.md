# Niamul | Infrastructure Portfolio

A responsive static portfolio website featuring a summary of the SASEC Road Connectivity Project-2 brief provided with this project. It uses plain HTML, CSS, and JavaScript, so there is no build step or dependency install. The source PDF stays local and is not linked from the public site because it contains contract and payment details.

## Personalize before publishing

- Confirm the display name and portfolio wording in `index.html`.
- Replace `hello@yourdomain.com` with your email address.
- The supplied PDF does not identify your personal role. Keep the project description as an overview unless you want to add your specific contribution.
- The construction photo is illustrative and loaded from Unsplash; replace it with an image you have permission to publish if preferred.

## Preview

Open `index.html` in a browser. The source `SASEC_2.pdf` remains in this folder but is not part of the public site.

## Publish with Vercel

Import the GitHub repository at [vercel.com/new](https://vercel.com/new). Choose **Other** as the framework preset, leave the build command and output directory empty, and deploy from the repository root. Vercel will serve `index.html` as a static site.

## Push to GitHub

After creating an empty repository on GitHub, run these commands in this folder (replace the URL with your repository URL):

```powershell
git init
git add index.html README.md .gitignore
git commit -m "Create infrastructure portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```