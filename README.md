# MindNest Project

A project created in flutter that facilitates communication & concept sharing between Psychologists & VR/AR Developers.

## Getting Started

A live demo of this application is hosted at https://algernyan.github.io

This application is written in Flutter, so in order to build and run the application please follow the instructions here: https://docs.flutter.dev/get-started/install

## How to Use 

**Step 1:**

Download or clone this repo by using the link below:

```
https://github.com/algernyan/algernyan.github.io.git
```

**Step 2:**

Go to project source folder and execute the following command in console to get the required dependencies: 

```
flutter pub get 
```

**Step 3:**

Run the following command to build the application for the web.

```
flutter build web
```

Additionally, you can run the following command to run the application in debug mode.

```
flutter run -d chrome
```

### Folder Structure
The lib folder contains the main code for the application.

```
1- info_pages - Contains all the info pages for Mental Health concepts definitions
2- vr_info_pages — Contains all the info pages for VR/AR concepts definitions
3- forum.dart — Contains the forum for VR/AR Developers and Psychologists to communicate through
4- research.dart - Populates the research page with relevant research in the mental health treatment field
5- vr_database.dart — Constructs the vr/ar knowledgebase
6- database.dart — Constructs the Mental Health knowledgebase
7- main.dart - This is the starting point of the application. All the application level configurations are defined in this file i.e, theme, routes, title, orientation etc.
```
