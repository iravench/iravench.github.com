---
layout: post
title: "Business Software Development Part 2"
date: 2013-01-02 12:00
comments: true
categories: [Software]
---
In [Part 1](http://blog.iraven.ch/post/2012/12/07/Business-Software-Development-Part-1), I provided the definition of Business Software Development. The conclusion is that Business is the final goal of a non-stop development process, and computable Device is the major channel to bridge Business and the end users.

### The challenges
What it really means to Software Development?

- Business is the final goal. (Never ever getting tired repeating this)
- Development is a Process and it works only when deliver.
- Delivery means shipping, means putting Business into Device.
- So the goal of Development is to make sure Business gets delivered to Device.

The major headaches stop us from getting there?

- We have one business model, yet it refuses to keep still.
- We have one business model, yet it targets multiple devices.
- Different devices require us knowledges of different platforms and tools.
- New device of good potentials for Business keeps coming up.
- Device has its own limits, which makes the One-Size-Fits-All design impossible.

Maybe not so bad after all?

- Although Business changes, it changes gradually.
- Although Device are many, some share common characteristics.
- Although we will have to face different Device platforms, we're running the same Business.

The emphasis here is that the escalated complexity of running Business the multi-devices fashion brings us developers new kinds of challenges. You should now stop considering yourself a mere Web Developer. Instead, you should approach other devices, design and code for the big platform. And this hardship is not for developers only.

### Searching for a way out
To begin the search of possible solutions, I list bellow a few points which I think are critical to have in order for any solution to be effective.

1. Abstract business logic from details — away from any detail including device hardware detail, data persistence detail, User Interface detail, Programming Framework detail…
2. Implement business logic as self-serving modules, they should be small at scale, easy to understand, clearly defined basic building blocks of the business domain.
3. Implement sub-application level modules/features to address common business scenarios, which should be based on the above business modules, away from details too.
4. Write automated tests, both the business and sub-application level modules should be covered.
5. Plan for all targeting devices, to identify and manage the common and unique feature sets, make sure the business goal covered fully.
6. Bridge the business and sub-application level modules with implementation details only when develop and deploy for a specific device. 

Mixing business logic with device details is bad because it makes the business logic hard to change. And the situation gets worse when the business starts targeting multiple devices, for each of this device requires unique platform knowledge to be operated effectively. Mixing Business logic with details makes it hard for the logic to be ported from one platform to another.

Business logic should be modularized, this makes sure future changes to the business isolated within a handful of modules. With sub-application level modules addressing the common business scenarios, features could be defined and maintained in a multi-devices environment reusing these modules.

Automated test is extremely important. When developing for a new platform, you'll have to port over at least part of your business logic due to the introduction of a new platform. Tests under such circumstances offer you great confidence. (Test should be simple, easy to write and read, therefore much easier to be ported over to and ran from a new platform, compare to the business logic.) Tests should not be developer only, higher level testing and integration is crucial for Business to be expressed consistently across devices.

Details only make sense to a specific device. By carefully implementing details the way it requires, you get the best performance while not complicating the business logic. For example, when a business feature requires user identity, a web application may read it from Browser Cookie, while a mobile application may need to retrieve the information from a Keychain Service.

So Business starts out an abstract idea and it should be maintained that way, the it got split into modules, realized into a specific form by details for each targeting device. A careful solution of Development process should cover above listed points in order to achieved the Business goal effectively under the new challenges.