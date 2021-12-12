---
layout: post
title:  Landing Page
date:   2021-12-05
description: >-
  We need to understand how the users engage with our landing page by collecting
  analytics and hostspots. Equally, we've implemented a newsletter to engage
  back with the users.
---

Our new landing page is located at
[https://shibui-events.web.app/](https://shibui-events.web.app/).

The webpage was created using [Vue.js](https://vuejs.org/) and hosted using
[Firebase](https://firebase.google.com/) (via their hosting service).

# Newsletter

We've implemented a simple newsletter by letting users enter their email and
then storing them securely in
[Firestore](https://firebase.google.com/products/firestore). After gathering
these emails we can use them to send email about future updates, releases,
events etc.

# Analytics

To get a grasp of our target audience, we've added
[Google Analytics](https://marketingplatform.google.com/about/analytics/) to the
landing page. This allows us to collect anonymous data about our users.

# Hostspots and usage

Other usefull insights we can gather from the landing page are hostspots and
usage patterns. These are obtained using [Hotjar](https://www.hotjar.com/) which
lets us understand how users behave on your site, what they need, and how they
feel.
