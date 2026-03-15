# GenixAI — Complete Deployment Guide
## Step-by-Step: Zero Cost, Live in 1 Hour

---

## WHAT YOU HAVE
- `index.html` — Complete app (landing page + 25 AI tools + 55+ languages)
- `api/generate.js` — Serverless function (hides your API key)
- `vercel.json` — Vercel configuration
- This README

---

## STEP 1 — Get Your FREE Anthropic API Key (10 min)

1. Go to: https://console.anthropic.com
2. Click "Sign Up" — use Google or email
3. Verify your email
4. Go to "API Keys" in left sidebar
5. Click "Create Key"
6. Copy the key (starts with `sk-ant-...`)
7. SAVE IT — you only see it once!

FREE CREDIT: Anthropic gives you $5 free credit. At ~$0.002 per generation, that's 2,500 free generations!

---

## STEP 2 — Create GitHub Account & Upload Files (10 min)

1. Go to: https://github.com
2. Sign Up (free)
3. Click "New repository" (green button)
4. Name: `genixai`
5. Set to PUBLIC
6. Click "Create repository"
7. Click "uploading an existing file"
8. DRAG AND DROP these files/folders:
   - index.html
   - vercel.json
   - api/ (folder with generate.js inside)
9. Click "Commit changes"

---

## STEP 3 — Deploy on Vercel (FREE, 5 min)

1. Go to: https://vercel.com
2. Click "Sign Up" — choose "Continue with GitHub"
3. Authorize Vercel
4. Click "Add New Project"
5. Find "genixai" repo → Click "Import"
6. DO NOT CHANGE ANYTHING
7. Click "Deploy"
8. Wait 2 minutes → Your app is LIVE!

You'll get a URL like: https://genixai.vercel.app

---

## STEP 4 — Add Your API Key (5 min)

This is THE most important step — without this, AI won't work.

1. In Vercel, go to your project dashboard
2. Click "Settings" tab
3. Click "Environment Variables" in left menu
4. Click "Add Variable"
5. Name: `ANTHROPIC_API_KEY`
6. Value: paste your key (sk-ant-...)
7. Click "Save"
8. Go to "Deployments" tab
9. Click the 3 dots "..." on latest deployment
10. Click "Redeploy"
11. Wait 1 minute → Now AI works!

---

## STEP 5 — Get a Free Custom Domain (Optional, 5 min)

Option A — Free Vercel domain:
Your app already has: https://genixai.vercel.app (free forever)

Option B — Buy .com domain ($10-12/year):
1. Go to https://namecheap.com
2. Search "genixai.com" or "getgenixai.com"
3. Buy it (~$10)
4. In Vercel → Settings → Domains → Add domain
5. Follow DNS instructions

---

## STEP 6 — Set Up Payments with Stripe (FREE)

1. Go to: https://stripe.com
2. Sign Up (free)
3. Complete verification (takes 1-2 days)
4. Go to "Products" → "Add Product"

CREATE 3 PRODUCTS:

Product 1:
- Name: "GenixAI Pro"
- Price: $12 / month (recurring)
- Copy the Payment Link URL

Product 2:
- Name: "GenixAI Business"
- Price: $29 / month (recurring)
- Copy the Payment Link URL

5. Open your index.html
6. Search for "Upgrade to Pro — $12/mo"
7. Add: onclick="window.open('YOUR_STRIPE_LINK')"
8. Do same for Business plan
9. Re-upload to GitHub (same drag & drop)
10. Vercel auto-deploys!

---

## YOUR APP IS NOW LIVE!

URL: https://genixai.vercel.app (or your custom domain)
Cost to run: $0/month until 100+ paying users
API cost: ~$0.002 per generation (very cheap)

---

## MARKETING — DO THIS ON DAY 1

### Reddit Posts (copy-paste these):

**r/entrepreneur:**
```
I built a free AI tool that generates content in 55+ languages.
Social captions, resumes, ads, emails, SEO copy — all in one place.
Works in Urdu, Arabic, Hindi, Spanish, French, basically any language.
Free to try: [your URL]
Would love feedback!
```

**r/SaaS:**
```
Built a multilingual AI content generator — 25 tools, 55 languages
[your URL]
Still in beta, completely free right now.
```

**r/digitalnomad, r/socialmedia, r/pakistan, r/India:**
Same message, slightly different intro.

### Facebook Groups to post in:
- "Digital Marketing" (2.5M members)
- "Social Media Marketing" (1M members)  
- "Entrepreneurs" (500K members)
- Local groups in Pakistan, India, UAE

### ProductHunt:
- Submit at: https://producthunt.com/posts/new
- Best day: TUESDAY or WEDNESDAY at 12:01 AM Pacific Time
- Title: "GenixAI — AI Content Generator in 55+ Languages"

---

## $1,000/MONTH ROADMAP

Week 1-2: Get 200 free users (Reddit, Facebook, Twitter)
Week 3: Convert 20 to paid = $240/month
Week 4: Scale to 50 paid users = $600/month
Month 2: 85+ paid users = $1,020/month ✅

Key: Post EVERY DAY on social media showing real outputs.
Show before/after. Show different languages working.
People trust what they can see.

---

## SUPPORT

If something doesn't work:
1. Check Vercel "Functions" logs for errors
2. Verify ANTHROPIC_API_KEY is set correctly
3. Make sure api/generate.js is in the /api folder on GitHub

You've got this! 🚀
