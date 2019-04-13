---
layout: post
title:  "Know Your IntelliJ – No tabs"
date:   2019-04-13 06:00:00 +0200
author: "Kamil Kubacki"
tags: ide java
---

In the next post of Know Your IntelliJ series, I would like to help you
with getting rid of navigation tabs' hell. By navigation tabs' hell I mean
a situation in which we get multiple files' tabs opened and showing up at
editor's screen. The image below presents the sample screen with multiple
files' tabs opened:

<img src="/images/blog/posts/know-your-intellij-no-tabs/tabs-view.png" alt="tabs-view" />

That kind of situation is caused by two factors: default IntelliJ's
configuration and our usage.

### Default navigation with files' tabs
By default, when we get our fresh IntelliJ installed, each file we open
to view is being put inside tabs' list in the editor's view.
Because of that, when we work in big projects in which we need to open
multiple class files to understand whole flow of data processing,
we end up with much worse situation than presented at the first image.
Moreover, navigating through the tabs of opened files can often be
disturbing and annoying. For me, it was affecting my productivity even
though, I was using shortkeys to jump from each tab to the other
(to get to the recently viewed files).

Finally, I found a better way to overcome this issue. I totally removed
the files' tabs list from my IntelliJ.

### Disabling the files' tabs
Let's get the fast walkthrough how to disable files' tabs displaying
in your editor's window and how to navigate without them.

First of all, we start by opening `Settings` window (`CMD and ,` on Mac OS)
and we type `placement` in the search box. If you followed
the instructions you should be able to see the similar image to the
one below:

<img src="/images/blog/posts/know-your-intellij-no-tabs/settings-tabson.png" alt="no-tabs-view" />

In the next step, we need to change `Tab Appearance` -> `Placement`
dropdown from `Top` to `None`. After the change, please click `Apply`
and `OK` to close the placement settings. Your settings screen should
look the same as in the image below, after applying changes
to `Placement` dropdown.

<img src="/images/blog/posts/know-your-intellij-no-tabs/settings-tabsoff.png" alt="no-tabs-view" />

As a result of the settings change, we get editor's view without
any files' tabs displaying on it. The image below presents the state
after the changes are completed.

<img src="/images/blog/posts/know-your-intellij-no-tabs/no-tabs-view.png" alt="no-tabs-view" />

### How to view the recent files?

The answer is `CMD and E` shortkey on Mac OS, which presents the files
we recently viewed and/or edited. With that shortkey, it is much
easier to keep the no tabs editor view and still benefit from
the list of files we worked on.

Below you can see the `Recent files` window which opens after `CMD and E`
hit on your Mac.

<img src="/images/blog/posts/know-your-intellij-no-tabs/recent-files.png" alt="no-tabs-view" />

### Summary

Proper and fast navigation is a key benefit we get from our IDE.
Sometimes though, we should apply changes to default IDE's configuration
to get our productivity up a bit. One of such examples is replacing the
files' tabs displaying in your editor's view with `Recent files` window
and no tabs view as this blog post was trying to describe.

If you enjoyed this post, please check the other ones from the
Know Your IntelliJ series on my blog.