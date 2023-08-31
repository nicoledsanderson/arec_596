# AREC 596: Getting Started with Github Desktop
This repo is a tutorial for teaching students in AREC 596 how to use Github Desktop. It borrows instructions from the [Github Docs page on how to use Github Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/creating-your-first-repository-using-github-desktop).

## Part 1: Installing GitHub Desktop and authenticating your account
You all should have done this before class. But if not, you can install GitHub Desktop on any supported operating system. After you install the app, you will need to sign in and authenticate your account on GitHub or GitHub Enterprise before you can create and clone a tutorial repository.

For more information on installing and authenticating, see "[Setting up GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/setting-up-github-desktop)."

## Part 2: Exploring Github Desktop
In the file menu at the top of the screen, you can access settings and actions that you can perform in GitHub Desktop. Most actions also have keyboard shortcuts to help you work more efficiently. For a full list of keyboard shortcuts, see "[GitHub Desktop keyboard shortcuts](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/github-desktop-keyboard-shortcuts)."

### The GitHub Desktop repository bar
At the top of the GitHub Desktop app, you will see a bar that shows the current state of your repository.

Screenshot of the GitHub Desktop app. A bar displaying details for the "hello-world" repository spans the top of the window, and is outlined in orange.

- Current repository shows the name of the repository you're working on. You can click Current repository to switch to a different repository in GitHub Desktop.
- Current branch shows the name of the branch you're working on. You can click Current branch to view all the branches in your repository, switch to a different branch, or create a new branch. Once you create pull requests in your repository, you can also view these by clicking on Current branch.
- Publish repository appears because you haven't published your repository to GitHub yet, which you'll do later in the next step. This section of the bar will change based on the status of your current branch and repository. Different context dependent actions will be available that let you exchange data between your local and remote repositories.

### Changes and History
In the left sidebar, you'll find the Changes and History views.

Screenshot of the GitHub Desktop app. A sidebar on the left-hand side, with tabs labeled "Changes" and "History", is highlighted with an orange outline.

- The **Changes** view shows changes you've made to files in your current branch but haven't committed to your local repository. At the bottom, there is a box with "Summary" and "Description" text boxes and a **Commit to BRANCH** button. This is where you'll commit new changes. The **Commit to BRANCH**button is dynamic and will display which branch you're committing your changes to.
- The **History** view shows the previous commits on the current branch of your repository. You should see an "Initial commit" that was created by GitHub Desktop when you created your repository. To the right of the commit, depending on the options you selected while creating your repository, you may see *.gitattributes*, *.gitignore*, LICENSE, or README files. You can click each file to see a diff for that file, which is the changes made to the file in that commit. The diff only shows the parts of the file that have changed, not the entire contents of the file

## Part 3: Publishing your repository to GitHub
When you create a new repository, it only exists on your computer and you are the only one who can access the repository. You can publish your repository to GitHub to keep it synchronized across multiple computers and allow other people to access it. To publish your repository, push your local changes to GitHub.

1. In the repository bar, click Publish repository.
Screenshot of the repository bar. A button, labeled "Publish repository", is highlighted with an orange outline.
1. In the "Publish Repository" window, enter details for your new repository.
  - GitHub Desktop automatically fills the "Name" and "Description" fields with the information you entered when you created the repository.
  - Keep this code private lets you control who can view your project. If you leave this option unselected, other users on GitHub will be able to view your code. If you select this option, your code will not be publicly available.
  - The Organization drop-down menu, if present, lets you publish your repository to a specific organization that you belong to on GitHub.

  a. Click Publish Repository.
  b. You can access the repository on GitHub.com from within GitHub Desktop. In the file menu, click Repository, then click View on GitHub. This will take you directly to the repository in your default browser.

## Part 2: Making, committing, and pushing changes
