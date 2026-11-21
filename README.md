# Md Shamim Mia — Portfolio Website

A free static portfolio site for GitHub Pages. No build step — just HTML, CSS and a little JavaScript.

**Live sections:** Hero · Featured case study · Services (KDP + graphic design) · Portfolio (books + design years) · Process · Pricing · About · Experience timeline · FAQ · Contact

## Files

```
index.html        ← the whole page (text lives here)
css/style.css     ← colours, layout, mobile design
js/main.js        ← mobile menu, scroll animations, back-to-top
images/           ← all pictures (see guide below)
```

## Image guide — which image goes where

| File | Where it appears | Recommended size | Status |
|---|---|---|---|
| `images/profile.jpg` | Hero photo frame | Square 1000 × 1000 px | ✅ Sam's profile photo — frame aspect-ratio is 1/1 to match the square photo exactly (do not change the frame ratio) |
| `images/project-1-cover.jpg` | Project 1 — Word Search cover | Portrait, ~680 × 900 px | ✅ Your real book cover |
| `images/project-1-interior.jpg` | Project 1 — puzzle page | ~680 × 1030 px | ✅ Real page from your book (Puzzle 1) |
| `images/project-1-solution.jpg` | Project 1 — solution page | ~680 × 1030 px | ✅ Real page from your book (Solution 3) |
| `images/project-1-thumb.jpg` | "Designed for the thumbnail" box | 150 px wide | ✅ Small copy of your real cover |
| `images/project-wordsearch-1.jpg` … `-5.jpg` | Word Search client-work gallery (covers, trios, variety collages) | 1100 px wide | ✅ Sam's real client work (Fiverr gig samples) |
| `images/project-2-covers.jpg` | Project 2 — cover design set | 1200 × 800 px | 🧩 Clean placeholder panel (labelled 'samples coming soon') — swap in real samples when Sam sends them |
| `images/project-3-interiors.jpg` | Project 3 — sudoku & maze interiors | 1200 × 800 px | 🧩 Clean placeholder panel (labelled 'samples coming soon') — swap in real samples when Sam sends them |
| `images/project-4-dotmarker-1.jpg` … `-6.jpg` | Project 4 — dot marker gallery (3 covers, then 3 cover+interior spreads) | 1100 px wide | ✅ Sam's real books (Dot Marker ABC, Dottie Dots, Easter edition) |
| `images/project-5-lowcontent.jpg` | Project 5 — notebooks/journals/logbooks | 1200 × 800 px | 🧩 Clean placeholder panel (labelled 'samples coming soon') — swap in real samples when Sam sends them |
| `images/project-6-illustration-1.jpg` | Project 6 — watercolor illustration (raincoat girl & puppy) | 1100 px wide | ✅ Sam's real illustration |
| `images/project-6-illustration-2.jpg` | Project 6 — watercolor illustration (grandmother reading) | 1100 px wide | ✅ Sam's real illustration |
| `images/project-6-illustration-3.jpg` | Project 6 — watercolor illustration (boy, lantern & fox) | 1100 px wide | ✅ Sam's real illustration |
| `images/showreel-poster.jpg` | Showreel video poster frame | 1280 × 720 | ✅ Frame from Sam's gig video |
| `videos/showreel.mp4` | Showreel section video (720p, muted, looping) | under ~10 MB | ✅ Compressed from Sam's 4K Fiverr gig video (original kept for a future YouTube HD version) |
| `images/project-7-logo.jpg` | Design years — logo & branding | 1200 × 800 px | 🧩 Clean placeholder panel (labelled 'samples coming soon') — swap in real samples when Sam sends them |
| `images/project-8-tshirt.jpg` | Design years — t-shirt design | 1200 × 800 px | 🧩 Clean placeholder panel (labelled 'samples coming soon') — swap in real samples when Sam sends them |
| `images/project-9-print.jpg` | Design years — business cards & flyers | 1200 × 800 px | 🧩 Clean placeholder panel (labelled 'samples coming soon') — swap in real samples when Sam sends them |

**To replace an image:** save your new picture with the *exact same file name* in the `images/` folder and upload it to GitHub (it overwrites the old one). No code change needed. Keep JPG under ~300 KB so the site stays fast.

## Two things to personalise in `index.html`

