# Personal Brand Website: Project Guide

This folder holds a ready-to-edit two-page personal brand site (`index.html` + `about.html`), plus a plan for all three phases of the assignment.

---

## Phase 1: Build the site

### Checklist against the assignment

| Requirement | Where it is | Your to-do |
|---|---|---|
| Name + professional headshot | `index.html` hero | Add your last name; save your photo as `images/headshot.jpg` and change `headshot.svg` → `headshot.jpg` in both pages |
| Professional tagline | `index.html` → `.tagline` | Adjust it to your actual focus |
| Call to action | "View My Work" + "Connect on LinkedIn" buttons | Swap `YOUR-PROFILE` for your LinkedIn URL and update the email |
| Short bio in your own voice | `about.html` → "A little about me" | Write it yourself (see the prompts in brackets) |
| Area of marketing interest + why | `about.html` card | Fill in |
| Career goals | `about.html` card | Fill in |
| Skills & Tools (certs, platforms, software) | `about.html` → Skills & Tools | Keep only what's true; add your own |
| At least one academic/creative work example | `about.html` → Featured Work | Add a real project + screenshot |
| Keyword-optimized page title (SEO) | `<title>` in **both** pages | Already done; rename if your focus is different |
| AI disclosure | Footer of both pages | Already included, word for word |

**Find every placeholder:** search the files for `[`, `YOUR-PROFILE`, and `your.email`.

### SEO titles used
- Home: `Aspiring Digital Marketer | Social Media & Analytics | Angelo`
- About: `About Angelo | Digital Marketing Skills, Tools & Portfolio`

They lead with the keywords someone would search for, stay under about 60 characters, and include your name. Each page also has a matching meta description.

### Publishing it for free (pick one)

**Option A: GitHub Pages (this repo)**
1. On GitHub, go to the repo → **Settings → Pages**.
2. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and the `/ (root)` folder, then save.
3. The site will be live at `https://angelo544.github.io/mkt-340/website/` within a few minutes.
   (The repo must be public for free GitHub Pages.)

**Option B: Netlify Drop (no account setup)**
Drag the `website` folder onto https://app.netlify.com/drop to get a live link right away.

**Option C: Wix / WordPress.com / Weebly**
Use this site as your blueprint: copy the same sections, wording, and SEO title into the builder's page settings.

### Save your "Before" state
Before Phase 2, take full-page screenshots of both pages (desktop **and** phone width). On Chrome: DevTools → `Ctrl/Cmd+Shift+P` → "Capture full size screenshot". In git, tag that version so you can always show the original:
```
git tag v1-before && git push origin v1-before
```

---

## Phase 2: Feedback & revision worksheet (bring to class)

### Task 1: Peer feedback (4 classmates)
Write down **specific, actionable** notes only (e.g., "CTA button is below the fold on mobile", not "looks good").

| # | Classmate | Suggestion (paraphrased) |
|---|---|---|
| P1 | | |
| P2 | | |
| P3 | | |
| P4 | | |

### Task 1: AI feedback
**Tool used:** ____________

**Prompt (exact wording):**
> Give me three ways to improve the clarity, professionalism, and marketing effectiveness of this personal brand website for an aspiring digital marketing professional.

| # | Suggestion (paraphrased) |
|---|---|
| A1 | |
| A2 | |
| A3 | |

### Task 2: Revision plan
**Peer-based change I'll implement (from P_):**
- What I'll change: ____________________________________________
- Why this one over the others: _________________________________

**AI-based change I'll implement (from A_):**
- What I'll change: ____________________________________________
- Why this one over the others: _________________________________

> Be specific. Weak: "make the bio clearer." Strong: "Replace the opening sentence of my bio with one that names social media analytics as my focus, so a recruiter sees my niche in the first line."

**A good tiebreaker for choosing:** pick the suggestion that (1) more than one person mentioned, (2) affects the first 5 seconds of a visitor's experience (hero, tagline, CTA), or (3) creates a **visible** before/after difference you can show in your presentation.

---

## Phase 3: 5-minute presentation outline

Aim for about 5–6 slides, mostly images, very little text (you're graded on **not** reading). Times are approximate.

| Time | Slide | What to say (talking points, not a script) | Rubric item |
|---|---|---|---|
| 0:00–0:30 | **Hook / Who I am** | Your name, your tagline, and the one thing you want people to remember | Delivery |
| 0:30–1:30 | **Before** | 1–2 screenshots. Explain which builder you used, what you were going for, and be honest about what wasn't working | Before explanation (25) |
| 1:30–2:30 | **Feedback received** | 3–4 bullets: a few peer notes and the AI's three, plus which AI tool you used. Point out any patterns | Feedback integration (25) |
| 2:30–3:45 | **What I changed and why** | Side-by-side before/after for each of your 2 changes. Say why you chose each one *over the others* and what impact it should have on a visitor or recruiter | Feedback integration + After justification |
| 3:45–4:40 | **After: live site** | Switch to the live site in a browser tab and click through the changed areas | After justification (25) |
| 4:40–5:00 | **Close** | One line on what you learned about personal branding, then point to your CTA ("Connect with me on LinkedIn") | Delivery (25) |

### Delivery tips
- Practice out loud 3 times and time it. Use slide images as cues instead of reading text.
- Open the live site in a tab **before** you start so you aren't loading it in front of the class.
- Treat it as a pitch: "Here's the problem, here's what I heard, here's what I did, here's the result."
- Have a backup: screenshots of the "after" in case the Wi-Fi fails.
