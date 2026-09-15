# ISDS 3100: Information Systems Foundations
Fall 2026

**AI Lab: Vibe Coding and Agent Skill development**

| Department | Contact |
| :--- | :--- |
| **E.J OURSO COLLEGE OF BUSINESS**<br>SDEIS DEPARTMENT<br>Nicholson Extension<br>Baton Rouge, LA 70803 | **GABRIELE PICCOLI, PH.D.**<br>2219 Business Education Complex<br>Tel: +1 (225) 578-8184<br>gpiccoli@lsu.edu |

---

The goal of this semester project, to be completed with a pair-programming approach, is to practice what we learn in class. Specifically, the project focuses on the Generative AI portion of the course. We will practice vibe coding, and we will learn about (and create) agent skills. 

If you are wondering why, as a future manager, you should be learning to vibe code and to create agent skills, here is some food for thought:
* You may never write software for a living, but you will increasingly **direct** systems that do work for you. 
* Vibe coding and building agent skills are small, concrete examples of the core managerial move in the age of GenAI. 
* You must be able to clearly specify what a capable system should do, encode that specification so it runs consistently, and judge whether the output is achieving the expected levels of performance. 

You are the navigator. The AI can produce the code or automate the work, but you must decide what **performance** and **results** must be. That judgment is the part that doesn’t get automated. The more you practice, the better you become at it. These are frontier skills for a manager. Now is your time to develop them.

## General requirements and expectations
The two separate projects described here are independent. For each one you will be working in teams of two, but you will be able to change your partner once the vibe coding project is complete. 

> [!IMPORTANT]
> It is expected that you will act as a professional, reliable partner to your teammates. If your teammate on the vibe coding project does not share your same commitment to quality work, professionalism or learning, you should select a new teammate for the second project. 

## Pair programming
In this project you choose a collaborator and you work as paired programmers. Pair programming is an agile software development technique (see Chapter 10 of your book), where two programmers work together at a single workstation to complete a coding task (e.g., to vibe code a website). 

* **Driver Role:** One of the two developers takes the driver role and writes the code. In a vibe coding environment, the driver is not actually writing the code but instead prompting the generative AI system that writes the code. 
* **Navigator Role:** The other developer reviews the code as it is being typed and thinks at a higher level about the project, spotting the potential for bugs, architectural challenges, and new features.

## Calendar
> [!WARNING]
> All work is due on the day of the deadline at 11:59:59 PM unless otherwise communicated. There is a **30% penalty per day** of delayed submission on all work. 

The updated list of key dates and deadlines for the semester is available on Moodle.

## Grading and evaluation
See syllabus for grading percentage of each element of the semester project. 
* For the **vibe coding project** each person is assigned the grade relative to their own website (i.e., grading is individual). 
* On the **agent skills project** the team produces one artifact (i.e., one agent skill) and shares the same grade. 

We assume equal contribution to the final deliverable. It is your responsibility to reach out to the instructor or GA early in the project if you believe that your teammate is not contributing adequately to the effort. 

---

## Website design and GitHub hosting
The first project consists in creating a personal website, one for each team member. You will take turns, working on one website at a time in the pair programming modality. 

> [!NOTE]
> While you will be pair programming each website, grading will be individual – each developer is graded on their own personal website (see grading section). 

> [!WARNING]
> You **shall not** use any website builder (e.g., Wix, Squarespace) or backend providers (e.g., Lovable, Supabase). Rather you will create the website on your computer using Google’s Antigravity IDE, test it, and then upload the code to GitHub (make a free account if you don’t have one yet). 

The following are the minimum requirements for each of your websites:
*   **Clear design:** You must choose a *hybrid layout* for your design. Your high-level content (about, skills, contact) must be in a single-page design. You must have at least one separate page to house your resume and a second separate page to describe one project that highlights your abilities or passions.
*   **Content:** Your website should open on your single-page and provide brief descriptions of you (profile), your skills (competencies), your experience (jobs held) and your contact. Your Resume and Project(s) page will expand on those highlights.
*   **Design elements:** The visuals, graphic elements, navigation appearance and text must work together to quickly communicate your purpose and orient users to your competencies and experiences. Your website must have a consistent page design, be professional and targeted to potential recruiters (your main audience). 
*   **Hosting:** Your code must be on your computer and be pushed to GitHub in your own GitHub account. Set the repository to be public for inspection. 
*   **Publicly reachable:** Your website should be hosted and publicly reachable in one of the following two free hosting services: GitHub Pages or Cloudflare Pages (both free). If you so choose, you can purchase a URL and point it to your website, but this is not a requirement. 

