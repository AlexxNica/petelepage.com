---
layout: post
title: 'Bug Bounty: Disappearing Templates'
date: '2006-03-13 09:06:00 -0500'
categories: blog
tags:
- MSDNBlogPost
comments: []
---

I've come across another bug that I've decided to put up for a bug bounty.&nbsp; This is a fairly hot topic within the forums right now, and a few people are seeing it, and it completely stops development of new web applications for them, and thats just not acceptable to me.

It seems that for some reason, all of the web templates in the "New Website" dialog disappear.&nbsp; The templates are there in the templates folder, it's just that VS and VWD doesn't seem them.&nbsp; Trying to run "devenv /installvstemplates" and "devenv /setup" or a repair setup doesn't seem to bring them back, the only way to bring them back is to uninstall and reinstall.

So, if you can find consistent repro steps that get the templates to disappear (you can't just delete the templates from the directory), and it's a real user scenario, I'll award you the bounty once it's been verified and meets the rules for the bug.

What is the bounty you ask?&nbsp; I've got another copy of the VS2005 &amp; SQL 2005 launch software that I can give away, and if that doesn't suit your fancy, I'm sure I can find something else along the same lines.&nbsp; XBox 360 games maybe, other Microsoft Titles maybe, I'll see what connections I can pull in for this!

If you get the repro steps, Reactivate the [bug](http://lab.msdn.microsoft.com/ProductFeedback/viewFeedback.aspx?feedbackid=389bdf85-cd4d-4795-8e62-d3c480b3e111) on the MSDN Product Feedback Center Site.&nbsp; When you reactivate the bug, include your repro steps, and any other info that is pertinent about the bug, then email me to let me know you've found the repro steps.