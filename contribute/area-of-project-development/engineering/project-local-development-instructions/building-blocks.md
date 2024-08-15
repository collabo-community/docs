---
description: SOFTWARE ENGINEERING CONTRIBUTING DOC FOR BUILDING BLOCKS
---

# Building Blocks

***

## Project description - page link

Find project description in the page attached below.

{% content-ref url="https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/building-blocks" %}
[Building Blocks](https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/building-blocks)
{% endcontent-ref %}

***

## Local development instructions

* Head over to the GitHub repository: [https://github.com/collabo-community/building-blocks](https://github.com/collabo-community/building-blocks)
* Fork and clone the repository as shown in the [SWE contribution workflow](https://docs.collabocommunity.com/contribute/v/software-engineering/#git-workflow-fork-and-clone-repository).

Find the local development instructions for the different Building Blocks projects in the tabs below, depending on the one you want to develop locally.

{% tabs %}
{% tab title="Blocks CSS" %}
{% hint style="info" %}
Once you have the repository on your local computer, ensure you are _**in the root of the project's directory**_. Then follow the steps below.
{% endhint %}

***

_**Installing project dependencies**_

Install dependencies (if you have not done so before):

```
npm install
```

***

_**Run and watch changes for Block CSS files**_

Run the script command below to compile/build the scss files into `css` files:

```
npm run blocks:css
```
{% endtab %}

{% tab title="Blocks TS" %}
{% hint style="info" %}
Once you have the repository on your local computer, ensure you are _**in the root of the project's directory**_. Then follow the steps below.
{% endhint %}

***

_**Installing project dependencies**_

Install dependencies (if you have not done so before):

```
npm install
```

***

_**Generating Blocks TS build files:**_

Run the script command below to compile/build the typescript files into `.js` and `.d.ts` files:

```
npm run blocks:ts:build
```

***

_**Testing out Blocks TS in other Collabo Community projects**_

{% hint style="info" %}
The BlocksTS library only works in projects using NodeJS environment i.e. it only works in projects where node\_modules folder is generated based on the dependencies/content of the package.json file.
{% endhint %}

Follow these steps when developing and testing out the changes made to the Blocks TS library, in some other Collabo Community project:

<mark style="background-color:yellow;">First steps:</mark>

* Ensure you have both the building building blocks repo and the repo for the project you want to test locally on your computer.
* Ensure that you have also followed the local development instructions to install dependencies, set them up and you are able to run them without problems.

<mark style="background-color:yellow;">Change directory into the project you want to use to test the BlocksTS library in. Then do the following:</mark>

* Link your local building blocks repo, using the relative path to your local building blocks repo. For example, if the repo folder for project you are testing with and the building blocks repo folder are on the same level and share the same parent folder, you would link it like so:

```
npm link ../building-blocks
```

* Then add the building blocks package to the project's dependencies as shown below. Check the package.json of the building blocks repo to know the version of the package to use. For example, if  building blocks' package.json has `"version": "0.0.0"` , you would add it to the package.json dependencies for the project you are testing with like so:

```
"@collabo-community/building-blocks": "^0.0.0"
```

* &#x20;Import what you need from building blocks, and start using/testing in the project.
{% endtab %}

{% tab title="Blocks Doc" %}
{% hint style="warning" %}
Development for Blocks Doc just recently started, things can change pretty quickly at the start of the project as it also includes research and experimentation.\
For now, ask about the latest local development instructions on our community Discord server and you'll be directed.
{% endhint %}
{% endtab %}
{% endtabs %}

***
