# Jo's Corner — Setup & Publishing Guide

---

## 🛠️ One-Time Setup (Parent does this — ~30 minutes)

### Step 1 — Put the site on GitHub
1. Go to **github.com** and create a free account (or log in)
2. Click the **+** → **New repository**
3. Name it `jos-corner`, set it to **Public**, click Create
4. Upload all the files from this folder (drag them in via "uploading an existing file")

### Step 2 — Connect to Netlify
1. Go to **app.netlify.com** → "Add new site" → "Import from Git"
2. Connect your GitHub account, select the `jos-corner` repo
3. Leave build settings blank, click **Deploy site**
4. Your site is now live at a `*.netlify.app` URL

### Step 3 — Enable Netlify Identity
1. In your Netlify dashboard → **Site configuration → Identity**
2. Click **Enable Identity**
3. Under **Registration**, choose **Invite only**
4. Scroll down to **Services → Git Gateway** → click **Enable Git Gateway**

### Step 4 — Invite your child
1. Still in Identity, click **Invite users**
2. Enter your child's email address
3. They'll get an email — they click the link, set a password, and they're in

### Step 5 — Create the posts folder in GitHub
1. Go to your `jos-corner` repo on GitHub
2. Click **Add file → Create new file**
3. Type `_posts/.gitkeep` as the filename
4. Click **Commit new file**

That's it! From here on your child handles everything from the /admin panel.

---

## ✏️ How to Publish a New Post (Your Child's Guide)

1. Go to **yoursite.netlify.app/admin**
2. Log in with your email and password
3. Click **"New Newsletter Post"**
4. Fill in the fields:
   - **Title** — what's the post called?
   - **Issue Number** — e.g. Issue No. 13
   - **Category** — pick from the list
   - **Short teaser** — 1–2 fun sentences for the card on the homepage
   - **Article** — write your post in the big editor box
5. Hit **Publish** when you're ready — the site updates in about 30 seconds!

The editor has a toolbar just like Google Docs — bold, italic, headings, bullet lists, and a quote button for those pretty indented quotes.

---

## 📬 Seeing Signups & Submissions (Parent)

Go to **app.netlify.com** → your site → **Forms** to see every newsletter signup and story submission. Set up email notifications there so you get pinged automatically.

---

## 💬 Setting Up Comments (Optional)

1. Enable Discussions on your GitHub repo: Settings → Features → Discussions ✓
2. Go to **giscus.app**, enter your repo name (e.g. `yourname/jos-corner`)
3. Copy the values it gives you
4. In `index.html` find `data-repo="YOUR-GITHUB-USERNAME/jos-corner"` and replace with your real values

---

## 🆓 Everything used here is free

| Feature | Tool | Cost |
|---|---|---|
| Hosting | Netlify | Free |
| Visual post editor | Decap CMS | Free |
| Newsletter signups + story forms | Netlify Forms | Free (100/mo) |
| Comments | Giscus | Free forever |
| Fonts | Google Fonts | Free |
