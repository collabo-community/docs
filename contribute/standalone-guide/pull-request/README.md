# Pull Requests: Submitting pull requests to any repository in Collabo Community

***

{% hint style="info" %}
Try to submit a pull request for an issue within 2 days of showing interest, even if you are not through fixing the issue, so that the associated issue ticket doesn't get reassigned to another contributor. Seeing some form of activity about it frequently (either on the issue ticket/pull request  or in our community channels) will help the community know you are actively working on it.
{% endhint %}

***

## PR 101: How to submit pull requests that make the work of reviewers and repository maintainers less complicated

* <mark style="background-color:yellow;">Do not submit a pull request for an issue ticket you are not assigned to. It will be counted as spam.</mark>\
  _**Reason:** We want to be clear about who is working on what, and we want to avoid more than one person working on the same issue ticket without knowing it._
* <mark style="background-color:yellow;">The name of your branch should use the branch naming convention in our</mark> [<mark style="background-color:yellow;">**contribution workflow documentation**</mark>](https://docs.collabo.community/contribute)<mark style="background-color:yellow;">.</mark>\
  _**Reason:** It is a way of confirming to maintainers/reviewers, that the issue ticket you are submitting a fix for exists on GitHub. Making use of the ticket's issue number in the branch name, makes it easy to identify and associate the fix you are submitting to the GitHub issue ticket._
* <mark style="background-color:yellow;">Link your pull request to the issue it aims to fix. Do this in description of the pull request you are submitting.</mark> \
  _**Reason:** The link helps reviewers to easily locate the associated issue ticket._ [_**Watch tutorial**_ ](https://www.youtube.com/watch?v=IqJWDTZdQG4\&list=PLMDhbo3xlD1ESa1\_9WN4yG7bGDDksEQx7\&index=4\&t=301s)_to help understand how to link pull request to issue ticket._
* <mark style="background-color:yellow;">Your pull request title must reflect the Issue title you are working on, and it should start with "Fix: ". For example, If the issue title is "Add contribution rules section", the pull request title should be "Fix: Add contribution rules section".</mark> \
  _**Reason:** This helps the internal team easily locate and quickly identify the associated pull requests to your issue tickets, when issuing release notes for the product or for any other reference purpose._ [_**Watch tutorial.**_](https://www.youtube.com/watch?v=Ej396Vra1oQ\&list=PLMDhbo3xlD1ESa1\_9WN4yG7bGDDksEQx7\&index=14)
* <mark style="background-color:yellow;">Only make changes that the issue asks to change. Do not change even as small as space or comma anywhere else that does not concern the issue ticket you are taking on.</mark>\
  _**Reason:** Reviewers will not have to deal with anything apart from what is in the issue ticket associated with the pull request. Reviewers can therefore focus, be thorough and do it with little or no fatigue. It is possible that more than one contributors are working on the same specific file(s) you are working on. Help make it easier for maintainers to merge these possibly conflicting changes from different contributors successfully, without "merging away" things we need by mistake. Also, If we discover that some pull request fix is later problematic after we have merged it in, we may need to revert (i.e. remove) the affected pull request fix. If changes for some other different issue are done in the same fix, this means we'll be removing all of them instead of just that one cause - which is what we don't want. Making reference to pull requests that contain more than the changes asked in the future is also problematic._
* <mark style="background-color:yellow;">Do not request review from an individual person when you want to request for review on your pull request (once you are done and you feel that your pull request is ready for review). Instead, request review from a review team.</mark>\
  _**Reason:** The review teams are created so that more than one persons can receive notifications to review your pull request. If one person is not around to review, some other reviewer can take it up. At the same time, you don't have to worry about who to tag or request review from, even if the maintainers of the project change._\
  _<mark style="background-color:yellow;">**Extra note:**</mark> <mark style="background-color:yellow;"></mark><mark style="background-color:yellow;">This does not mean that persons who are not on the review teams cannot review a pull request.</mark>_

***

## What are the review teams, and which review team to request review from for the project you are contributing to?

Review teams are the way we assign the responsibility to people within our community to review pull requests that come in from contributors, based on their area of interest(s) or expertise. The people in these review teams are also contributors themselves.

The list of review teams can be found at: [https://github.com/orgs/collabo-community/teams](https://github.com/orgs/collabo-community/teams)

Brief description of the review teams:

* `collabo-community/review-docs` reviews pull requests for our documentation repo on GitHub
* `collabo-community/review-web-app` reviews pull requests for our web client repos on GitHub
* `collabo-community/review-mobile-app` reviews pull requests for our mobile client repos on GitHub
* `collabo-community/review-backend-api` reviews pull requests for our backend repos on GitHub
* `collabo-community/review-cli` reviews pull requests for our CLI repos on GitHub

{% hint style="info" %}
Even if more review teams are added or they change in the future, we follow a stable and predictable pattern for naming the review teams.

Review teams can be easily identified, as _**review-**_ is present in the team name.
{% endhint %}

***

## How to request review from a review team on your pull request

After submitting your pull request, and anytime you feel your pull request is ready for reviewers to take a look, go to the reviewers dropdown there in your pull request. Then select a review team from the drop down list. You will only find one review team on the list, so just select that one.

For example, in the screenshot below, the contributor is selecting the `collabo-community/review-docs` review team because they are submitting the pull request to the documentation repository.

{% hint style="info" %}
How to know which review team to tag or select on your pull request? - Check the readme of the repository you are submitting pull request to.
{% endhint %}

{% hint style="warning" %}
If you are not able to access the dropdown to request review, there are 2 options:

* Add a comment on the pull request tagging the correct review team.
* Reach out on our community Discord server to get access to it: Only contributors who actively contribute to the community are eligible for this upgrade.
{% endhint %}

<figure><img src=".gitbook/assets/Screenshot 2024-04-06 at 18.34.48.png" alt=""><figcaption><p>Selecting a review team from the reviewer dropdown on your pull request</p></figcaption></figure>

***

{% hint style="info" %}
Feel free to ask questions in the community channels, if you are not clear about anything written on this page.
{% endhint %}

***

{% hint style="info" %}
This YouTube playlist from our old Git and Github course content may also help you when contributing to any of our projects. [_**Go to the old Git and Github course playlist.**_](https://www.youtube.com/playlist?list=PLMDhbo3xlD1ESa1\_9WN4yG7bGDDksEQx7)
{% endhint %}
