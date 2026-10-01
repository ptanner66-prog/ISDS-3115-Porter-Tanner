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
I spent my entire summer vibecoding with different tools and moved away from the IDE months ago after i learned the basics 
and models got more capable. Going into this seemed like a walk in the park for me but that was not the case which taught 
me even more about coding with LLMs. Since leaving the IDE I didn't realize how lazy I had become allowing agents to do almost
everything for me. I got so caught up in the multi agent harnesses and optimizing my workflow that I lost control of my codebase. 
Using an IDE for the first time in a while helped me realize that no matter how good the coding agent is, I still must keep total control
of my agents. I learned that I had little control and understanding of my code when using claude code desktop app or something or that nature.
Since this project, I have migrated my workflow over to VS code and is my go to dev space now. I was able to take what i learned with multi agent orchestration 
and combine it with the control aspect that i veered away from to create a dev workflow that allows agents to work at frontier level while also keeping control
of my repo in my hands.

