---
description: SOFTWARE ENGINEERING CONTRIBUTING DOC FOR CREATE COLLABO APP
---

# Create Collabo App

***

## Project description - page link

Find project description in the page attached below.

{% content-ref url="https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/create-collabo-app" %}
[Create Collabo App](https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/create-collabo-app)
{% endcontent-ref %}

***

## Local development instructions

Find the local development instructions for the different Create Collabo App projects in the tabs below, depending on the one you want to develop locally.

{% tabs %}
{% tab title="CLI" %}
_**Local development instructions:**_

* Head over to the GitHub repository: [https://github.com/collabo-community/create-collabo-app](https://github.com/collabo-community/create-collabo-app)
* Fork and clone the repository as shown in the [SWE contribution workflow](https://docs.collabocommunity.com/contribute/v/software-engineering/#git-workflow-fork-and-clone-repository).

***

_**Instructions for installing dependencies and linking CLI:**_

{% hint style="info" %}
Once you have the repository on your local computer, ensure you are _**in the root of the project's directory**_. Then install globally and uninstall globally following the steps below.
{% endhint %}

Install dependencies:

```
npm install
```

Link after installing dependencies, so that you can access/use the Create Collabo App commands in the terminal:

```
npm link
```

Unlink (this is for when you are done developing):

```
npm unlink
```

***

_**CLI commands and flags:**_

The way you operate/run the CLI is still largely the same as what is in the former [Node Mongo user doc](https://docs.collabocommunity.com/node-mongo/detailed-guide) at the moment. The only difference (for now) is the main CLI command i.e. Instead of `node-mongo`, use `collabo-be`. Similarly for the shorter version of the commands - instead of `nmgo`, use `c-be`.

***

#### Learning resources

* [Twilio | Dominik Kundel: How to build a CLI with node.js](https://youtu.be/s2h28p4s-Xs) - _YouTube video_.
* [Twilio | Dominik Kundel: How to build a CLI with node.js](https://www.twilio.com/blog/how-to-build-a-cli-with-node-js) _- blog post._
{% endtab %}

{% tab title="Backend API Boilerplates" %}
_**Local development instructions:**_

* Head over to the GitHub repository: [https://github.com/collabo-community/backend-api-boilerplates](https://github.com/collabo-community/backend-api-boilerplates)
* Fork and clone the repository as shown in the [SWE contribution workflow](https://docs.collabocommunity.com/contribute/v/software-engineering/#git-workflow-fork-and-clone-repository).

***

_**Instructions for installing dependencies and starting the development server:**_

{% hint style="info" %}
Once you have the repository on your local computer, follow the steps below.
{% endhint %}

* Change directory into any of these folders in the repository, depending on the template you wish to work on: `ts-esm-async-await` folder, `js-esm-async-await` folder, `js-cjs-async-await` folder or `js-cjs-then` folder.
* Once in the chosen folder, follow _**steps 1 to 4**_ in the tabs under the [Running the generated backend API application](https://code-collabo.gitbook.io/node-mongo-user/node-mongo-user-docs/readme#running-the-generated-backend-api-application) section of the former Node mongo user docs, depending on the connection setup type you prefer to use. \
  _**Some slight modifications to the steps exist:**_ We have removed the automated dev server for now. For _**step 4**_, just use `npm run dev:atlas` or `npm run dev:local` script commands accordingly.

***

_**Handling .env files during development:**_

* Retain the `.env.example` file so that it doesn't get deleted from our repo when you submit your code fix.
* Create a copy of the `.env.example` file, rename this copy to `.env` , then change the `PORT` and add other environment variables to store your secrets as desired or as needed in your `.env` file.

***

#### Learning resources

* [TomDoesTech: REST API with Node.js, Express, TypeScript, MongoDB & Zod](https://www.youtube.com/watch?v=BWUi6BS9T5Y).
* [TomDoesTech: Module '"mongoose"' has no exported member 'DocumentDefinition'.ts (tutorial fixes)](https://www.youtube.com/watch?v=5-1KuU-21uI).
* [Academind: Building a restful API with node.js](https://academind.com/tutorials/building-a-restful-api-with-nodejs/).
* [CodAffection: MEAN stack CRUD operations](https://youtu.be/UYh6EvpQquw) - _1st 33 minutes_.
{% endtab %}
{% endtabs %}

***
