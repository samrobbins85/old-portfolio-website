+++
categories = ["hackathon"]
coders = ["samrobbins85", "karina-talibzhanova"]
date = 2020-06-11T23:00:00Z
description = "An Android App to keep track of electronic components"
github = ["https://github.com/samrobbins85/locatemytech"]
image = "https://res.cloudinary.com/samrobbins/image/upload/q_auto/v1593354325/original-removebg-preview_ywohmf.png"
title = "Same Home Different Hacks"
type = ""
[[tech]]
logo = "https://res.cloudinary.com/samrobbins/image/upload/q_auto/v1592150134/dart_eivof0.svg"
name = "Dart"
url = "https://dart.dev/"
[[tech]]
logo = "https://res.cloudinary.com/samrobbins/image/upload/q_auto/v1592150085/flutter_hxftsi.svg"
name = "Flutter"
url = "https://flutter.dev/"
[[tech]]
logo = "https://res.cloudinary.com/samrobbins/image/upload/q_auto/v1592151079/Cloud_Firestore_1-_Icon_Light_sddjno.svg"
name = "Google Firestore"
url = "https://firebase.google.com/products/firestore"

+++
In this project we made an Android app to keep track of electronic components.

## Installation

The code can be found here [https://github.com/samrobbins85/locatemytech](https://github.com/samrobbins85/locatemytech "https://github.com/samrobbins85/locatemytech"), it can be downloaded with

```bash
git clone https://github.com/samrobbins85/locatemytech.git
```

We haven't built the packages for this, so you will have to build it yourself using Flutter, instructions can be found here [https://flutter.dev/docs/get-started/install](https://flutter.dev/docs/get-started/install "https://flutter.dev/docs/get-started/install").

## Pages

### Homepage

When you open the app, you are greeted with the following page

![](https://res.cloudinary.com/samrobbins/image/upload/q_auto/v1593442133/homepage_yn25xq.jpg)

This allows you to see all the components you have. A new component can be added with the plus button at the bottom and a component can be edited by tapping on it.

The main code for this page is stored in `main.dart`. It consists of the class `_MyHomePageState` which defines all the content on the page. The widget `build` describes the content around the edge of the page, such as the titlebar. The widgets `_buildBody` `_buildList` and `_buildListItem` are then used to define the content on the page.

### Projects

By opening the sidebar and selecting projects, you will be taken to this page

![](https://res.cloudinary.com/samrobbins/image/upload/q_auto/v1593444927/projects_btsq2d.jpg)

This allows you to configure the projects you have to allocate components to. You can delete a project with the delete button and add a new project with the plus button at the bottom. This code for this page is stored in `projects.dart` and has a very similar layout to `main.dart`.