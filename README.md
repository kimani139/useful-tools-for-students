# Useful Tools for Students

A collaborative guide by [kimani139, teammate1, teammate2].

## Table of Contents
- [Introduction](#introduction)
- [VS Code](#vs-code)
- [Notion](#notion)
- [Canva](#canva)
- [How to Contribute](#how-to-contribute)
- [Repo Owner: Review & Merge](#repo-owner-review--merge)
- [Keeping Everyone in Sync](#keeping-everyone-in-sync)
- [Tips for Good Collaboration](#tips-for-good-collaboration)
- [Bonus: Handling a Merge Conflict](#bonus-handling-a-merge-conflict)
- [What to Submit](#what-to-submit)

## Introduction
This guide covers tools that every student should know about. Each section is written by a different team member. Follow the collaboration workflow described in the assignment: create a branch for your section, write your content, open a pull request, and request a review before merging.

## VS Code
**Visual Studio Code** (VS Code) is a free, open-source code editor from Microsoft. It is lightweight, fast, and highly extensible with a large ecosystem of extensions.

### Why Students Should Use It
- Cross-platform: available on Windows, macOS, and Linux.
- Language support: syntax highlighting, IntelliSense (autocomplete), and debugging support for many languages.
- Integrated terminal: run commands without leaving the editor.
- Extensions: add linters, formatters, snippets, themes, and AI-assistants.
- Good for coursework: supports notebooks, version control integration, and remote development (WSL / SSH / Containers).

### How to Get Started
1. Download from: https://code.visualstudio.com/
2. Install recommended extensions for your language (e.g., Python, ESLint, Prettier).
3. Open a project folder and use the Source Control view to work with Git.

### Useful Links
- VS Code Documentation: https://code.visualstudio.com/docs
- Popular extensions: Python, ESLint, Prettier, Live Server

## Notion
**Notion** is an all-in-one workspace for notes, docs, planning, and knowledge bases. Students can use it to organize notes, manage projects, and collaborate on shared documents.

### Why Students Should Use It
- Flexible templates for lecture notes, project trackers, and reading lists.
- Collaborative editing with comments and mentions.
- Embed media and code snippets; create database views for tasks and deadlines.

### How to Get Started
1. Sign up at https://www.notion.so/ and create a workspace.
2. Use a template (Lecture Notes, Task Board) or create a page from scratch.
3. Share pages with teammates and set appropriate permissions.

### Useful Links
- Notion Guides: https://www.notion.so/help

## Canva
**Canva** is an online design tool that helps students create posters, presentations, social media graphics, and more without needing advanced design skills.

### Why Students Should Use It
- Easy drag-and-drop editor with many templates.
- Useful for creating project slides, posters, and visuals for reports.
- Free tier provides many templates and assets.

### How to Get Started
1. Sign up at https://www.canva.com/.
2. Choose a template (Presentation, Poster) and customize text, images, and colors.
3. Download the final design as PDF or PNG.

### Useful Links
- Canva Learn: https://www.canva.com/learn/

---

## How to Contribute
Every team member should do the following for their assigned section:

1. Accept the collaborator invitation (the repo owner must add you as a collaborator in Settings > Access > Collaborators).
2. Clone the repository:

   git clone https://github.com/kimani139/useful-tools-for-students.git
   cd useful-tools-for-students

3. Create a branch named after your section (use lowercase, hyphens):

   git checkout -b add-<your-section>-section

4. Open README.md and replace the placeholder comment for your section with at least one paragraph of content. Use Markdown headings, lists, links, and examples.
5. Stage, commit, and push your branch:

   git add README.md
   git commit -m "Add <Section Name> section"
   git push origin add-<your-section>-section

6. On GitHub, click Compare & pull request, fill the PR title and description, request a review from the repo owner or teammates, and create the pull request.

## Repo Owner: Review & Merge
The repo owner (project maintainer) should:

1. Go to Pull requests → open the PR.
2. Click Files changed to review the content.
3. If content is fine, choose Review changes → Approve → Submit review.
4. Click Merge pull request → Confirm merge.

If changes are needed, choose Request changes and leave comments; the contributor should update their branch and push again.

## Keeping Everyone in Sync
After a PR is merged, every team member should update their local repository:

git checkout main
git pull

Before starting new work, always pull the latest changes to avoid conflicts.

## Tips for Good Collaboration
- Use descriptive branch names: add-notion-section, fix-typo-in-intro.
- Write clear commit messages describing what you changed.
- Keep pull requests focused (one section per PR).
- Review teammates' PRs carefully and leave constructive comments.

## Bonus: Handling a Merge Conflict
If two people edit the same lines, a conflict can occur.

1. On GitHub, the second PR will show "This branch has conflicts that must be resolved". Click Resolve conflicts.
2. GitHub shows both versions with conflict markers (<<<<<<<, =======, >>>>>>>). Edit the file to keep the desired content and remove markers.
3. Click Mark as resolved → Commit merge.

Locally, resolve conflicts by pulling main, merging, editing the file, committing, and pushing the branch again.

## What to Submit
When you are done, provide the following to the instructor:

- Repository link: https://github.com/kimani139/useful-tools-for-students
- GitHub usernames of all team members (so contributions can be verified)
- Evidence that each team member contributed via a separate pull request (Closed PRs tab) with descriptive titles and review comments
- Final README with properly formatted Markdown

---

If you want, I can now create branches and commit the three section drafts on separate branches so each teammate has a ready branch to open a PR from. Reply: "Create branches with drafts" to have me create add-vscode-section, add-notion-section, and add-canva-section and push drafted content for each.
