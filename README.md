# Awesome Progressive Web Apps [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of Progressive Web Apps resources.

> Progressive Web Apps are experiences that combine the best of the web and the best of apps. They are useful to users from the very first visit in a browser tab, no install required. As the user progressively builds a relationship with the App over time, it becomes more and more powerful. It loads quickly, even on flaky networks, sends relevant push notifications, has an icon on the home screen and loads as a top-level, full screen experience.
>
> -- <cite>[Google Developers - Your First Progressive Web App](https://developers.google.com/web/fundamentals/getting-started/your-first-progressive-web-app/?hl=en)</cite>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

If you want to contribute, please read the [contribution guidelines](contributing.md).

## Contents

- [Must Reads](#must-reads)
- [Learning Resources](#learning-resources)
- [Reference](#reference)
- [Browser Support](#browser-support)
- [Libraries and Tools](#libraries-and-tools)
- [Videos](#videos)
- [Case Studies](#case-studies)
- [Sample Progressive Web Apps](#sample-progressive-web-apps)
- [Specific Technologies](#specific-technologies)
  - [Service Workers](#service-workers)
  - [CacheStorage API](#cachestorage-api)
  - [Background Sync](#background-sync)
  - [Installable Web Apps](#installable-web-apps)
  - [Push Notifications](#push-notifications)
  - [IndexedDB](#indexeddb)

## Must Reads

- [Google Developers - Your First Progressive Web App](https://developers.google.com/web/fundamentals/getting-started/your-first-progressive-web-app/?hl=en) - A step-by-step guide to building a progressive web apps using the app shell pattern.
- [Wired - Wait! The Web Isn’t Dead After All. Google Made Sure of It](http://www.wired.com/2016/04/wait-web-isnt-really-dead-google-made-sure/) - The behind the scenes story of progressive web apps for non-developers.

## Learning Resources

- [Awesome Service Workers](https://github.com/TalAter/awesome-service-workers) - A collection of awesome resources for learning service workers.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - This free Udacity course is a must if you're planning on building a progressive web app.
- [Service Workers W3C Specification](https://www.w3.org/TR/service-workers/) - The official service workers spec.

## Browser Support

- [Can I Use - Service Workers](http://caniuse.com/#feat=serviceworkers) - Up-to-date browser support table of ServiceWorker API.
- [Is Service Worker ready?](https://jakearchibald.github.io/isserviceworkerready/) - Current status of ServiceWorker support in different browsers.

## Videos

- [Instant Loading: Building offline-first Progressive Web Apps - Google I/O 2016](https://youtu.be/cmGr0RszHc8) - A quick dive into the most common technologies and techniques for building progressive web apps.
- [Offline Web Applications Using IndexedDB & Service Worker](https://www.udacity.com/course/offline-web-applications--ud899) - This free Udacity course is a must if you're planning to dive deep into service workers.
- [Progressive Web Apps (Chrome Dev Summit 2015)](https://www.youtube.com/watch?v=MyQ8mtR9WxI) - An introduction to progressive web apps by Alex Russell and Andreas Bovens.
- [Polymer and Progressive Web Apps: Building on the modern web - Google I/O 2016](https://www.youtube.com/watch?v=fFF2Yup2dMM) - Using Polymer to build progressive web apps.

## Case Studies

- [Building the Google I/O 2016 Progressive Web App](https://developers.google.com/web/showcase/2016/iowa2016) - Building and launching a progressive web app using web components, Polymer, and material design.
- [AliExpress Case Study](https://developers.google.com/web/showcase/2016/aliexpress) - AliExpress increases conversion rate for new users by 104% with new progressive web apps.
- [eXtra Electronics Case Study](https://developers.google.com/web/showcase/2016/extra) - United eXtra Electronics grows eCommerce sales by 100% with Web Push Notifications.
- [Jumia Case Study](https://developers.google.com/web/showcase/2016/jumia) - Push Notifications help Jumia reverse cart abandonment and increase conversions by 9X.
- [Konga Case Study](https://developers.google.com/web/showcase/2016/konga) - Konga cuts data usage 92% with new Progressive Web App.
- [Suumo Case Study](https://developers.google.com/web/showcase/2016/suumo) - Japan's top real estate site supercharges new listings with web Push Notifications and sees a 31% open rate for notifications.

## Sample Progressive Web Apps

- [PWA.rocks](https://pwa.rocks/) - A showcase of several progressive web apps, collected by the [Opera Dev Relations team](https://twitter.com/ODevRel).
- [SVGOMG](https://jakearchibald.github.io/svgomg/)
- [Guitar Tuner](https://aerotwist.com/blog/guitar-tuner/)
- [Voice Memos](https://voice-memos.appspot.com/)
- [Hacker News](https://react-hn.appspot.com/)

## Specific Technologies

### Service Workers

- [Awesome Service Workers](https://github.com/TalAter/awesome-service-workers/) - A curated collection of the finest service worker resources.

### CacheStorage API

- [Offline Storage for Progressive Web Apps](https://medium.com/@addyosmani/offline-storage-for-progressive-web-apps-70d52695513c) - The current state of offline storage in the browser
- [CacheStorage API](https://developer.mozilla.org/en-US/docs/Web/API/Cache) - API docs, and sample code from Mozilla.

### Background Sync

- [Introducing Background Sync](https://developers.google.com/web/updates/2015/12/background-sync) - A gentle introduction to background sync, along with some great videos and code samples.
- [Background Sync Explained](https://github.com/WICG/BackgroundSync/blob/master/explainer.md) - The official "explainer" document for background sync, including one-off synchronization and periodic synchronization.
- [Background Sync Spec](https://wicg.github.io/BackgroundSync/spec/) - The WIP spec for Background Sync.

### Installable Web Apps

- [Increasing Engagement with Web App Install Banners](https://developers.google.com/web/updates/2015/03/increasing-engagement-with-app-install-banners-in-chrome-for-android?hl=en) - An intro to App Install Banners and making sure Chrome offers your web app to your users.
- [Installable Web Apps with the Web App Manifest in Chrome for Android](https://developers.google.com/web/updates/2014/11/Support-for-installable-web-apps-with-webapp-manifest-in-chrome-38-for-Android) - An introduction to installable Web Apps in Chrome for Android.

### Push Notifications

- [Can I Use - Push API](http://caniuse.com/#feat=push-api) - Up-to-date browser support table of Push API.
- [Chrome Platform Status - Web Notifications](https://www.chromestatus.com/feature/5480344312610816) - Implementation status for Chrome and other browsers.
- [PWA Dev Summit 2016 codelab - Push Notifications](https://developers.google.com/web/fundamentals/getting-started/push-notifications/?hl=en) Up-to-date getting started tutorial for Progressive Web App, Push Notifications and service worker basics.
- [Using the Push API](https://developer.mozilla.org/en-US/docs/Web/API/Push_API/Using_the_Push_API) - An article introducing Push API.

### IndexedDB

- [IndexedDB API](https://developer.mozilla.org/en/docs/Web/API/IndexedDB_API) - API docs, key concepts, and sample code from Mozilla.
