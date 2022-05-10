## Table of Contents
* [Overview](#overview)
* [User Guide](#user-guide)
    * [Landing Page](#landing-page)
    * [Sign Up / Sign In Pages](#sign-in-and-sign-up)
    * [Index Pages](#index-pages)
    * [Home Page](#home-page)
    * [Add Spot Page](#add-spot-page)
    * [User Page](#user-page)
    * [Spot Page](#spot-page)
* [Community Feed](#community-feedback)
* [Developer Guide](#developer-guide)
  * [Installation](#installation)
* [Team](#team)
    * [Deployment](#team)
    * [GitHub Organization](#team)
    * [M1 Project Page](#team)
    * [M2 Project Page](#team)
    * [M3 Project Page](#team)
    * [Team Contract](#team)


## Overview

*Walking with Pele* is a web application that will provide a portal for students in search of adventure. Oahu contains a multitude of experiences for individuals to encounter. This web application will enable students to find new experiences on Oahu while also sharing their own for others to see. By doing so, the application will build upon itself in a way that it will provide new paths for new students to follow.


## User Guide

This section showcases the application's user interface along with its capabilities.

### Landing Page

This page greets the user, along with giving a brief overview of the application's capabilities.

![](images/landing-page-wwp4.png)
![](images/landing-page-wwp4-p2.png)
![](images/landing-page-wwp4-p3.png)

### Sign in and Sign up

By clicking on the "Login" button, users have the option to either "Sign in" or "Sign up". If the user already has an account, they may choose "Sign in" and will be brought to the following page to do so:

![](images/sign-in-wwp3.png)

If the user does not have an account, they may choose "Sign up" to register their own account and will be brought to the following page accordingly:

![](images/sign-up-wwp4.png)

### Index Pages

This application provides a few pages that present its database.

The "Random Spot" page recommends a "Spot" for users to check out. 

![](images/random-spot3.png)

The "Top Spots" page shows users the 3 most liked Spots in the entire application.

![](images/top-spots.png)

The "All Spots" page allows users to see all the Spots added to the application and all of their information. There will also be a search function implemented that will allow users to filter through Spots given certain requirements.

![](images/list-spots4.png)

### Home Page

After the user has logged in, they are taken to the home page, which is quite similar to that of the "Landing" page with the inclusion of the NavBar.

![](images/home-page-wwp3.png)

### Add Spot Page

Logged-in users are also given the ability to create and define "Spots" to share with other users.

![](images/add-spot4.png)

### Map Page

The Map page places color coded Markers on each Spot currently within the database. There are also smaller inclusions of this map within each Spot page with their individual marker shown.

![](images/map-wwp.png)

### User Page

This page contains basic information about a user such as their Name, along with the "Spots" they have visited and reviewed.

![](images/user-page3.png)
![](images/user-page4.png)

### Spot Page

This page contains basic information about a "Spot" such as the location name, address, type of location, etc. Users are also able to start conversations with other users through the comments on each Spot page. Additionally, users are also able to remove their own comments.

![](images/spot-comment.png)
![](images/spot-comment2.png)

## Community Feedback

This is a summary of the feedback from the University of Hawaii at Manoa community.

## Developer Guide

This section provides information about how to use our code for their own projects.

### Installation

The first step would be to [install Meteor](https://www.meteor.com/install).

Following the installation, visit our [application GitHub page](https://github.com/walking-with-pele/walking-with-pele). While there, select the option to "Use this template" to create a GitHub repository initialized with your own copy of the application. Then, clone the repository to your computer locally.

Assuming everything was successful, change directory to the walking-with-pele/app directory and install the required libraries with the following command:
```
$ meteor npm install
```

After doing that initial installation of the required libraries, install the libraries for React Google Maps.
```
$ meteor npm install --save react-google-maps
```

Right after installing the libraries, start the application with the following command:
```
$ meteor npm run start
```

The application should appear at [https://localhost:3000](https://localhost:3000).

## Team

*Walking with Pele* is designed, implemented, and maintained by the combined efforts of Hyuma Tsuchiya, Don Maddock, Kai He, Zhixin Li, and Joshua Rico.

- [Deployment](https://walking-with-pele.xyz/)
- [GitHub Organization](https://github.com/walking-with-pele)
- [M1 Project Page](https://github.com/orgs/walking-with-pele/projects/1)
- [M2 Project Page](https://github.com/orgs/walking-with-pele/projects/2)
- [M3 Project Page](http://github.com/orgs/walking-with-pele/projects/3)
- [Team Contract](https://docs.google.com/document/d/14qmEBdDGsJFoggl1_zcuq7dORanDT3HtZ3sc19qAK7Y/edit?usp=sharing)
