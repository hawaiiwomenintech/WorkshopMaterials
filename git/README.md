Meetup event here: https://www.meetup.com/Honolulu-Women-in-Technology-Meetup-Group/events/265672112/

# Git & GitHub 101

## Introduction

### Git vs. GitHub
- **Git** is a distributed version control system that is free to use. Version control software keeps track of revisions to the codebase. "Distributed" means that Git keeps a copy of the entire codebase on each developer's machine. Git is available on most operating systems, including Mac OS, Linux, and Windows.
- **GitHub** is a software service that uses Git and hosts copies of a codebase and its revision history in the form of a repository. Usually, a single GitHub repository contains the entire codebase for a software project. However, it is also possible to divide a large project into multiple GitHub repositories.

### Why use Git?
- Git makes life much easier for you and your teammates! Instead of having to remember what files you changed, then sending your teammates a copy of those files, you can say goodbye to worry and just `git push` your changes. Your teammates can then retrieve those changes later with `git pull` when they need it.
- Git helps your productivity by relieving stress: You don't have to get upset at future you for deleting rather important code. You can just go back to that point in time and reverse the changes made, if needed.

### Why use GitHub?
- GitHub provides free unlimited public and private repositories, with no limit on the number of collaborators for a public repository, and up to 3 collaborators for private repositories. That's quite a lot for free and more than enough to get started.
- GitHub gives you a chance to showcase your work to future employers and the world via public repositories. And you can always start out with a private repository before making it public.
- GitHub has become a social network of sorts, allowing all kinds of developers to share their work, meet, discuss, or collaborate.

## Getting Started

### Terminal Setup

#### Mac Users

#### Windows Users

### GitHub Setup
1. Create a GitHub account: https://github.com/join
1. **Fork** this repository by clicking "Fork" in the top right-hand corner: https://github.com/honoluluwomenintech/study1-git-and-github-101
  - The process of forking creates a new copy of the forked repository at a new **remote** (like an "address" for where the code lives)
  - That new remote will be your GitHub username and will live at: https://github.com/your-username-here/study1-git-and-github-101
1. After forking and being redirected to the new copy, click on the green "Clone or download" button and copy the HTTPS link (it'll be the same as the URL but you'll see `.git` at the end)

### Git Setup
1. Download Git for your operating system: https://git-scm.com/downloads
1. Install Git by following the installation instructions
1. Have the terminal ready and you're all set!

## Git Commands (+ a few shell commands) -- Part 1

Now we're ready to use Git in the terminal, even though we can also use Git using a graphical user interface (GUI).

### `git clone`
1. Enter `git clone https://github.com/your-username-here/study1-git-and-github-101.git`

### `touch </path/to/filename>`
1. Enter `touch learning.txt`

### `git add </path/to/filename>`
1. Enter `git add learning.txt`

### `git commit -m "Use imperative tense to write a descriptive message"`
1. Enter `git commit -m "Add a new file to learn Git and shell commands"`

### `git push`

## GitHub Processes -- Part 1

### Creating a Pull Request