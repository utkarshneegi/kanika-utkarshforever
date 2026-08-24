# Kanika & Utkarsh — Wedding Website

A single-page wedding site with a live countdown, event details, gallery, and RSVP form.

## Publish this on GitHub Pages (free, ~5 minutes)

1. **Create a new repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it whatever you like (e.g. `kanika-utkarsh-wedding`)
   - Keep it **Public** (GitHub Pages on the free plan requires public repos, unless you have GitHub Pro/Team/Enterprise)
   - Don't initialize with a README (you already have one) — click **Create repository**

2. **Upload these files**
   - On your new repo's page, click **Add file → Upload files**
   - Drag in `index.html`, the `images` folder, and this `README.md`
   - Scroll down, click **Commit changes**

3. **Turn on GitHub Pages**
   - Go to your repo's **Settings → Pages** (left sidebar)
   - Under "Build and deployment" → **Source**, select **Deploy from a branch**
   - Under **Branch**, choose `main` and folder `/ (root)` → **Save**

4. **Visit your site**
   - Wait 1–2 minutes, then refresh the Pages settings page — you'll see a banner with your live URL:
     `https://<your-username>.github.io/<repo-name>/`
   - That's your wedding website, live and shareable.

## Making changes later

- Edit `index.html` directly on GitHub (click the pencil icon on the file), or clone the repo locally and edit there.
- Any commit to `main` redeploys the site automatically within a minute or two.

## Using your own domain (optional)

If you'd like something like `kanikaandutkarsh.com` instead of the github.io URL:
1. Buy the domain from any registrar (Namecheap, GoDaddy, etc.)
2. In repo **Settings → Pages**, add it under **Custom domain**
3. In your registrar's DNS settings, add a `CNAME` record pointing to `<your-username>.github.io`

## Notes

- The RSVP form is currently front-end only — submissions show a thank-you message but aren't sent anywhere. Let Claude know if you'd like it wired up to an email or a form service (e.g. Formspree) before sharing the link widely.
- All photos live in `/images` as regular files, so the repo stays small and fast to load — don't switch back to embedding them as base64.
