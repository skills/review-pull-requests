<!--
  <<< Author notes: Header of the course >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses Creative Commons Attribution 4.0 International.
-->

# Review pull requests

_Collaborate and work together on GitHub._

<!--
  <<< Author notes: Start of the course >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
  Each step should be wrapped in <details>/<summary>, with an `id` set.
  The start <details> should have `open` as well.
  Do not use quotes on the <details> tag attributes.
-->

<details id=0 open>
<summary><h2>Welcome</h2></summary>

All great projects start with collaboration. Pull requests are the foundation of teamwork on GitHub — and pull request reviews give you the ability to work together and discuss changes specific to a pull request by commenting, requesting changes, or approving.

- **Who is this for**: Developers, new GitHub users, users new to Git, students, managers, teams.
- **What you'll learn**: When and how to request a review; how to provide a review of someone else's pull request.
- **What you'll build**: We'll be reviewing a pull request for a simple game.
- **Prerequisites**: We assume you are familiar with creating branches, commits, and pull requests—you can learn this in our [Introduction to GitHub](https://github.com/skills/introduction-to-github) course.
- **How long**: This course is five steps long and takes less than 30 minutes to complete.

## How to start this course

1. Right-click **Start course** and open the link in a new tab.
   <br />[![start-course](https://user-images.githubusercontent.com/1221423/218596841-0645fe1a-4aaf-4f51-9ab3-8aa2d3fdd487.svg)](https://github.com/skills/review-pull-requests/generate)
2. In the new tab, follow the prompts to create a new repository.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository—private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   ![Create a new repository](https://user-images.githubusercontent.com/1221423/218594143-e60462b6-9f2a-4fa3-80de-063ac5429aab.png)
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

</details>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

<details id=1>
<summary><h2>Step 1: Open a pull request</h2></summary>

_Welcome to "Review pull requests"! :wave:_

Let's get started by opening a pull request.

**What is a pull request?**: Collaboration happens on a pull request. The pull request shows the changes in your branch to other people. This pull request is going to keep the changes you just made on your branch and propose applying them to the `main` branch.

### :keyboard: Activity: Create a pull request

1. Click on the **Pull requests** tab in your repository.
2. Click **New pull request**.
3. In the **base:** dropdown, make sure **main** is selected.
4. Select the **compare:** dropdown, and click `update-branch`.
5. Click **Create pull request**.
6. Enter a title for your pull request: `Update the game over message`.
7. Enter a description for your pull request: `Update the game over message so people know how to play again!`
8. Click **Create pull request**.

Next, wait about 20 seconds for actions to run, then refresh this course's README (the one you're following instructions from) and a [GitHub Action](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: this step combines the commend, approve, and needs changes steps from the previous version.
-->

<details id=2>
<summary><h2>Step 2: Assign yourself</h2></summary>

_Great job opening that pull request! :wave:_

**What is a _pull request review_?**: Reviewing a pull request is an opportunity to examine another contributor's changes and give them feedback. It's an awesome opportunity to learn more about how the project works and how others solve problems.

The best way to get a review is to ask for one. On GitHub, you can ask someone to review a pull request by assigning them as a reviewer or assignee. If you are not ready for review, consider [creating a draft pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) instead.

### :keyboard: Activity: Assign yourself

1. Open the pull request you just created.
1. Under **Assignees** on the right side of the screen, add yourself.

Because you created the pull request, you can't assign yourself as a reviewer, but feel free to assign a friend as a reviewer instead to see how it works :smile:

Next, wait about 20 seconds for actions to run, then refresh this course's README (the one you're following instructions from) and a [GitHub Action](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: this step combines the commend, approve, and needs changes steps from the previous version.
-->

<details id=3>
<summary><h2>Step 3: Leave a review</h2></summary>

_You assigned yourself! :tada:_

Pull request reviews ensure quality and maintain momentum of changes to your project.

#### When reviewing a pull request:

1. Review the _title_ and _body_ of the pull request, and possibly any associated issue, to understand the intended change. 
1. Review the [diff](https://docs.github.com/en/get-started/quickstart/github-glossary#diff), the comparison of the proposed code, in the context of the whole project.
1. For most things, try out the proposed change. Check if the actual change matches the intention. Find the repository's [contributing guide](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors) to find out how to review the changes.

#### In your review comments:

- Identify potential issues, risks, and limitations.
- Suggest changes and improvements.
- Share awareness of upcoming changes that the pull request doesn't account for.
- Ask questions to verify shared understanding.
- Highlight what the author did well and should keep doing.
- Prioritize the most important feedback.
- Be concise _and_ provide meaningful detail.
- Treat the pull request author with kindness and empathy.

When an approval or request for changes is not yet needed, consider using **comments**. An **approval** lets the author know you believe the pull request is safe to merge. **Requesting changes** lets the author know you believe the pull request is not ready to merge.

### :keyboard: Activity: Leave a review

1. On the pull request, click **Files changed**.
1. Click **Review changes**.
1. Add a comment with your initial thoughts on the pull request.
1. Select _comment_. You won't be able to _approve_ or _request changes_ to your own pull request.
1. Click **Submit review**.

Next, wait about 20 seconds for actions to run, then refresh this course's README (the one you're following instructions from) and a [GitHub Action](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=4>
<summary><h2>Step 4: Suggest changes</h2></summary>

_Nice work reviewing that pull request :sparkles:_

Now that you have explored the different ways you can review a pull request it is time to learn how to use _suggest changes_.

**What is _suggest changes_?**: This feature enables you to recommend a change to a pull request that the author can commit with the push of a button.

### :keyboard: Activity: Suggest changes

1. On the pull request, click **Files changed**.
1. Find the `index.html` changes.
1. Hover your cursor next to the line numbers on the left side of the page.
1. Click the blue plus icon.
1. After the comment form appears, click the **Add a suggestion** button. <br>
![add-a-suggestion-button](https://user-images.githubusercontent.com/97056108/184449714-61e8ee51-824a-48c1-9436-2dfd67f2c070.png)
1. Edit the suggestion.
1. Click **Add a single comment**.

Next, wait about 20 seconds for actions to run, then refresh this course's README (the one you're following instructions from) and a [GitHub Action](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!--
  <<< Author notes: Step 5 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=5>
<summary><h2>Step 5: Apply suggested changes</h2></summary>

_Nicely done suggesting changes! :partying_face:_

Now let's see how easy it is to [apply your suggestion](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests/incorporating-feedback-in-your-pull-request).

### :keyboard: Activity: Apply suggested changes

1. Click **Commit suggestion**.
1. Type a commit message.
1. Click **Commit changes**.

Next, wait about 20 seconds for actions to run, then refresh this course's README (the one you're following instructions from) and a [GitHub Action](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!--
  <<< Author notes: Step 6 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

<details id=6>
<summary><h2>Step 6: Merge your pull request</h2></summary>

_Almost there! :heart:_

You can now [merge](https://docs.github.com/en/get-started/quickstart/github-glossary#merge) your pull request!

### :keyboard: Activity: Merge your pull request

1. Click **Merge pull request**.
1. Delete the branch `update-game` (optional).

Next, wait about 20 seconds for actions to run, then refresh this course's README (the one you're following instructions from) and a [GitHub Action](https://docs.github.com/en/actions) will automatically close this step and open the next one.

</details>

<!--
  <<< Author notes: Finish >>>
  Review what we learned, ask for feedback, provide next steps.
-->

<details id=X>
<summary><h2>Finish</h2></summary>

_Congratulations friend, you've completed this course!_

<img src=https://octodex.github.com/images/hula_loop_octodex03.gif alt=celebrate width=300 align=right>

As you continue working on GitHub, remember that high quality reviews improve your projects. If you are new to a repository, inquire about what review practices they have so you can hit the ground running.

Here's a recap of all the tasks you've accomplished in your repository:

- You learned how to assign pull requests for review.
- You left a review on a pull request.
- You suggested changes to a pull request.
- You applied suggested changes to a pull request.

### What's next?

- Try adding a [`CODEOWNERS`](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) file to your project to automatically assign reviewers to pull requests.
- We'd love to hear what you thought of this course [in our discussion board](https://github.com/skills/.github/discussions).
- [Take another GitHub Skills course](https://github.com/skills).
- [Read the GitHub Getting Started docs](https://docs.github.com/en/get-started).
- To find projects to contribute to, check out [GitHub Explore](https://github.com/explore).

</details>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/skills/.github/discussions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2022 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [CC-BY-4.0 License](https://creativecommons.org/licenses/by/4.0/legalcode)
