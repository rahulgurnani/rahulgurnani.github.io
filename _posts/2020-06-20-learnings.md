---
title: "Learnings as a Software Engineer"
last_modified_at: 2020-06-21T16:20:02-05:00
categories:
  - Blog
tags:
  - software engineering
---

In this post, I share my learnings, which are mostly based on my experience working as a Software Engineer at Indihood.

### Design documents are helpful

Whenever starting to build a new software or modifying a part of existing system, design document is where you write :
* what you want to do
* how would you go about doing it, why are you choosing one design/approach over other

It's also the place where your peers can share feedback and raise concerns, before you start coding. Often it's difficult to get everyone to read your design document, so it may be a good idea to tag relevant people to read sections or ask them relevant questions about the choice.

While coding, if there are changes in design choices because of some changes in requirements or some practical hurdles, it's good practice to update the design document. This helps you track how design evolved over time and adds visibility to the work you do. Design documents also help in justifying when something takes longer than expected because of update in software architecture.

Coding becomes easier once the design ready. You don't have to think too much because many choices have already been made while writing design document. 

### Leverage Concurrency

Having more than one task to work on at any point in time keeps one working even if one of the task hits a blocker. Leverage this by having at least 2 tasks to work on at any time. 

### Ease the task of code reviewer

Create pull requests (PR) which are easier to review, so that they reviewed quicker and better. For this, you should:
* Describe well what the code change is suppose to do in PR description
* Separate refactors from the actual code change, may be as a separate PR or separate commit
* Break the change into commits and write readable commit messages, so that people can review commit wise if the change is big
* if needed, arrange a meeting to explain the code

### Move chats/email to relevant documents/code

The communications that happen on chat or email over an aspect of system or piece of code often get lost. Try to move these to the relevant design document or as a note or TODO in your code. This way the discussion doesn't get lost and others can refer it in future. 
