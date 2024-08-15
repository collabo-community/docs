---
description: SOFTWARE ENGINEERING CONTRIBUTING DOC FOR COLLABO COMMUNITY APP
---

# Collabo Community App

***

## Project description - page link

Find project description in the page attached below.

{% content-ref url="https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/collabo-community-app" %}
[Collabo Community App](https://app.gitbook.com/s/D4inNwzMBU3WuBySeYcV/collabo-projects/collabo-community-app)
{% endcontent-ref %}

***

## Local development instructions

Find the local development instructions for Collabo Community App projects in the tabs below, depending on the one you want to develop locally.

{% tabs %}
{% tab title="Web Client" %}
_**Local development instructions:**_

* Head over to the GitHub repository: [https://github.com/collabo-community/web-client](https://github.com/collabo-community/web-client)
* Fork and clone the GitHub repository as shown in the [SWE contribution workflow](https://docs.collabocommunity.com/contribute/v/software-engineering/#git-workflow-fork-and-clone-repository)

***

_**Instructions for installing dependencies and starting the frontend web client:**_

{% hint style="info" %}
Once you have the repository on your local computer, ensure you are _**in the root of the project's directory**_. Then install and run following the steps below.
{% endhint %}

Install dependencies:

```
npm install
```

Run the development server:

```
npm run dev
```
{% endtab %}

{% tab title="Mobile Client" %}
_**First time Setup Instructions for the mobile client:**_

* Install flutter, and configure every other thing you need to get flutter apps running on your computer - See [flutter docs](https://docs.flutter.dev/get-started/install).
* Run `flutter doctor` on the flutter console or in your terminal, to confirm that all that you need has been installed or not. Then install whatever is left if any.
* Also set up Android Studio and/or Xcode, and their mobile phone emulators/simulators.

***

_**Local development instructions:**_

* Head over to the GitHub repository: [https://github.com/collabo-community/mobile\_client](https://github.com/collabo-community/mobile\_client)
* Fork and clone the GitHub repository as shown in the [SWE contribution workflow](https://docs.collabocommunity.com/contribute/v/software-engineering/#git-workflow-fork-and-clone-repository)

***

_**Instructions for installing dependencies and starting the mobile client:**_

{% hint style="info" %}
Once you have the repository on your local computer, ensure you are _**in the root of the project's directory**_. Then follow the steps below.
{% endhint %}

* Install package dependencies with flutter command:

```
Flutter pub get
```

* Run the commands to prevent error:

```
flutter pub outdated
```

```
flutter pub upgrade
```

* Then run the app on your emulator or physical device

***

#### Learning resources

* [Flutter Mapp | Flutter Tutorial For Beginners in 3 Hours](https://www.youtube.com/watch?v=CD1Y2DmL5JM)
{% endtab %}

{% tab title="Backend Server API" %}
{% hint style="warning" %}
The backend aspect of the project has not yet started.
{% endhint %}
{% endtab %}
{% endtabs %}

***