---

## Vibe Coding Primer
This handout helps you get started on your project using Google Antigravity as your IDE. No prior coding, GitHub, or command-line experience is assumed. The best approach would be to practice this with the classic “Hello World” page so that when you have your vibe coded website built you can move efficiently. 

We will cover:
1. Set up your tools and accounts (one time)
2. Build and test your site on your own computer
3. Upload to GitHub
4. Preview the website locally, iterate and push major improvements

> [!IMPORTANT]
> You must be able to **see and edit the actual code** (the `.html`, `.css`, `.js` files) in Antigravity IDE’s editor. No Wix, Squarespace, Lovable, v0, or any tool that hides the code from you. Antigravity’s agent *writes* the code, but the actual files it creates you can inspect, edit, and own (that’s the point of vibe coding).

### Set up your tools and accounts (do this once)
1.  **Google Antigravity IDE (free):** Download the installer from the official page at antigravity.google and run it. Note that there are multiple products called Antigravity and you need to get the Antigravity IDE. Launch the installer:
    *   When prompted, choose *Start fresh*.
    *   Pick a theme.
    *   On the Agent Manager / mode screen, choose *Review-driven development* (recommended). You stay in control and approve actions, while the agent helps. This is the approach we want for learning.
    *   Sign in with a *Google account* (create a free one if you don’t have one or don’t want to use an existing one) and select a model (*Gemini 3 Pro* is the default; Claude and others may also be listed and may give you limited usage. You can experiment with various models later).

    Antigravity is built on a familiar VS Code–style editor, so the layout will feel standard: a file editor in the middle, an Agent Manager panel where you give the AI instructions, and a built-in browser preview for testing.
2.  **Git (free):** Git is an open-source distributed version control tool. It is used by software developers to track changes in files and coordinate work among multiple people. It is the software you will use to *push* your code to GitHub. Before the installation check if you already have it. For example, on a Mac you can check in the Terminal app by typing `git --version`. If Git isn’t installed, your Mac will offer to install it. If needed, you can download Git from git-scm.com and install it by following the prompts.
3.  **GitHub account (free):** Sign up at github.com. Pick a professional username, if you don’t have an account yet, this is your opportunity to create one that recruiters will see. Be smart and be professional. `jane-smith` – professional. `Xxgamergirlxx` – not professional. 

