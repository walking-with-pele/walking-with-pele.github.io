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
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
  * [Installation](#installation)
* [Development History](#development-history)
  * [M1 Project Page](#development-history)
  * [M2 Project Page](#development-history)
  * [M3 Project Page](#development-history)
  * [Deployment](#development-history)
* [Team](#team)
    * [Team Contract](#team)
    * [GitHub Organization](#team)


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

This following is a summary of the feedback from the University of Hawaii at Manoa community. Additionally, if you would like to give your own feedback on the application, please fill out this [form](https://forms.gle/54ZjE1mrfrv1hMre7).

![](images/comm-feedback-1.png)
 Scale: 1 (Highly Disagree) - 5 (Highly Agree)

![](images/comm-feedback-2.png)
Scale: 1 (Highly Disagree) - 5 (Highly Agree)

![](images/comm-feedback-3.png)
Scale: 1 (Highly Disagree) - 5 (Highly Agree)

![](images/comm-feedback-4.png)

![](images/comm-feedback-5.png)
Scale: 1 (Highly Disagree) - 5 (Highly Agree)

![](images/comm-feedback-6.png)

![](images/comm-feedback-7.png)
Scale: 1 (Very Bad) - 5 (Very Good)

![](images/comm-feedback-8.png)

![](images/comm-feedback-9.png)

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

## Development History

Our project was developed through the practice of [Issue Drive Project Management](http://courses.ics.hawaii.edu/ics314f19/modules/project-management/), which the following Milestones were created:

### Milestone 1: Initial Development
As shown in [M1 Project Page](https://github.com/orgs/walking-with-pele/projects/1), the project began with initial ideas and HTML mockups to reflect it. 

### Milestone 2: Integration of Data Models
As ideas were solidified, for [M2 Project Page](https://github.com/orgs/walking-with-pele/projects/2), we began to integrate the use of Data Models into the application.

### Milestone 3: Final Adjustments
Lastly for [M3 Project Page](http://github.com/orgs/walking-with-pele/projects/3), we implemented final adjustments to ensure a better user experience.

### Deployment

You can visit our application with the following link: [Walking with Pele](https://walking-with-pele.xyz/).

![ci-badge](https://github.com/walking-with-pele/walking-with-pele/workflows/ci-walking-with-pele/badge.svg)

## Team

*Walking with Pele* is designed, implemented, and maintained by the combined efforts of Hyuma Tsuchiya, Don Maddock, Kai He, Zhixin Li, and Joshua Rico.

- [Team Contract](https://docs.google.com/document/d/14qmEBdDGsJFoggl1_zcuq7dORanDT3HtZ3sc19qAK7Y/edit?usp=sharing)
- [GitHub Organization](https://github.com/walking-with-pele)
