---
layout: post
title: "Updates and Fixes!"
date: 2025-04-08 11:30
category: Disco Tray
author: Joseph Washum
tags: [Disco Tray]
summary: Reworked aspects of the Firebase rules, Fixes to MapDisplay working, and Fixes to the rating system!
---
Good evening everyone, and welcome back! If you have been following along then you know that we are getting dangerously close to finishing up the Faulkner Footsteps app for our clients over at the Faulkner County Historical Society! This past week has truly been a wrap-up week for myself and my teammate Colten. As we have neared ever closer to getting this app done we have tried to ensure that the app is working as best as possible each week, but it always helps to have a second pair of eyes look over something.

Thus, Dr. Goadrich reviewed our app and beta tested some things as a first time user of our app. Finding that there were issues in our firebase which were looking for admins, specifically and not allowing some of the basic functionality of the app to happen for normal users (I.e. Ratings unavailable for new users). So Colten and myself got straight to work and managed to get a pull request in by the end of the weekend to ensure that the app was fully functional as of the issues that we had currently found. To do some of our fixes this involved, on my end, editing / updating the firebase rules and working directly on adding additional error handling and bug fixing to several of the functions in our app state and login pages which dealt with looking for if a user was an admin or not.

But finally, and at long last we nearing the end of our journey my friends! This week we are working on beta testing the app with members of disco tray and previous members of the project to hopefully get some substantial feedback and ensure that our app is as good as it possibly can be. I look forward to talking with you all again soon and look forward to updating you all about how our progress goes with beta testing!