# frontend-prerequisites-report
Summary report of frontend developer prerequisites
Frontend Developer Prerequisites

1. Installing a Code Editor
When I started looking into frontend, the first tool everyone mentioned was a code editor. This is where we write our HTML, CSS, and JavaScript.The most recommended one is Visual Studio Code (VS Code). It’s free, very popular, and has thousands of extensions. I learned that it makes life easier because it shows colors for code, auto-completes what I type, and even warns me when something is wrong. There’s also WebStorm, which is a paid editor, but it comes with a lot of advanced features built-in.
What I understood:A good code editor is like a digital workspace. Instead of typing in a plain notepad, I get a smart environment that supports me, makes me faster, and keeps my code clean.
2. Essential Extensions – Prettier, ESLint/TSLint
Next, I learned about extensions — these are like small helpers you add into VS Code.
•	Prettier: This formats code automatically. For example, if I type messy code with random spaces, Prettier fixes it to look neat with one click.
•	ESLint: This checks JavaScript code for mistakes or bad habits. For example, it can warn me if I forget a semicolon or if I use a variable in the wrong way.
•	TSLint: Similar, but used for TypeScript.
What I understood:At first, I thought formatting didn’t matter much, but now I see why it’s important. Clean code is easier to read, especially when working in a team. These extensions make sure my code looks professional and avoids silly errors.
3. How the Web Works
This part was really interesting because it explained what happens behind the scenes when I type something like google.com in the browser.
a) HTTP / HTTPS and Request-Response Cycle
•	HTTP: The main language the browser and server use to talk.
•	HTTPS: Same thing, but secure (data is encrypted).
•	Cycle:
1.	Browser sends a request (“Hey server, give me this page”).
2.	Server replies with a response (HTML, CSS, data, images).
3.	Browser displays it on the screen.
What I understood:Every time I click a link or submit a form, this cycle happens. Knowing this helps me debug when something goes wrong, like a failed request.
b) Status Codes
•	200 → Success.
•	301/302 → Redirected.
•	400 → Bad Request (my side).
•	401/403 → Unauthorized or Forbidden.
•	404 → Page Not Found.
•	500 → Server Error.
c) How Browsers Render Pages
Browsers don’t just show HTML directly — they go through steps:
1.	Parse HTML → create DOM Tree.
2.	Parse CSS → create CSSOM Tree.
3.	Combine them → Render Tree.
4.	Layout → figure out positions and sizes.
5.	Paint → draw everything on screen.
What I understood:The DOM and CSSOM are like blueprints. The browser first builds a structure of the page, then paints it. If my code is too complex or changes DOM too much, the page becomes slow.
d) DNS, Hosting, Domains, CDNs
•	Domain: The name, like example.com.
•	DNS: The internet’s phonebook that turns the domain into an IP address.
•	Hosting: The server where website files live.
•	CDN: Extra servers around the world that store copies of files to make websites load faster everywhere.
What I understood:When I type a website name, DNS finds the right server. Hosting delivers the files. A CDN makes sure they come from the nearest place to me, so it feels fast.
e) Web Performance
I learned that performance is about speed and responsiveness:
•	Metrics: First Contentful Paint (FCP), Largest Contentful Paint (LCP), Time to Interactive (TTI).
•	Techniques: compress images, lazy load, minimize CSS/JS, use CDNs.
What I understood:Users hate slow websites. Google even ranks fast websites higher. So as a frontend developer, I must care about performance from the start.
4. Git and GitHub Basics
b) Repositories, Commits, Push, Pull
•	Repository: A project folder tracked by Git.
•	Commit: A saved snapshot of changes.
•	Push: Send changes to GitHub.
•	Pull: Bring changes from GitHub to my computer.
What I understood: Instead of copying folders “project_v1, project_v2”, Git lets me save clean versions step by step.
c) Branching, Merging, and Conflicts
•	Branch: A copy where I work safely.
•	Merge: Combine it back.
•	Conflict: Happens if two people edit the same line → must choose which version to keep.
What I understood: Branching is teamwork’s safety net. Everyone works on features without breaking the main code.
d) Pull Requests & Code Review
A Pull Request is when I ask to merge my branch into the main branch. Others can review, comment, or approve.
What I understood: This is how teams make sure only quality code is added. It’s also a learning moment because I can see feedback from others.
e) .gitignore
A file that tells Git to ignore certain files (like node_modules/ or secrets).
What I understood: This prevents me from uploading unnecessary files and keeps the repo clean.



Refrences 
[1] https://code.visualstudio.com 
[2] https://prettier.io , https://eslint.org 
[3] https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview 
[4] https://developer.mozilla.org/en-US/docs/Web/HTTP/Status  [5]https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/ 
[6] https://www.cloudflare.com/learning/cdn/what-is-a-cdn/ [7]https://web.dev/learn/performance/ 
[8] https://www.atlassian.com/git/tutorials/what-is-git [9]https://www.atlassian.com/git/tutorials/using-branches 
 [10] https://skills.github.com  
[11]https://www.toptal.com/developers/gitignore 



<img width="468" height="649" alt="image" src="https://github.com/user-attachments/assets/029c0a50-3e00-44f1-b226-bd1f44bff3fa" />
