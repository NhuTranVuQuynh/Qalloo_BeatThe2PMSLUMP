# Qalloo Energy: Beat the 2 PM Slump

Campaign landing page for a university digital marketing course. Qalloo is a project name based on Qallo, used with the brand's consent so the page isn't mistaken for the official site.

The page takes visitors through five steps: wake Ollo, find your flavour, see your pack, Q&A, and trial checkout.

## Files

```
index.html     the whole page (HTML, CSS and JavaScript in one file)
images/        Ollo poses and the Qalloo Energy pack photos
```

All images are stored in `images/` and linked with relative paths, so they keep working wherever the folder is hosted. The only outside request is Google Fonts (Fredoka and DM Sans). Without it the page falls back to a system font.

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `qalloo-2pm-slump`.
2. Upload `index.html` and the whole `images` folder to the root of the repository. Keep the folder name and file names exactly as they are.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then click **Save**.
4. After a minute or two the page is live at `https://<your-username>.github.io/<repository-name>/`.

## Links per channel

Add `?src=` to the link to change the welcome line for each entry point:

| Link | Used for |
|---|---|
| `.../?src=instagram` | Instagram bio and Reels (default) |
| `.../?src=tiktok` | TikTok bio |
| `.../?src=booth` | QR code at the 2 PM Slump Station |

For a presentation you can fix the clock, so the slump headline shows at any time of day:

- `.../?time=14:05` peak slump
- `.../?time=10:30` morning version
- `.../?time=17:20` after-work version

Without `?time=`, the page uses the visitor's real time.

## Still to fill in

- Instagram handle in the "Follow" button (search for `[@campaign_handle]` in `index.html`)
- SLUMP5 discount amount and checkout total (`[discount]`, `[total]`)
- Checkout link to the shop (search for `#checkout`)
