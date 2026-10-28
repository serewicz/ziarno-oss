# Module 3: Contributing your first patch

**Level:** Foundation  
**Time:** about 4 hours  
**Needs:** a laptop or a phone with a browser; some exercises need an internet connection once.

## Learning objectives
By the end you will be able to:
- Use git on the command line for clone, branch, commit, and push
- Open an issue and a pull request
- Respond politely to review feedback

## Lesson outline
1. What git is, and why it is separate from GitHub or GitLab
2. Clone, branch, commit, push
3. Forks and pull requests (GitHub) or merge requests (GitLab)
4. How to read CONTRIBUTING.md and pick a good first issue
5. Writing a clear issue and a clear PR description
6. Getting review, making changes, and being patient

## Hands-on exercise: Make a first pull request
1. Create a free account at https://github.com/ (click **Sign up**, follow the steps, confirm your email).
2. Install git. On Windows, download it from https://git-scm.com/ and accept the defaults. On Ubuntu, open Terminal and type `sudo apt install git`.
3. Open https://github.com/firstcontributions/first-contributions and read the README.
4. Click **Fork** at the top right. Then click **Create fork**.
5. On your fork, click the green **Code** button and copy the HTTPS address.
6. In Terminal (or Git Bash on Windows), type `git clone ` and paste the address. Press Enter. Then type `cd first-contributions`.
7. Type `git switch -c add-your-name` and press Enter.
8. Open the file `Contributors.md` in a text editor. Add your name on a new line. Save.
9. Type `git add Contributors.md`, then `git commit -m "Add my name"`, then `git push -u origin add-your-name`. Enter your GitHub username and a personal access token if asked (the README explains how to make one).
10. Go back to your fork in the browser. Click **Compare & pull request**, then **Create pull request**.
11. Wait for the review. Read any comments and reply.

## Quiz
1. What is the difference between git and GitHub?
2. What file usually explains how to contribute?
3. What do you do when a reviewer asks for changes?

<details><summary>Answers</summary>

1. Git is the tool that tracks changes. GitHub is a website that hosts git repositories.
2. CONTRIBUTING.md.
3. Thank them, make the change on the same branch, and push again.

</details>

## Free resources
| Resource | License |
|---|---|
| [First Contributions](https://github.com/firstcontributions/first-contributions) | MIT |
| [Software Carpentry: Version Control with Git](https://swcarpentry.github.io/git-novice/) | CC BY 4.0 |
| [Software Carpentry: The Unix Shell](https://swcarpentry.github.io/shell-novice/) | CC BY 4.0 |
| [Pro Git book](https://git-scm.com/book/en/v2) | CC BY-NC-SA 3.0 |
| [GitHub Hello World](https://docs.github.com/en/get-started/start-your-journey/hello-world) | CC BY 4.0 (GitHub docs) |
| [GitLab tutorials](https://docs.gitlab.com/tutorials/) | CC BY-SA 4.0 |
| [Open Source Guides: How to Contribute](https://opensource.guide/how-to-contribute/) | CC BY 4.0 |
| [Linux Foundation LFD102: A Beginner's Guide to Open Source Software Development (free)](https://training.linuxfoundation.org/training/beginners-guide-open-source-software-development/) | Free course; LF terms |


## More free resources from across tech

Vendor-neutral where possible. Vendor material is labeled. Links checked October 2026.

| Resource | Provider | Cost | License or terms |
|---|---|---|---|
| [GitHub Skills (free interactive courses)](https://skills.github.com/) | GitHub | Free with a GitHub account | MIT (course repos); vendor platform |
| [Open Source Guides: How to Contribute](https://opensource.guide/how-to-contribute/) | GitHub | Free | CC BY 4.0 |
| [GitLab docs: Getting started](https://docs.gitlab.com/user/get_started/) | GitLab | Free | CC BY-SA 4.0 |
| [How to contribute to freeCodeCamp](https://contribute.freecodecamp.org/) | freeCodeCamp | Free | BSD-3-Clause |
| [Software Carpentry: Version control with Git](https://swcarpentry.github.io/git-novice/) | The Carpentries | Free | CC BY 4.0 |
| [Python Developer's Guide](https://devguide.python.org/) | Python Software Foundation | Free | CC0 / PSF terms |

Links checked October 2026. If one breaks, please open an issue.
