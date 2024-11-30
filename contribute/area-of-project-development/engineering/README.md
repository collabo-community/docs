---
description: COLLABO COMMUNITY'S ENGINEERING CONTRIBUTION WORKFLOW
---

# Contribution Workflow for Engineers

***

## Git workflow: Fork and Clone repository

**Step 1:** Head over to the the _**repository URL**_ i.e. (the Collabo Community's) GitHub repository for that project.

{% hint style="warning" %}
Get the _**repository URL**_ link to the GitHub repository for a project from _**Project local development instructions**_, through the sidebar.&#x20;
{% endhint %}

**Step 2:** Fork the repository. Then clone the forked repository unto your local computer. Clone URL options explained below:

* **HTTPS url option:** If you are using `https` _**clone url**_, the clone command with your url will look like this:

```
git clone https://github.com/your-github-user-name-here-instead/the-repo-name.git
```

* **SSH url option:** [See GitHub documentation for SSH configuration](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) incase you wish to be able to work with SSH url for git operations (that is, if you have not set it up before). If you are using `SSH` _**clone url**_, the clone command with your url will look like this: git@github.com:

```
git clone git@github.com:your-github-user-name-here-instead/the-repo-name.git
```

{% hint style="warning" %}
You can get the url to clone the project with, through the green code button in the repository on Github as shown below in the screenshot.
{% endhint %}

<figure><img src=".gitbook/assets/Screenshot 2023-11-13 at 01.39.27 (1).png" alt=""><figcaption><p>Position of the Green Code button and the popup to copy URL on GitHub</p></figcaption></figure>

***

## Installing dependencies and running the project locally

{% hint style="warning" %}
Every project may have different instructions for how to install dependencies and how to run the project locally. See _**Project local development instructions**_ from the _**sidebar**_ of this documentation page to get specific instructions for that project.
{% endhint %}

***

## Git workflow: Create new branch to make your changes in

Except you are requested to create your branch from another branch, always create your new branch from the `develop` branch:

```
git checkout develop
```

Create your branch using the our branch naming convention:

```
git checkout -b @GH-replaceThisPartWithYourGitHubIssueTicketNumber
```

For example, if your issue ticket number is `62` on GitHub, you would create the branch like so:

```
git checkout -b @GH-62
```

{% hint style="warning" %}
`@GH` simply means the issue ticket is on GitHub. Making use of the ticket's issue number in the branch name, makes it easy to identify and associate the fix you are submitting to the issue ticket.
{% endhint %}

***

## Git workflow: Add, commit and push changes to remote

**Make the desired changes** you wish to submit to the project, add, commit and push your changes:

```
git add .
```

```
git commit -m "replace this part with a commit message that describes your changes"
```

```
git push origin replace-this-part-with-the-name-of-your-branch
```

Then **send a pull request**. See page below for the **guidelines for submitting pull requests to any repository**:

{% content-ref url="https://app.gitbook.com/o/-MWSSST6_GF5VEuG0Atd/s/kz0h3jWUEnMa4Mjjkort/" %}
[Pull Request Guidelines](https://app.gitbook.com/o/-MWSSST6_GF5VEuG0Atd/s/kz0h3jWUEnMa4Mjjkort/)
{% endcontent-ref %}

***