Evaluate progress by launching Antigravity IDE, typing `git --version` and verifying that Git is properly installed. Visit your new GitHub account and verify that it is created and you can access it with your credentials. Create the standard “hello world” project to make sure everything works correctly ([GitHub Hello World Guide](https://docs.github.com/en/get-started/using-github/hello-world)). Once you clear this checkpoint you are in business and ready to work on your personal website.

### Build and test your site on your own computer
The following requirements will help you keep the structure of your project clean and your work simple and efficient. 
1. Create a new folder in a specific location (e.g., the folder with your class documents). Give it a clear name (e.g., `firstname-website`). Learn and apply good naming conventions (e.g., no spaces, all lowercase, dash separators). 
2. Initialize the main files in your website. You can create them yourself or prompt the agent appropriately to create them. Start with the following files:
   *   `index.html` — this is your home/landing page (the single-page part: Profile, Skills, Experience, Contact). Browsers and GitHub Pages look for `index.html` first.
   *   `resume.html` — your resume page.
   *   `project.html` — your project page.
   *   `styles.css` — your shared styling, so every page looks consistent.

To vibe code with the agent, make sure the Agent Manager panel is open, make sure your folder is selected, choose a model, and simply describe what you want in plain English. For example: 
> *“I want to create my personal website. It has a very specific structure. Create the following four files to initialize our project: index.html, resume.html, project.html and styles.css.”* 

To verify the work of the agent, you should see files in the Explorer side panel (on the left). Open each one and browse the code. If you know the language used (e.g., HTML) you will recognize what is going on. If you don’t know the language, it’s ok. For this project you are not expected to directly modify any code (but you of course can if you so choose). The agent writes the code into your files. The key learning point here is that, by having direct access to the code and being able to inspect it, you directly own all the elements of your final product. 

Once you are comfortable with the workflow and the tools you can iterate by prompting the agent to make changes and improve your website as you see fit with follow-up instructions (e.g., “use a navy and white palette,” “the contact link is broken, please verify what is wrong”).

> [!TIP]
> A great feature of GenAI agents is that you can ask them to explain what they are doing and what is going on. This is perhaps the most valuable part of this project, and you should take advantage of it! As you interact with the agent and ask questions, you are improving your ability to architect systems and code. 

Make sure to not accept anything you don’t understand. Simply ask the agent to explain why a task is needed, why something is not working, whether there are better designs available, or what it suggests doing in specific situations. You will be amazed by how much you learn through these “coaching” sessions. As you get better and more comfortable with the agent you can dive deeper into more complex tasks. 

### Upload to GitHub
GitHub will serve not only as the host of your final product, but also as a remote backup of your work. So, you should not wait to complete your project before you push it to the repo. You should instead do so as you go along, at the end of each day of coding or when you complete major milestones. We suggest that you do your first commit and push once you have the bare bone skeleton of your web site. 

First, you will create the repository (repo as developers call it) on GitHub. There are several ways to do so (see [GitHub Docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)). You are probably best off doing it on the GitHub website directly. 
* You will choose a repo name (make it meaningful). 
* You must set the repo to **public** to later publish as a GitHub page. 
* Make sure to leave the README file empty for this repo, you will add it later. 

Second, with the repo created, you can push your code. You can do so from the Terminal app or directly from the Antigravity IDE. The first time you will need to sign in with your credentials. The sign in process evolves over time, so review the requirements before your first commit. You will know that you have successfully completed this step when refreshing the repo page on GitHub will show you the updated code, the correct timestamp, and the latest commit message.

### Preview the website locally, iterate and push major improvements
At various stages of development, you can ask the agent to preview the work (e.g. *“Start a local preview of this site and open it in the browser”*). Antigravity IDE serves your site in its built-in browser preview. Every time the code changes, refresh the preview to see it. 

**This is your iteration workflow: change → inspect → refine.** 

As you get comfortable with the vibe coding iteration process, ask your agent how to start a local server so you can preview the website in your browser (rather than the built-in browser of Antigravity IDE). Sometimes websites look different on different browsers (e.g., Chrome, Safari), so previewing it in multiple browsers is a good website design practice. 

Once you like the results in terms of content and design, here is a checklist:
*   [ ] Every navigation link works.
*   [ ] The design looks consistent across all three pages.
*   [ ] The content reads well and looks professional to a recruiter.
*   [ ] Resize the preview narrow — does it still look OK on a phone-width screen?

At this point you are mainly testing locally; nothing is on the public internet yet. But once you make major improvements you should push them to your GitHub repo. Follow the sequence of Git commands: 
*   `git add .`
*   `git commit -m "descriptive commit message"`
*   `git push`

Note that you can push code from the terminal or from Antigravity IDE. You will likely identify your preferred method and stick with it. Remember, Git is a version control system that allows you to revert to previous commits if you make mistakes or don’t like a set of improvements. GitHub is your remote backup, it ensures you don’t lose your work accidentally. Use these tools to vibe code like a pro.

### Publish your personal website live with GitHub Pages
Your code is on GitHub, but not yet visitable as a public website. To publish the work for free as GitHub Pages you follow these steps:
*   In your repository, click Settings (top menu) → Pages (left sidebar).
*   Under Branch, choose main, keep the folder as / (root), and click Save.

Wait a few minutes, then refresh the Pages settings screen. A green box appears with your live address:
`https://YOURUSERNAME.github.io/firstname-website/`

This is your public website, the one you will share with recruiters, family and friends. You can see why choosing a professional and descriptive repo name is important. Test every page and link on the live version of your website using the public URL. Be sure to test on multiple browsers and multiple devices – PC, tablet, smartphone. Your website should be responsive and display well on each platform. You will likely have to get back into Antigravity IDE and iterate further. Pushing the new code to GitHub will automatically update the public website.
