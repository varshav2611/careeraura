# CareerAura

**A free, 3-minute career-guidance tool for teens in India.**

🔗 **Live:** [careeraura.netlify.app](https://careeraura.netlify.app)

## The problem

Only an estimated 13% of Indian students receive any professional career guidance before choosing a stream or degree — a decision that shapes the next decade of their life. Most existing tools stop at "you're a Creative Type!" with no concrete next step.

## What it does

CareerAura is a 7-question quiz that maps a student's answers across 10 career clusters (Technology, Medicine, Business, Design, Law, Science, Finance, Media, Social Impact, Psychology), then returns their top 5 matches — each with:

- **A real pathway** — school focus, entrance exams, degree, and early roles
- **Tiered, zone-filterable colleges** — sourced from [NIRF 2025](https://www.nirfindia.org/Rankings/2025/Ranking.html) category rankings, split into Tier 1 (reach) and Tier 2 (accessible), filterable by North/South/East/West/Central India
- **Free prep resources** — matched per career (NTA Abhyas, SWAYAM/NPTEL, DIKSHA, Khan Academy India, and others)
- **Alumni outreach templates** — a ready-to-use message template and a live LinkedIn search link per college, teaching the "ask for 15 minutes" skill directly
- **Skills-of-the-future context** — sourced from the [WEF Future of Jobs Report 2025](https://www.weforum.org/publications/the-future-of-jobs-report-2025/) and [India Skills Report 2026](https://news.careers360.com/india-skills-report-2026-employability-56-35-pc-ai-tools-digital-gig-economy-workforce-global-talent-hub)

It explicitly frames itself as a conversation-starter with a parent, teacher, or counselor — not a replacement for one.

## Why I built it

I have a background in HR business partnering, workforce planning, and organizational psychology (15+ years across pharma and telecom), plus volunteer experience. This project sits at the intersection of that experience and a genuine gap I kept seeing: kids making irreversible academic decisions with almost no structured guidance.
I built it using claude.

## How it's built

- Single-page vanilla HTML/CSS/JS — no framework, no backend, no build step
- Deployed on Netlify
- Installable as a Progressive Web App (manifest + icons included)
- Privacy-safe analytics via [GoatCounter](https://goatcounter.com) — no cookies, no personal data collected, deliberately chosen given the audience includes minors
- Built using Claude (Anthropic) as an AI development partner — I directed the product decisions, content, sourcing, and design; Claude implemented the code

## Status

This is a **pilot-stage prototype**, not a launched product. It hasn't yet been tested with a real student cohort — that's the next step, in partnership with the NGOs named above. Feedback is collected in-app via a simple 👍/👎 widget.

## Data sources

| Data | Source |
|---|---|
| College rankings | [NIRF 2025](https://www.nirfindia.org/Rankings/2025/Ranking.html) category-wise rankings, cross-checked with [Collegedunia](https://collegedunia.com) |
| Global skills | [WEF Future of Jobs Report 2025](https://www.weforum.org/publications/the-future-of-jobs-report-2025/) |
| India-specific skills | [India Skills Report 2026](https://news.careers360.com/india-skills-report-2026-employability-56-35-pc-ai-tools-digital-gig-economy-workforce-global-talent-hub) (ETS/CII/AICTE/AIU/Taggd), [NASSCOM](https://www.nasscom.in) |
| Learning platforms | [nasscom FutureSkills](https://futureskills.nasscom.in/) / [FutureSkills Prime](https://www.futureskillsprime.in/) (MeitY-backed) |

## License

Free to use, adapt, and share for non-commercial, educational purposes.
