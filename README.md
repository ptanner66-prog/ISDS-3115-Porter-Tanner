# Porter Tanner: Personal Website

**Live site:** https://ptanner66-prog.github.io/ISDS-3115-Porter-Tanner

**Repository:** https://github.com/ptanner66-prog/ISDS-3115-Porter-Tanner

This repository contains the source code for my personal portfolio website built for ISDS 3115 at Louisiana State University. Developed with semantic HTML5, modern vanilla CSS, and lightweight JavaScript, the site showcases my background in economics and information systems, legal data engineering work at Motion Granted, self-hosted homelab infrastructure, and professional resume.

## Reflection
I spent my entire summer vibecoding with different tools and moved away from the IDE months ago after I learned the basics and models got more capable. Going into this seemed like a walk in the park, but that was not the case—which taught me even more about coding with LLMs. Since leaving the IDE, I didn't realize how lazy I had become allowing agents to do almost everything for me. I got so caught up in multi-agent harnesses and optimizing my workflow that I lost control of my codebase.

A clear example occurred when building the homelab server rack on the projects page. I asked the agent to render stacked Dell PowerEdge server faceplates, but it returned a 3-unit layout that left awkward dead space and mismatched vertical gaps. Because the agent couldn't visually balance the CSS container heights, flexbox spacing, and the image aspect ratios from prompts alone, the layout kept falling flat. It wasn't until I stepped directly into the IDE, inspected the DOM elements and CSS box model, and explicitly directed the layout to 4 tightly stacked units that the design snapped into place.

Using an IDE for the first time in a while helped me realize that no matter how capable the coding agent is, I must maintain deep technical understanding and active control of my codebase. Since this project, I have migrated my primary workflow into VS Code. I was able to take what I learned from multi-agent orchestration and combine it with the hands-on control and code-level inspection I had veered away from, creating a dev workflow that allows agents to work at a frontier level while keeping full ownership of my repository in my hands.

