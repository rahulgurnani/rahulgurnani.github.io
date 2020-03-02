---
title: "Developing scalable flutter apps"
last_modified_at: 2020-02-13T16:20:02-05:00
categories:
  - Blog
tags:
  - flutter, design patterns
---

This post is about my recent experiences of developing flutter app at current place of work. I found flutter very developer friendly and am impressed by the cross platform nature of the sdk (android, iOS, web even Desktop apps 😮).

In what follows, I share some patterns and practices that I find useful for development.

### Widget Tree

I think drawing a widget tree, based on the mocks given by an UI designer should be the first step, before writing any code. This gives you an insight on the common components in the UI. If you are using the provider pattern, widget tree makes it easier for you to decide where will the provider for a state be initialized.
