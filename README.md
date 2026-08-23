# Romantic Proposal Website

A fully static, Render-ready romantic website.

## Personalize it

1. Replace the text in `index.html` wherever you want her name or personal stories added.
2. Put her photos in `assets/photos/` using these exact names:
   - her-hero.jpg
   - her-1.jpg
   - her-2.jpg
   - her-3.jpg
   - her-4.jpg
   - her-5.jpg
   - her-6.jpg
   - her-7.jpg
   - music-cover.jpg
3. Put your MP3 song at:
   - `assets/music/our-song.mp3`

If a local photo is missing, the website currently falls back to an online demo image so the design still looks complete.

## Deploy on Render

### Option A — GitHub
1. Create a GitHub repository.
2. Upload all files from this project.
3. In Render, click **New +** → **Static Site**.
4. Connect your GitHub repository.
5. Build command: leave blank.
6. Publish directory: `.`
7. Deploy.

### Option B — render.yaml
Push the entire project to GitHub including `render.yaml`.
Render can detect the configuration through Blueprint deployment.

## Important note about music

Modern browsers normally block autoplay with sound. The visitor should press the play button.
That is why this site includes a built-in music player and a floating music control.

## Suggested next personalization

For the strongest emotional effect, customize:
- her actual name;
- where/how you met;
- a specific memory only the two of you understand;
- why you admire her personally;
- a real future date idea;
- your chosen song;
- 6–8 of her best photos.

## Yes-button email notification

The **Yes** button is configured to send an email notification to:

`keynnankoga@gmail.com`

It uses FormSubmit's AJAX endpoint, so no Gmail password is stored in the website.

### First-time activation

FormSubmit may send an activation/confirmation email to `keynnankoga@gmail.com` the first time the form is submitted.
Open that message and confirm the form once. After activation, future Yes-clicks can be delivered automatically.

The browser console logs an error if the notification service cannot be reached, while the visitor's romantic experience remains intact.
