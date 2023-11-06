<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Introduction to GitHub

_Get started using GitHub in less than an hour._

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 2: Commit a file

_You created a branch! :tada:_

Creating a branch allows you to edit your project without changing the `main` branch. Now that you have a branch, it’s time to create a file and make your first commit!

**What is a commit?**: A _[commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ is a set of changes to the files and folders in your project. A commit exists in a branch. For more information, see "[About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)".

### :keyboard: Activity: Your first commit

The following steps will guide you through the process of committing a change on GitHub. A commit records changes in renaming, changing content within, creating a new file, and any other changes made to your project. For this exercise, committing a change requires first adding a new file to your new branch.

1. On the **< > Code** tab in the header menu of your repository, make sure you're on your new branch `my-first-branch`.

2. Select the **Add file** drop-down and click **Create new file**.

   ![create new file option](/images/create-new-file.png)

3. In the **Name your file...** field, enter `PROFILE.md`.

   **Note:** `.md` is a file extension that creates a Markdown file. You can learn more about Markdown by visiting "[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)" in our docs or by taking the "[Communicating using Markdown](https://github.com/skills/communicate-using-markdown)" Skills course.

4. In the **Enter file contents here** area, copy the following content to your file:

   ```
   Welcome to my GitHub profile!
   ```

   <img alt="profile.md file screenshot" src="/images/my-profile-file.png"/>

5. Click **Commit changes...** in the upper right corner above the contents box. For commits, you can enter a short commit message that describes what changes you made. This message helps others know what's included in your commit. GitHub offers a simple default message, but let's change it slightly for practice. First, enter `Add PROFILE.md` in the first text-entry field titled "Commit message".

   <img alt="screenshot of adding a new file with a commit message" src="/images/commit-full-screen.png" />

6. In this lesson, we'll ignore the other fields and click **Commit changes**.
7. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

  <<< Author notes: Step 3 >>>
  Just a historic note: the previous version of this step forced the learner
  to write a pull request description,
  checked that `main` was the receiving branch,
  and that the file was named correctly.

## Step 3: Open a pull request

_Nice work making that commit! :sparkles:_

Now that you have made a change to the project and created a commit, it’s time to share your proposed change through a pull request!

**What is a pull request?**: Collaboration happens on a _[pull request](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request)_. The pull request shows the changes in your branch to other people and allows people to accept, reject, or suggest additional changes to your branch. In a side by side comparison, this pull request is going to keep the changes you just made on your branch and propose applying them to the `main` project branch. For more information about pull requests, see "[About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)".

### :keyboard: Activity: Create a pull request

You may have noticed after your commit that a message displayed indicating your recent push to your branch and providing a button that says **Compare & pull request**.

![screenshot of message and button](/images/compare-and-pull-request.png)

To create a pull request automatically, click **Compare & pull request**, and then skip to step 6 below. If you don't click the button, the instructions below walk you through manually setting up the pull request.

1. Click on the **Pull requests** tab in the header menu of your repository.
2. Click **New pull request**.
3. In the **base:** dropdown, make sure **main** is selected.
4. Select the **compare:** dropdown, and click `my-first-branch`.

   <img alt="screenshot showing both branch selections" src="/images/pull-request-branches.png" />

5. Click **Create pull request**.
6. Enter a title for your pull request. By default, the title will automatically be the name of your branch. For this exercise, let's edit the field to say `Add my first file`.
7. The next field helps you provide a description of the changes you made. Here, you can add a description of what you’ve accomplished so far. As a reminder, you have: created a new branch, created a file, and made a commit.

   <img alt="screenshot showing pull request" src="/images/Pull-request-description.png" />

8. Click **Create pull request**. You will automatically be navigated to your new pull request.
9. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

   **Note**: You may see evidence of GitHub Actions running on the tab with the pull request opened! The image below shows a line you might see on your pull request after the Action finishes running.

   <img alt="screenshot of an example of an actions line" src="/images/Actions-to-step-4.png"/>
<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->



Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
