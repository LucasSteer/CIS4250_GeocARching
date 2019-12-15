# Introduction

This is a public repository for the group project produced by Lucas Steer, Silas Sales, Davis Onyeije, and Aaron Gordon for their CIS*4250 course at the University of Guelph. As part of this course students were asked to form groups of 2-4 individuals, determine a project idea and scope, and implement their idea within 3 months (roughly from the start of September to the end of November).

# What is GeocARching

This project is an Android mobile app with the working title "GeocARching". The core concept was to replicate the [Geocaching](https://www.geocaching.com/) experience entirely within AR.

# What it does

The app uses the device's location and the Google Maps API to place caches at a specific real-world location so that users needed to be within roughly 10m of that location to jump into AR and find the cache.

AR functionality was powered by ARCore, Sceneform, and Google Cloud Anchors to allow users to scan real-world geometry (such as a table) and place 3D models in AR. When other users got to the real-world location that the cache was placed at, they would need to move their device around and use the built-in camera to find the cache in AR.

We also implemented basic gamification features (such as a levelling and XP system fueled by finding caches) and leaderboards to see who had found the most caches.

# Future of the project

There are plenty of bugs (and "jank") in this project, however, overall it met the goals that we set out to accomplish when we started the project. I, personally, would like to resolve some of these issues, clean up the codebase, and implement automated testing to improve the project's stability. In addition, there was functionality that I had envisioned that wasn't realistic to expand upon within the scope and timeline of the project that I hope to resolve.

# Notes

## Accounts and keys

You may notice that there are API keys, email contacts, etc. that are exposed; all of these are no longer valid or have been shutdown.

## 3rd party resources

In addition to the "andy" model, we used the following 3D models:
* Car: https://www.turbosquid.com/FullPreview/Index.cfm/ID/1055619
* Pepper: https://www.turbosquid.com/FullPreview/Index.cfm/ID/1467304
* Cactus: https://www.turbosquid.com/FullPreview/Index.cfm/ID/1340212

If any of the creators or associated parties have issue with the models existing in this application, please contact me and they will be removed.