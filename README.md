# Porter Tanner: Personal Website

**Live site:** https://ptanner66-prog.github.io/ISDS-3115-Porter-Tanner/
**Repository:** https://github.com/ptanner66-prog/ISDS-3115-Porter-Tanner

ISDS 3100 (Fall 2026), AI Lab: Vibe Coding. Porter Tanner · ptanne6@lsu.edu · Instructor: Gabriele Piccoli, Ph.D.

## What it is
My personal website, built by directing an AI coding agent and hosted on GitHub Pages. It uses a hybrid layout:

| Page | File | What's on it |
|---|---|---|
| Home (single page) | `index.html` | Profile, skills, experience, contact |
| Resume | `resume.html` | Education, ventures, earlier work, skills |
| Projects | `project.html` | Motion Granted citation database, Agentic Operator To-Do List, home lab server |
| Shared styling | `styles.css` | One stylesheet for all three pages |

The site files live in [`website-design-and-github-hosting/porter-website/`](./website-design-and-github-hosting/porter-website/). Images are in `graphics/`. The root `index.html` redirects visitors to that folder so the GitHub Pages URL opens the site directly.

It's plain HTML and CSS with a few lines of inline JavaScript (copy-email button, screenshot zoom), and it uses no website builder or backend.

## Run it locally
```bash
cd website-design-and-github-hosting/porter-website
python3 -m http.server 8000
# open http://localhost:8000
```

## Reflection

<!--
DIRECTIONS: delete this comment and write your reflection here, in your own words.

The rubric (10% of the grade) wants ONE specific, insightful reflection:
a concrete technical point plus a clear learning from directing the agent.
Generic lines like "I learned a lot about AI" score 4-6/10. Aim for 3-6 sentences:

  1. The moment: what you asked the agent for, and what came back wrong or surprising.
  2. The technical why: what was actually going on (name the HTML/CSS/JS detail).
  3. The learning: what you now do differently when you direct an agent.

Real moments from this build you could pick from (use one, and tell it your way):
  - The "Contact" button used a mailto: link, which does nothing on computers with no
    default mail app, so we added a copy-email button as a fallback.
  - The Motion Granted logo would not grow inside its badge because the <img> had a
    fixed width="32" attribute in the HTML; the CSS change alone did nothing.
  - The first design the agent produced (purple glassmorphism) looked like every
    other AI-made site; you had to specify "sleek black" and reject the generic output.
  - Phone view: the original scaffold hid the nav entirely under 768px
    (display: none), so phone visitors could not navigate at all.
-->

---

*The agent skill project for the second half of the course is in [`agent-skill-design-and-deployment/`](./agent-skill-design-and-deployment/).*
