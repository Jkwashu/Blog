---
layout: post
title: "Logging Admins"
date: 2025-03-04 11:20
category: Disco Tray
author: Joseph Washum
tags: [Disco Tray]
summary: Worked on Reintegrating the previous implementation of admin page that was never merged, ran into some issues, but finished strong with adding new life to the log in page!
---
Hello again everyone! Well this was a bit of a hectic week if I do say so myself, its a bit of a story so feel free to sit back and get your popcorn ready before reading. A few weeks ago if you recall I updated you all with new news of a brand spankin new admin page! Unfortunately due to time constraints and not knowing if an admin page was something that the clients would want, we made the decision to not worry about an admin page.

Well earlier in the week, last Thursday my team and I went to meet our client for the first time since working on the project and give her an update as to how the app had come along since she had last seen it. While she was very pleased with our progress she gave us a list of what to do next to fully bring the app to life. Thus, a conversation about having a way for her to add or change sites within the app was born, and I had a green light. Of course there were other things, but the admin page is my baby at this point, and I want to make it as pristine as possible for our client's eyes the next time that we see her!

So, I worked on the administration page for a majority of my time this week, I grabbed the old code, reformatted some of my rushed aspects and got to work reintegrating it in our app. I hook up the admin page so that you can only access it if you have logged in as an admin, and you have got to our handy-dandy profile page to click to see the admin page. And well, its all there, and most of all it worked (kinda).. Well the issue is, my previous implementation of the code had not seen the light of day since before Colten had made changes to the way we handled images in our firebase, I was unaware of exactly what changed and thus, our problem began.

So in editing the test site, my admin page recreated a version of the test site which made the image a string (as set up in the app_state 'create site' function) but this happened to be very destructive and blacked out the app for a bit until Dylan and I found that images must be arrays of strings now and the app was back online. Now you're probably thinking surely thats it right? The admin page works now and it was all a 'great success' as some might say, but no.

You see my friends if nothing else I needed to know if my fixed version fully worked, in the case one of us down the line created or edited a page and it was my fault the whole thing broke again. Well you see where this is going.. So I tried again, low and behold, changes saved, firebase updated, but upon returning to the historical sites page, I was met with my app crashing once again. And again, and again.

Well, that essentially sums up how many of my hours went this week, endless debugging my mistakes and attempting not to brick the app in the process for Colten or Dylan. Which I guess I was mildly successful at, but ultimately it just wasn't a very successful week, and I look forward to finding what was wrong with my implementation and getting this admin page up and running for good the next time around.

With the remaining time that I had I scrapped my admin page changes and stowed them away in a separate folder, working more directly on the app and improving the log in page. Which took a bit of time and re-formatting, but turned out looking really good ! So now Faulkner Footsteps is completely all one theme! Yippie !

So that about summarizes everything folks, I look forward to updating you all with a successful week very very soon, and until next time stay safe everyone !