# A02

How to Use Git, Webstorm, and Github:

Step 1: Install WebStorm
- Download WebStorm from JetBrains: [https://www.jetbrains.com/webstorm/download](https://www.jetbrains.com/webstorm/download)
- Install and launch the application.
- Sign in with your JetBrains account or start a free trial.

Step 2: Create a New Project
- Open WebStorm.
- Click **New Project**.
- Choose a project type (e.g., Node.js, HTML, etc.).
- Set the project location and click **Create**.

Step 3: Initialize a Git Repository
- Right-click your project folder in the Project pane.
- Select **Git** → **Enable Version Control Integration**.
- Choose **Git** from the dropdown and click OK.
- This creates a local **Repository**.

Step 4: Connect to GitHub
- Go to **File** → **Settings** → **Version Control** → **GitHub**.
- Log in using your GitHub credentials or token.
- Create a new GitHub **Repository** or link to an existing one.

Step 5: Clone a GitHub Repository
- In WebStorm, go to **File** → **New** → **Project from Version Control**.
- Paste the GitHub URL and click **Clone**.
- WebStorm will download the project and open it.

Step 6: Make Changes and Commit
- Edit your code or add new files.
- Go to **Git** → **Commit**.
- Write a clear commit message (e.g., `Feature: added login form`).
- Click **Commit** or **Commit and Push**.

Step 7: Push Changes to GitHub
- After committing, go to **Git** → **Push**.
- WebStorm will upload your changes to the **Remote** GitHub **Repository**.

Step 8: Pull Updates from GitHub
- To sync with the latest changes, go to **Git** → **Pull**.
- This downloads updates from the **Remote** repository.

Step 9: Create and Use a Branch
- Go to **Git** → **Branches** → **New Branch**.
- Name your branch (e.g., `feature-login`) and switch to it.
- Make changes and commit them.
- Later, you can merge this branch into the main branch.

Step 10: Handle a Merge Conflict
- If two branches modify the same file, a merge conflict may occur.
- WebStorm will highlight the conflict.
- Use the built-in merge tool to resolve differences and complete the merge.

Step 11: Fetch Latest Changes
- Use **Git** → **Fetch** to check for updates on the **Remote** without applying them.
- This is useful to preview incoming changes before a pull.

---

**Glossary**

- **Branch**: A separate line of development in a project. Allows multiple features to be developed at the same time.
- **Clone**: A copy of a remote **Repository** downloaded to your local machine.
- **Commit**: A snapshot of your changes with a message describing what was done.
- **Fetch**: Retrieves updates from the **Remote** repository without merging them.
- **Git**: A distributed version control system used to track changes in source code.
- **GitHub**: A web-based platform for hosting and collaborating on **Git** repositories.
- **Merge**: Combines changes from one **Branch** into another.
- **Merge Conflict**: A situation where Git cannot automatically resolve differences between two **Branches**.
- **Push**: Sends your local **Commits** to the **Remote** repository.
- **Pull**: Downloads and integrates changes from the **Remote** repository.
- **Remote**: A version of your project hosted on a server (e.g., GitHub).
- **Repository**: A storage space for your project files and version history.

---

References

1. JetBrains WebStorm Documentation: [https://www.jetbrains.com/webstorm/documentation](https://www.jetbrains.com/webstorm/documentation)
2. Git Official Documentation: [https://git-scm.com/doc](https://git-scm.com/doc)
3. GitHub Docs: [https://docs.github.com](https://docs.github.com)
4. Atlassian Git Tutorials: [https://www.atlassian.com/git/tutorials](https://www.atlassian.com/git/tutorials)
