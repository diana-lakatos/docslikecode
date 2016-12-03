---
layout: post
title: Reviewing Docs Efficiently in GitHub
excerpt: "Do you know what tool was found to be most effective at saving lives in hospitals?"
modified: Sat Dec 3 08:44:08 CST 2016
categories: articles
tags: [github, git, review, edit, write, approve, request changes, pull request, writing]
image:
  feature: jocelyndurston-life-saving-picnic.jpg
  credit: Flickr jocelyndurston
  creditlink: https://flic.kr/p/5dYY25
comments: false
share: true
---

Do you know what tool was found to be most effective at saving lives in hospitals? Literally life-saving... 

Is it new technology? No. It’s a clipboard, pen, and a well-designed checklist. Checklists can save lives. 

How about a checklist for documentation reviews to save the docs?

You know you want a quick win in reviewing. For one thing, it’s great to remain in the GitHub context. It’s also great to train others to become better reviewers. What? Train others with your Git-works-for-writing mind tricks? Yes, yes you can.

The newest addition to GitHub’s web interface includes Reviews. This new collaboration feature gives you the chance to formally “approve” or “request changes” to pull requests. You can also summarize your review as well as line-by-line leave comments, editing them or deleting them before putting the whole summary bundle together. This workflow is game-changing for treating docs like code in a version control system. I love how much discussion this enables amongst various team members - writers, developers, product managers, designers, even customers!
 
Your team can make their own review checklist. Here an example based on my experience:

### Self-check: (Should I even review this?)

* Do I know enough about the subject to review for accuracy?
* Do I have the configuration in place to test the instructions?
* Have I been reviewing for an hour already? If so, take a 20 minute break.

### Organization/Audience:

* Does this piece of information belong in the section or deliverable where it is placed?
* Are the headings correct for the style guidance and overall organization?
* Is the flow and structure logical for a reader to follow?
* Will the audience understand the context as well as why this information matters to them?

### Tooling:

* Does the document build correctly without errors?
* Is the output formatted as expected?

### Accuracy:

* Have you run all the commands in the doc review?
* Are the results as expected?
* Do they match the version of the software that is in this deliverable?
* If there are screenshots, are they accurate for the version?
* Are trademarked names used properly?
* Are preferred terms used correctly? For example, plugin or plug-in.
* Is there any security concern with the information?
* Has data been properly redacted if needed?
* If the writer intends for the patch to be a bug fix, read the bug itself. Does the doc addition or edit fix the bug?

### Syntax:
* Is the grammar correct?
* Is the markup correct?
* Is the document spell-checked?
* Are acronyms spelled out at first use?
* If a glossary is in place, are definitions of new terms available?

### Meta information:
* Is the commit message clear as to the purpose of the change?
* Are bug fixes correctly linked in the commit message?

The best coaching for better reviews happens when you wait to respond. Instead of reacting immediately to a pull request, wait. Give others a chance to review first, especially those you want to improve in their reviews. Then, if you find anything, you can comment later and the first reviewer can learn more.
Get your product manager to review your docs. You know you want their insights. They know the customer best, they know the product even better, and they know the business inside and out. Yours may or may not be on GitHub now, but get them an account and show them how fun it is to add thumbs-up emojis to a comment. 👍

## Resources

If you want to get better at reviews and coach others in reviews, read more.

Smart Bear is a company here in Austin and has gathered best practices for code review.

Because we want to treat docs like code, think about how these could work well for documentation also:

[Best Practices for Code Review](https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/)

[Collaborator's Guide to a Better Peer Code Review](https://smartbear.com/learn/code-review/guide-to-code-review-process/)

{% include sign-up.html %}