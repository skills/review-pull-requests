# Reviewing pull requests

_See how collaboration works on GitHub and start building great things, together._

![](https://repository-images.githubusercontent.com/149791379/3578a500-586d-11ea-9ac3-39087235fe44)

**Tags**: GitHub

---

This course will dive into how you can get your best work done by identifying when and how to request a review, how to perform a review for someone else's pull request, and other awesome collaboration methods.

All great projects start with collaboration. Pull requests are the foundation of teamwork on GitHub — and pull request reviews give you the ability to work together and discuss changes specific to a pull request by commenting, requesting changes, or approving.

## What you'll learn

We'll answer common questions like:
- What is a pull request?
- How do I request, review, or comment on a pull request?
- How do I accept changes introduced by a pull request review?
- What are the responsibilities of a reviewer?
- What's a CODEOWNERS file?
- What's a diff and how do I use it?
- How do I implement changes from a pull request review?
- How can I suggest a change when reviewing a pull request?

And when you're done you'll be able to:
- Create a pull request
- Comment on pull requests
- Leave reviews on pull requests
- Know what’s expected when reviewing pull requests
- Request pull request reviews
- Accept changes introduced by a pull request review


## What you'll build
We'll be building a tetris game!

<p align="left">
  <img src="https://user-images.githubusercontent.com/57373296/75575281-e332b200-5a2d-11ea-94da-8ce317ab1206.gif" width="350" height="350">
</p>

## Prerequisites
None. This course is a great introduction to using pull requests.

## Projects used
- This course uses a javascript [tetris game](https://github.com/jakesgordon/javascript-tetris)

## Audience

Developers, new GitHub users, users new to Git, students, managers, teams


---

## Welcome!

Hello and welcome! In this course you will learn how you can get your best work done in pull requests.  You'll learn when and how to request a review, how to review someone else's code, and how to respond to reviews. To do this, we'll be playing around with the code in this repository that makes a simple Tetris game.

If you'd like, you can use [GitHub Pages](https://pages.github.com/) to host your Tetris game. Just go to the **Settings** tab of this repository. Scroll down to **GitHub Pages** and select `main` as a **Source**. 

### New to GitHub?

For this course, you'll need some background knowledge. If you need a refresher on the GitHub flow, check out [the Introduction to GitHub course]({{ host }}/{{ course.Owner.login }}/introduction-to-github).

## Pull Requests Reviews 101

Reviewing a pull request is an opportunity to examine another contributor's changes. While reviewing a pull request, you can extrapolate how someone else solved a problem. It's an awesome opportunity to learn more about how the code works and how others solve problems. Reviewing a pull request is a great learning opportunity!

## Step 1: Add assignees for issues and pull requests

Assignees on issues and pull requests let other team members know who is responsible. The assignee oversees the issue or pull request in an accessible and visible way.

### :keyboard: Activity: Assign yourself to this issue

1. On the right side of the screen, click the `assign yourself` text under the **Assignees** section

<hr>
<h3 align="center">I'll respond below for your next step</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response, wait a few seconds and refresh the page for your next steps._


# Commenting on Pull Requests

As a collaborator on a repository, you will get and give pull request reviews before merging code. This is important! It ensures quality code and maintains momentum of changes to your project.

As you can see, I've opened this pull request and requested you as a reviewer. Pull requests are places to _share_ the changes made to the repository.

### Responsibilities of a reviewer

As a pull request reviewer, your role is to help the pull request author (thats me!) by making sure:

- Code destined for production is of the highest quality
- Intentional shortcuts (technical debt) are commented on and confirmed
- The greater team is aware of potential risks associated with changes

These broad responsibilities can include more specific goals, like:

- Pointing out potential issues in code quality, security, or business logic
- Suggesting other reviewers to the author, when warranted
- Commenting on, approving, or requesting changes on the PR
- Providing suggestions for alternate or better implementation details

Some repositories use a [CODEOWNERS](https://help.github.com/articles/about-codeowners/) file. The `CODEOWNERS` file assigns responsibility for certain parts of the code to specific individuals or teams. When the `CODEOWNERS` feature is enabled, only the code owner has the final authority to approve the pull request. Your review may not be a formal approval, but it does show confidence.

## Step 2: Communicate in pull requests

When an approval or request for changes is not yet needed, consider using **comments**. Comments enable you to inquire about the proposed change early in the review process. You don't need to wait until something is complete to make suggestions.

### :keyboard: Activity: Comment on my pull request

1. On the pull request, click **Files changed**
1. Hover over the line of code where you'd like to add a comment, and click the blue comment icon
1. In the comment window, type a question or leave a more general comment
1. When you're done, click **Add single comment**

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response, wait a few seconds and refresh the page for your next steps._


Nice work, @{{ user.username }}! Assigning yourself to an issue is a great way to let people know what you are working on. Once you begin working, it's important to get feedback on your work through reviews.

<hr>
<h3 align="center">Learn more in the <a href="{{ url }}">next pull request</a> </h3>


Uh oh @{{ user.username }}, something went wrong! I wasn't expecting this change. Please go over the instructions again and make sure you've followed them as exactly as you can.

If you would like help troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.


## Reviewing Pull Requests

Nice work @{{ user.username }}. By providing feedback, you've enabled me to reevaluate how I am making my desired change. But, pull request reviews don't stop at commenting. You can also `approve` or `request changes` on my pull request.

When you get asked to review something, you should acknowledge the request. Acknowledging a review request could take several forms. It could be leaving a comment on the pull request or leaving a review. In some cases, it could be rejecting the review request altogether.

<details><summary>Before you review, some things to consider</summary>

#### Discern the context

Review the title and body of the pull request to understand the intended change. This should help you identify limitations, boundaries, and other important context.

#### Observing the progress

As a reviewer, there are certain things to look for when identifying how to best provide feedback. In early stages, reviews should focus on the general direction of the changes. Identify if the goal is possible, rather than nitpicking the style, polish, or wording. Pull requests that are closer to merging should receive a robust review. Thorough testing is one of many ways to ensure the changes won't break the project.

Regardless of timing, focus your feedback on the most essential changes. Suggest changes for minor issues within the pull request. When suggesting major changes, open a separate pull request against the author's branch.

</details>

## Step 3: Leave a review

I've made some changes to this branch and would love :heart: it if you could `approve` this pull request. For now, just approving the pull request will suffice. In a moment we will look at requesting changes. :+1:

### :keyboard: Activity: Approve a pull request

1. In the pull request, click the **Files changed** tab
1. Review the changes in the pull request by commenting on specific lines
1. Above the changed code, click **Review changes**
1. Type a comment summarizing your feedback on the proposed changes
1. Select **Approve** to approve merging the changes proposed in the pull request
1. Click **Submit review**

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response, wait a few seconds and refresh the page for your next steps._


# Using `request changes` on a pull request

Thanks again for all your help on that last pull request. With our powers combined, _anything_ is possible! This next change might introduce some new changes that aren't going to look great.

Sometimes, the author might identify that something isn't working. They might need a helping hand :wave: to solve the problem. In other instances, it might only work in their environment. When reviewing a pull request, look at and test the code to pinpoint any bugs or unexpected behavior.

### Writing a review

#### Review the `diff`

Reviewing the `diff`, the comparison of the proposed code, in the context of the whole project. Could it introduce performance problems, or security vulnerabilities? Try to predict unintended consequences that this change could cause.

#### Try it out

For most things, actually trying out the proposed change is a good idea. This makes it a lot easier to tell if the actual change matches the intention. You can do this by:

- Cloning the repository, and checking out to the branch compared in the pull request. Run the application in your local development environment.
- Deploying the pull request to a review-lab or staging environment (as appropriate).

When summarizing your review, let the author know if you completed any of these tests.

#### Empathy and Constructive Feedback

The goal of providing feedback on a pull request is to ensure that the best possible change is being added. Sometimes, a change isn't addressing the problem in the best possible way. It's the reviewer's responsibility to provide meaningful and constructive feedback.

### Requesting Changes 101

Before you submit your review, your line comments are pending and only visible to you. You can edit pending comments anytime before you submit your review. To cancel a pending review and its pending comments, scroll down to the end of the page in the Conversation tab. Then click **Cancel review**.

## Step 4: Leave a review that asks for changes

If you could check out this code for me and tell me what is wrong, that would be fantastic.

### :keyboard: Activity: Requesting changes

1. On the pull request, click **Files changed**
1. Hover over the line of code where you'd like to add a comment, and click the blue comment icon
1. In the comment window, type your comment
1. Click **Start a review**
    - If you have already started a review, you can click **Add review comment**
1. Above the changed code, click **Review changes**
1. Type a comment summarizing your feedback on the proposed changes
    - _Note: The problem here is that too many Tetris pieces are the same color. In your review, you might want to suggest that I choose colors which would be easier to see when playing the game._
1. Select **Request changes** to submit feedback introducing changes necessary before merging
1. Click **Submit review**

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response, wait a few seconds and refresh the page for your next steps._


## Great work!

Thanks for approving my pull request. Now, I can merge it into our project.


<hr>
<h3 align="center">Let's continue working in <a href="{{ url }}">the next pull request</a>
</h3>


It looks like you've given me an approval, but the code isn't ready yet.

Luckily, you can change your mind about reviews. Go ahead and leave a review again, but make sure to select "request changes" this time.

If you would like help troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.


It looks like you've commented, but the code isn't ready yet.

Luckily, you can change your mind about reviews. Go ahead and leave a review again, but make sure to select "request changes" this time.

If you would like help troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.


## Requesting changes

Thanks for making that suggestion on my change. In my excitement to ship more stuff, I must have gotten distracted while picking colors. :grimacing: I'm making a change to this branch to fix my mistake.

Not all the pull request reviews you perform in the future will decide the color of the blocks in our Tetris game. :smile:

Although you may want to leave short comments like: 👍, 👎🏽, awesome!, or no; these don't give the author much detail. Provide comments **like the following** to enable the author of the pull request to respond:

- This looks like it’ll be helpful to our users, but I’m not sure about the flow. I also have some concerns about the efficiency of these queries.
- Although this feature might be useful, do we have any data that identifies that our users need it?

## Step 5: Practice reviews

While you were reading this, I made your suggested changes. If you could approve my pull request, that would be awesome!

### :keyboard: Activity: Give another pull request review

1. In the pull request, scroll down to the bottom and look for your own review status
1. Next to your review, click **Approve changes**

<hr>
<h3 align="center">Return to this pull request for my next comment</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response, wait a few seconds and refresh the page for your next steps._


## Step 8: Don't just review, suggest!

Now that you have explored the different ways you can review a pull request it is time to learn how to use the _suggest changes_ functionality. This feature, enables you to recommend a change to a pull request that the author can commit with the push of a button!

### :keyboard: Activity: Create a pull request

1. Create a pull request using the `base: main` and `compare: update-readme` branches

<hr>
<h3 align="center">Click here to start the <a href="{{ url }}">pull request</a></h3>


Good pull requests help contributors understand the context. They have a body description detailing the suggested change.

Let's edit this pull request to add a body description.

### :keyboard: Activity: Fixing your pull request

1. The first comment on your pull request will have the default text of **No description provided**. Click ![octicon-kebab-horizontal] in the top right corner of the comment box to make an edit.
1. Add a description of the changes you've made in the comment box. Feel free to add a description of what you’ve accomplished so far. As a reminder, you have:
    - Left reviews and line comments
    - Created a file and made a commit
    - Opened a pull request
1. Click the green **Update comment** button at the bottom right of the comment box when done.

If you would like help troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.

<hr>
<h3 align="center">Watch below for my response</h3>

[octicon-kebab-horizontal]: https://unpkg.com/octicons/build/svg/kebab-horizontal.svg


Thanks for opening this pull request, @{{ user.username}}. 

```suggestion
You can play the game at: {{ pagesUrl }}
```

I've made a suggested change to this pull request because I think you should link your version of the game in your README file. I made this suggestion by creating a review comment that uses some :sparkle: special :sparkle: formatting.

It looks like this:

    ```suggestion
    You can play the game at: {{ pagesUrl }}
    ```

### :keyboard: Activity: Apply the suggestion

1. Click **Commit suggestion**
2. Enter a commit message
3. Click **Commit changes**

For more information about suggested changes, check out this [GitHub Help](https://help.github.com/articles/incorporating-feedback-in-your-pull-request) article.


## Step 7: Merge this pull request

Thanks for accepting my suggested change. Now that the pull request is finished, you should merge the change in and start playing your game!

### :keyboard: Activity: Merge pull request

1. Click **Merge pull request**
1. Click **Confirm merge**
1. Delete the branch


Oh no! @{{ user.username }}, it looks like you have accidentally closed this pull request. To complete this activity, please reopen and use the instructions provided to close this pull request in its correct sequence of steps.

If you would like help troubleshooting, create a post on the [GitHub Community]({{ communityBoard }}) board. You might also want to search for your issue to see if other people have resolved it in the past.


# Congratulations! :tada:

![hulatocat](https://octodex.github.com/images/hula_loop_octodex03.gif)

Nice work helping me with all these pull requests! As you continue working on GitHub, remember that high quality reviews improve your projects. If you are new to a repository, inquire about what review practices they have so you can hit the ground running.



