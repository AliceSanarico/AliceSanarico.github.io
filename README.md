# Alice Sanarico's Personal Website

This is the source code for my personal academic website, built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

🌐 **Live site**: https://alicesanarico.github.io

## How to Update Your Website

### Upload Your CV
1. Save your CV as `cv.pdf`
2. Upload it to the `static/` folder in this repository
3. The website will automatically link to it

### Add Your Profile Picture
1. Save your profile picture as `picture.png` (square format recommended, e.g., 500x500px)
2. Upload it to the `static/` folder
3. The website will automatically display it

### Update Your Bio
Edit the `subtitle` section in `config.yml` (around line 56)

### Add Projects
Edit `content/projects/_index.md` and add your projects following the existing format

### Add Publications
Edit `content/publications/_index.md` and add your publications

### Add Teaching Experience
Edit `content/teaching/_index.md` and add your courses

### Add Conferences & Workshops
Edit `content/conferences/_index.md` and add your presentations

### Update LinkedIn URL
Edit `config.yml` and find the LinkedIn URL (around line 79) - replace the placeholder with your actual LinkedIn profile URL

## Local Development

If you want to preview changes locally before publishing:

1. Install Hugo: https://gohugo.io/installation/
2. Clone this repository with submodules:
   ```bash
   git clone --recurse-submodules https://github.com/AliceSanarico/AliceSanarico.github.io.git
   cd AliceSanarico.github.io
   ```
3. Run the local server:
   ```bash
   hugo server -D
   ```
4. Open http://localhost:1313 in your browser

## Automatic Deployment

The website automatically rebuilds and deploys whenever you push changes to the `main` branch, thanks to GitHub Actions.

## Theme

This site uses the [PaperMod theme](https://github.com/adityatelange/hugo-PaperMod). For advanced customization, refer to their documentation.

## Questions?

Feel free to open an issue or contact me at alice.sanarico@unimi.it
