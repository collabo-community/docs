---
description: SOFTWARE ENGINEERING CONTRIBUTING DOC FOR COLLABOCATE
---

# Collabocate

***

## Project description - page link

Find project description in the page attached below.

{% content-ref url="https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/collabocate" %}
[Collabocate](https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/collabocate)
{% endcontent-ref %}

***

## Local development instructions

* Head over to the GitHub repository: [https://github.com/collabo-community/collabocate](https://github.com/collabo-community/collabocate)
* Fork and clone the repository as shown in the [SWE contribution workflow](https://docs.collabocommunity.com/contribute/v/software-engineering/#git-workflow-fork-and-clone-repository).

Find the local development instructions for the different Collabocate projects in the tabs below, depending on the one you want to develop locally.

{% tabs %}
{% tab title="GitHubSync" %}
{% hint style="info" %}
Once you have the repository on your local computer, ensure you are _**in the root of the project's directory**_. Then install and run following the steps below.
{% endhint %}

***

_**Install project dependencies**_

Install dependencies:

```
npm install
```

***

_**First time setup instructions for GitHubSync \[General]**_

Make a copy of the `.env.example` file, then rename the copy to `.env` - it is this renamed copy that you will store your secrets in. Ensure that the .env file is in the _**root of the project's directory**_.

***

_**First time setup instructions for GitHubSync \[API server]**_

{% hint style="info" %}
Do not litter our repositories with your GitHubSync tests or experiments. Use the  REPO\_API\_URL for the community's test/experiment repo has shown below.
{% endhint %}

{% hint style="info" %}
Request for the GITHUB\_PERSONAL\_ACCESS\_TOKEN that works with our repos, from our community Discord server.
{% endhint %}

In the `.env` file, supply:

* The (GitHub)  REPO API url of the repository the community's test/experiment repo in the `.env` file as shown below (i.e. just copy and paste this in your .env file). Make sure to add it under/after the `GITHUB_API_BASE_URL` environment variable so that the variable in the repo url can take effect:

```
REPO_API_URL=${GITHUB_API_BASE_URL}/repos/collabo-community/use-me-for-experiments
```

* The GitHub personal access token for accessing the repo url:

```
GITHUB_PERSONAL_ACCESS_TOKEN=add-the-token-here
```

* The port number of your choice (for the API server to run on) e.g.

```
PORT=4800
```

***

_**First time setup instructions for GitHubSync \[test client]**_

In the `.env` file, supply:

* The backend url as shown below (i.e. just copy and paste this in your .env file). This is what will help connect the client to the API server. Make sure to add it under/after the `PORT` environment variable so that the variable in the backend url can take effect:

```
BACKEND_URL=http://localhost:${PORT}
```

* The port number of your choice (for the test client to run on) e.g.

```
CLIENT_APP_PORT=5500
```

***

_**Running the API server**_

Start the API server. In the root of the repository, run this in your terminal:

```
npm run dev:api
```

***

_**Running the test client**_

Start the client. In the root of the repository, run this in your terminal:

```
npm run dev:client
```
{% endtab %}
{% endtabs %}

***
