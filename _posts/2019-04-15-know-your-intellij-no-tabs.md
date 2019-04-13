---
layout: post
title:  "Know Your IntelliJ – No tabs"
date:   2019-04-15 06:00:00 +0200
author: "Kamil Kubacki"
tags: ide java
---

In the next post of Know Your IntelliJ series, I would like to help you
with getting rid of navigation tabs' hell. By navigation tabs' hell I mean
a situation in which we get multiple files' tabs of opened and showing up at
editor's screen. The image below presents the sample screen with multiple
files' tabs opened:

<img src="/images/blog/posts/know-your-intellij-no-tabs/tabs-view.png" alt="tabs-view" />

This is caused by two factors: default IntelliJ settings and our usage.

### Default navigation with tabs
By default, when we get our fresh IntelliJ installed, each file we open
to view is being put inside tabs' list in the editor's view.
Because of that, when we work in big projects where we need to open
multiple class files to understand whole flow of data processing,
we end up with much worse situation than at the first image. Moreover,
navigating through the tabs of opened files can often be
disturbing and annoying. For me, it was affecting my productivity even
though, I was using shortkeys to jump from each tab to the other
(to get to the recently viewed files).

Finally, I found a better way to overcome this issue. I totally removed
the files' tabs list from my IntelliJ.

### Navigation without tabs
Let's get the fast walkthrough how to disable files' tabs displaying
in your editor's window and how to navigate without it.

First of all, we start by opening Settings windows (`CMD and ,` on Mac OS)
and we type `placement` in the search box. If you followed the instruction
you should see the following image:

<img src="/images/blog/posts/know-your-intellij-no-tabs/settings-tabson.png" alt="no-tabs-view" />

We need to change `Tab Appearance` -> `Placement` dropdown from `Top` to
`None`. After the change, please click `Apply` and `OK` to close the
placement settings. Your settings screen should look the same as in the
image below, after applying changes to `Placement` dropdown.

<img src="/images/blog/posts/know-your-intellij-no-tabs/settings-tabsoff.png" alt="no-tabs-view" />

As a result of settings change, we get editor's view without
any files' tabs displaying on it. The image below presents the state
after the changes are completed.

<img src="/images/blog/posts/know-your-intellij-no-tabs/no-tabs-view.png" alt="no-tabs-view" />

**Now, the main question - how can you navigate through the recently
opened files?**

The answer is `CMD and E` on Mac OS, which presents the files we recently
viewed and/or edited. With that shortkey, it is much easier to keep the
no tabs editor view and still benefit from the list of files
we worked on.

Below you can see the `Recent files` window which opens after `CMD and E`
hit on your Mac.

<img src="/images/blog/posts/know-your-intellij-no-tabs/recent-files.png" alt="no-tabs-view" />

### Summary

