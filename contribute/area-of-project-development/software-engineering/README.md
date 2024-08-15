---
description: ENGINEERING CONTRIBUTION WORKFLOW
---

# Contribution Workflow for Engineers

***

## Community Contributing Guide

Visit the contributing guide page below to get directions about what is important in Collabo Community, and also learn how to make quality contributions to Collabo Community.

{% content-ref url="https://app.gitbook.com/o/-MWSSST6_GF5VEuG0Atd/s/XdbpF9uCzy0cC5JUJYyW/" %}
[Contributing Guide](https://app.gitbook.com/o/-MWSSST6\_GF5VEuG0Atd/s/XdbpF9uCzy0cC5JUJYyW/)
{% endcontent-ref %}

***

## Finding projects to contribute to with their local development instructions

{% hint style="info" %}
See _**Project local development instructions**_ from the _**sidebar**_ of this documentation page to find _**Engineering**_ project local development instructions documentation pages. You will be able to get the link to the GitHub repository for the project that interests you from the pages there. You will need the link to get the project onto your local computer, as shown in the next steps below.
{% endhint %}

***

## Git workflow: Fork and Clone repository

Once you find an Engineering project that interests you contribute to, head over to the the _**repository URL**_ i.e. (the Collabo Community's) GitHub repository for that project.

{% hint style="info" %}
Fork the repository. Then clone the forked repository unto your local computer.
{% endhint %}

**HTTPS url option:** If you are using `https` _**clone url**_, the clone command with your url will look like this:

{% code overflow="wrap" %}
```
git clone https://github.com/your-own-github-account-user-name-will-be-here-instead/the-repo-name.git
```
{% endcode %}

**SSH url option:** [See GitHub documentation for SSH configuration](https://docs.github.com/en/authentication/connecting-to-github-with-ssh) incase you wish to be able to work with SSH url for git operations (that is, if you have not set it up before). If you are using `SSH` _**clone url**_, the clone command with your url will look like this:

{% code overflow="wrap" %}
```
git clone git@github.com:your-own-github-account-user-name-will-be-here-instead/the-repo-name.git
```
{% endcode %}

{% hint style="info" %}
You can get the url to clone the project with, through the green code button in the repository on Github as shown below in the screenshot.
{% endhint %}

<figure><img src=".gitbook/assets/Screenshot 2023-11-13 at 01.39.27 (1).png" alt=""><figcaption><p>Position of the Green Code button and the popup to copy URL on GitHub</p></figcaption></figure>

***

## Installing dependencies and running the project locally

{% hint style="info" %}
Every project may have different instructions for how to install dependencies and how to run the project locally. See _**Project local development instructions**_ from the _**sidebar**_ of this documentation page to get specific instructions for that project.
{% endhint %}

***

## Git workflow: Create new branch to make your changes in

Except you are requested to create your branch from another branch, always create your new branch from the `develop` branch:

```
git checkout develop
```

Create your branch using the our branch naming convention:

<pre><code><strong>git checkout -b @GH-replaceThisPartWithYourGitHubIssueTicketNumber
</strong></code></pre>

For example, if your issue ticket number is `62` on GitHub, you would create the branch like so:

```
git checkout -b @GH-62
```

`@GH` simply means the issue ticket is on GitHub. Making use of the ticket's issue number in the branch name, makes it easy to identify and associate the fix you are submitting to the issue ticket.

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

Then **send a pull request** for your changes to be reviewed.

***

## Pull request guidelines

See page below for the **guidelines for submitting pull requests to any repository**.

{% content-ref url="https://app.gitbook.com/o/-MWSSST6_GF5VEuG0Atd/s/kz0h3jWUEnMa4Mjjkort/" %}
[Pull Request Guidelines](https://app.gitbook.com/o/-MWSSST6\_GF5VEuG0Atd/s/kz0h3jWUEnMa4Mjjkort/)
{% endcontent-ref %}

***
