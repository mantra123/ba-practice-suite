# BA Practice Suite 🎯

An AI-powered SQL & Excel practice tool built for Business Analyst interview prep.

Live site: **[your-username.github.io/ba-practice-suite]()**

---

## What it does

- ♾️ **Unlimited questions** — powered by Claude AI, every question is unique
- 🗄️ **SQL track** — SELECT, JOINs, GROUP BY, subqueries, window functions
- 📊 **Excel track** — VLOOKUP, IF/SUMIF, PivotTables, INDEX MATCH, dashboards
- 📈 **Progress tracking** — streak, accuracy, session stats saved locally
- 🎯 **Topic filters** — drill specific concepts you're weak on
- ✅ **Instant feedback** — hints, solutions, explanations for every question

---

## Setup (5 minutes)

### 1. Fork this repo
Click **Fork** at the top right of this page.

### 2. Enable GitHub Pages
Go to your forked repo → **Settings** → **Pages** → Source: `main` branch → `/root` → **Save**

Your site will be live at `https://your-username.github.io/ba-practice-suite` in ~2 minutes.

### 3. Get your Anthropic API key
1. Go to [console.anthropic.com](https://console.anthropic.com)
2. Sign up / log in
3. Click **API Keys** → **Create key**
4. Copy the key (starts with `sk-ant-`)

> 💡 Cost: ~$0.003 per question. 100 questions ≈ ₹25.

### 4. Add your key to the app
Open your live site → click **Settings** in the top right → paste your API key → **Save key**

That's it. Start generating questions!

---

## Tech stack

- Pure HTML/CSS/JS — zero dependencies, zero build step
- Anthropic Claude API (claude-sonnet) for question generation
- localStorage for progress persistence

---

## Adding to your resume

Under **Projects**, write:

> **BA Practice Suite** | HTML · CSS · JS · Anthropic API | [link]
> Built an AI-powered interview prep tool generating unlimited SQL and Excel questions for Business Analyst roles. Integrates Claude API for dynamic question generation with instant feedback, hint system, and progress tracking.

---

## Local development

No build step needed. Just open `index.html` in your browser.

```bash
git clone https://github.com/your-username/ba-practice-suite
cd ba-practice-suite
open index.html   # Mac
# or double-click index.html on Windows
```

---

Built by Mantra Sura | [LinkedIn](https://linkedin.com/in/yourhandle)
