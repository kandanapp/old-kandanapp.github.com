---
layout: post
title: "How to Contribute Code"
date: 2013-02-05 15:17
comments: true
categories: [Open Source, Development Process, Kandan]
---
<div class="alert alert-info">
	<h4>Note: </h4>This is a living Document. The most recent copy is always available on the <a href="https://github.com/kandanapp/kandan/wiki/How-to-Contribute-Code">Wiki</a>
</div>

### How To Contribute Code
Whether you've got a bugfix, documentation update, or new feature for us, these are the steps to follow to contribute code back into the main kandan repo.

**1. Get the latest code from Github**

You'll need to understand a little bit about how git and gihub work before this step (if you need an introduction guide, Github [has a good one](http://learn.github.com/p/intro.html) you can learn from). In simple terms, log in to github, visit the Kandan project page, and click the "fork" button to create your own copy of the repo.  You will push your changes to this new repo under your own github account, and we will pull changes into the main repo from there.
<!-- more -->
For the sake of the rest of the examples in this guide, we're going to assume your Github username is "**GITHUB_USERNAME**" and use that in our examples.

Now, we want to grab the latest from this newly created repository and pull it down to your local machine. Getting the latest code from your repo is simple, just clone it:

```bash
git clone git://github.com/GITHUB_USERNAME/kandan.git
cd kandan
```
This will give you a directory called "kandan" on your local machine with the latest checkout from your fork of the main kandan repo. **Note:** this is *not* a direct reference to the main kandan repo. When you make changes in your fork, you'll need to let us know about it so we can pull it over....but that's later in the process.

**2. Add a remote for the main kandan repo**

One thing you'll need to do to make things easier to integrate and keep up to date in your fork is to add the main kandan repo as a remote reference. This way you can fetch the latest code from the production version and integrate it. So, here's how to set that up:

```bash
git remote add upstream https://github.com/kandanapp/kandan.git
git remote   (this will list out your remotes, showing the new one we added)
```

Then, when you need to pull the latest from the main kandan repo, you just fetch and merge the master branch:

```bash
git fetch upstream
git merge upstream/master
```

You can also use *git pull upstream master* if you want it all in one step.

**3. Making a branch for your changes**

When adding features or bug fixes, please create a separate branch for each changeset you want us to pull in, either with the issue number in the branch name or with an indication of what the feature is. To create the branch, do something like this:

```bash
git branch   (lists your current branches)
git branch my_new_code   (makes a new branch called my_new_code)
git checkout my_new_code
```

If you're working on an issue in the Issues list for the main kandan repo, use the naming convention "kandan-[issue-num]" for your branch name to help us keep track of what your patch actually fixes

**4. Push your code and make a pull request**

When you have finished making your changes, you'll need to push up your changes to your fork so we can grab them. With them all committed, push them:

```bash
git push upstream kandan-[issue-num]
```

This pushes everything in that branch up. Then you can go back over to the main kandan github page and issue a pull request from there.  Tell us what you want us to merge and what it does/fixes, and one of us will pick it up.

That lets us know that there's something new from you that needs to be pulled in. We'll review it and get back to you about it if we have any questions. Otherwise, we'll integrate it and let you know when it's in!

### Conclusion
Hope this guide helps you get started in contributing to the kandan project! If you still have questions, don't hesitate to send an email over to admin@kandanapp.com and we'll get back to you.  