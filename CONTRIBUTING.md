# Contributing

Thanks for coming to society this semester!

## Join the society github organization

Use the [join tool](https://github.com/Web-Design-Development-Society/join-tool) to easily join our github org.

Benefits

- Make it easier to set up teams
- Make it easier to manage repo permissions
- Membership of the org listed on your github profile

## Webdev Environment Setup

- Install [git](https://git-scm.com/downloads)
- Install [vscode](https://code.visualstudio.com/)
- Install [node.js & npm](https://nodejs.org/en/download)

Recommended Quality-of-life Extensions

- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) to autoformat your code
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) to add more icons to file explorer
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) if you're using it
- [Snippet Studio](https://marketplace.visualstudio.com/items?itemName=AlexDombroski.snippetstudio) to create reusable custom autocompletion

## Learn to Code Together

There are several approaches to code together as a team. You should decide together how you can best collaborate and achieve your goals

### Local Branches and Merging

Learn the maximum amount of [Git](https://git-scm.com/docs) and skip learning Github's PR system

1. Branch off of main
2. Code on a branch with your name
3. Pull main, and merge the your branch
4. Resolve conflicts if necessary
5. Push to github
6. Recreate or backmerge your branch to keep it up to date with main

Benefits

- Learn the most about git the fastest
- Doesn't require learning much about Github

Drawbacks

- Requires granting everyone push access (slower setup)
- More difficult to see what others are working on

### Local Branches and Github PRs

Use a good mix of git and github for a balance of speed and benefits.

1. Branch off of main
2. Code on a branch with your name
3. Push branch and [create PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
4. Merge via PR. You're told beforehand if conflicts will occur
5. Pull main and delete branch

Benefits

- Many companies prefer to collaborate this way
- Optionally perform code review or collaborate in PRs
- PRs give a good summary of what code changed.

Drawbacks

- Requires granting everyone push access (slower setup)
- May be slower than just merging locally

### Github Forks & PRs

Create your own [copy of the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) to use throughout the semester. Periodically click `contribute` and `sync fork` to merge code together.

1. Click `Fork` to copy the repository
2. Optionally create branches to make keeping fork up to date easier
3. Make your changes
4. Create and merge PR
5. Use remote tracking branches and/or `sync fork` to resolve conflicts

Benefits

- Learn the "open source way" of contribution
- Easy for repo admins to see what your working on
- Requires a very minimal understanding of git (until you have merge conflicts)

Drawbacks

- Have to create a whole new github repository instead of just branching
- Smaller setup collectively, but may feel like more individual setup

_Read more about [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)_

### Live Server

[Live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) allows you to edit code simultaneously in VS Code (similar to google docs).

Benefits

- Easy
- No Merge Conflicts

Drawbacks

- Mostly useful for collaboration code in society
- Missed opportunity to learn Git & Github
