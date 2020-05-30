---
title: "Developing scalable flutter apps"
last_modified_at: 2020-02-13T16:20:02-05:00
categories:
  - Blog
tags:
  - flutter, design patterns
---

This post is about my recent experiences of developing flutter app at current place of work. I found flutter very developer friendly. Most impressive thing about it is the cross platform nature of the sdk (android, iOS, web and even Desktop apps 😮).

In what follows, I share some patterns and practices that I find useful for development.

### Draw the Widget Tree

In my humble opinion, drawing a widget tree, based on the UI wire-frames should be the first step, before writing any code. This gives you an insight on the common components that would be used in your app. If you are using the provider pattern, widget tree makes it easier for you to decide where will the provider for a state be initialized. It also helps you structure your code

### Sketch out the BloCs

As a developer, it's often good idea to think in terms of the UI as a function of state of the app. So, given a state of the app, it should be straightforward to derive what the UI would look like. This helps in writing effective tests for the code.

### Coding

### Project Structure