1. **Contact form (Formspree — LIVE)** — form 'Portfolio Contact', endpoint `https://formspree.io/f/xeaglkoz`, recipient shamimmia19961@gmail.com. Every message (a) arrives as an email in Sam's Gmail and (b) is stored in his Formspree dashboard (formspree.io → log in → Submissions). Free plan: 50 messages/month, dashboard keeps the last 30 days. To change the recipient or form, edit it in the Formspree dashboard — the site code does not need to change unless the form ID changes.
2. **Tools list** — the site lists Adobe Photoshop, Illustrator and InDesign. If your tools are different, edit that list (search for "Adobe Photoshop").

## Publishing

See the step-by-step GitHub Pages guide Muse gave you (create repo → upload these files → Settings → Pages → Branch: main → your free URL is `https://YOUR-USERNAME.github.io/portfolio/`).

## Updating text later

All words are in `index.html` — open it, find the sentence, change it, re-upload the file. Or just ask Muse to do it.

## Updating the site later (free, as often as you like)

### Option A — Ask Muse (easiest, recommended)
Send Muse the new photo or text in chat and say what to change ("add this cover", "change the price", "add a new service"). Muse edits the files and sends you a fresh ZIP. Upload the changed files to GitHub (step 3 below) and the live site updates itself. You never need to touch code.

### Option B — Do it yourself on GitHub
1. Open your repository on github.com and sign in.
2. To **change text**: click `index.html` → click the pencil (Edit) icon → find the sentence → type the new one → scroll down → **Commit changes**.
3. To **replace a photo**: open the `images` folder → click the file → **⋯ → Delete file** → then **Add file → Upload files** and upload the new photo with the *exact same name*.
4. Wait 1–2 minutes and refresh your site link. Done — no cost, no limit on how often.

### How to add a brand-new project
1. Put the project photo in the `images/` folder with a clear name, e.g. `project-10-coloring.jpg` (1200 × 800 px, JPG, under ~300 KB).
2. In `index.html`, find a project card (search for `project-tag`) and copy the whole block from `<article class="project reveal">` to `</article>`.
3. Paste the copy right after it, then change three things in the pasted block: the image file name, the `<h3>` title, and the description text.
4. Upload both files to GitHub (the photo into `images/`, and the edited `index.html`). The new project appears within 1–2 minutes.
   *(Or skip steps 2–4 entirely — send the photo to Muse and ask for it to be added.)*

## Adding a video (Showreel section)

The site has a **Showreel** section ready for a portfolio video. Two ways to fill it:

### Best way — YouTube (unlisted) or Vimeo embed
GitHub Pages refuses files over 100 MB and big videos make the site slow, so the video lives on YouTube and plays inside the page:
1. Upload your video to YouTube and set it to **Unlisted** (only people with the link — or visitors to this site — can see it).
2. Easiest: send Muse the video link in chat — Muse swaps it into the Showreel section for you.
3. DIY: on the video page click **Share → Embed**, copy the `<iframe ...>` code, and in `index.html` replace the whole `<div class="video-frame reveal"> ... </div>` block's inner poster part with that iframe (keep the outer div). Commit — the video is live in 1–2 minutes.
4. To change the video later, just repeat with the new link. The site itself never gets heavier.

### Short clips — direct MP4
A tiny silent clip (a book flip-through, a cover reveal) can live in the repo itself:
- Keep it **under ~10 MB**, MP4 format, ideally under 30 seconds.
- Put it in a `videos/` folder and ask Muse to wire it in as an auto-playing, muted, looping clip — or replace the poster block with:
  `<video src="videos/clip.mp4" autoplay muted loop playsinline></video>`

### Sending your portfolio photos & videos to Muse
- A few files: send them right in the chat.
- Many or large files: put them in a **Google Drive folder** and send Muse the folder link.

## Payments — how the Hire Me section works

A static GitHub Pages site **cannot take card payments directly** — there is no server and no payment gateway. That is normal for portfolio sites. Instead, the Contact section offers the two routes Sam actually uses:
- **Fiverr** — the client orders there and Fiverr holds the money in escrow until the work is approved.
- **Payoneer** — for direct clients and remote roles, by agreed milestones.

If Sam later wants real on-site checkout, that needs a payment link (e.g. a Payoneer payment request link or a Stripe Payment Link) pasted into the same buttons — the design does not change.
