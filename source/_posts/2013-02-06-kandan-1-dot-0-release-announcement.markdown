---
layout: post
title: "Kandan 1.0 Release Announcement"
date: 2013-02-06 20:51
comments: true
categories: [Open Source, Ruby on Rails, HipChat, Kandan]
author: Tony Guntharp
---

### Announcement

The Kandan Team is pleased to announce the Official 1.0 release of [Kandan](https://github.com/kandanapp/kandan) an Open Source alternative to HipChat.

What is Kandan? Kandan is a private chat service for your company or team. You can invite colleagues to share ideas and files in a persistent group chat room or rooms.

Unlike HipChat or other alternatives, Kandan is completely Open Source and can be hosted internally or externally by your organization or by a third party.
<!-- more -->
### Features
These are features that work out of the box on any provider:

 * Easy deploy to CloudFoundry, Heroku, dotCloud, etc.
 * Collaborative team chat
 * Unlimited channels
 * Embed formats for images and youtube videos with requests for others (twitter, facebook, g+, etc.)
 * Synchronized sound player - play any audio-tag compatible url for the whole channel (Pending :P)
 * /me command!
 * Highly extensible plugin format

### Get Involved
Since Kandan is a fully open-source app, we would appreciate if you dive in and start adding features, fixing bugs (what bugs?), and cleaning up the code.

But before you jump right in there there are a few caveats. 

If you're going to contribute code then you're going to have to sign our [Contributor License Agreement](http://www.clahub.com/agreements/kandanapp/kandan) (hereafter referred to as CLA) which is modeled after the one that [NodeJS](http://nodejs.org) uses.

A CLA is a legal document in which you state you are entitled to contribute the code/documentation/translation to the project you’re contributing to and are willing to have it used in distributions and derivative works. This means that should there be any kind of legal issue in the future as to the origins and ownership of any particular piece of code, then that project has the necessary forms on file from the contributor(s) saying they were permitted to make this contribution.

The CLA also ensures that once you have provided a contribution, you cannot try to withdraw permission for its use at a later date. People and companies can therefore use that software, confident that they will not be asked to stop using pieces of the code at a later date.

You will also really want to take heart and read these two blog posts.

* [How to Contribute Code](http://kandanapp.com/blog/2013/02/05/how-to-contribute-code/)
* [How to Contribute Issues](http://kandanapp.com/blog/2013/02/05/how-to-contribute-issues/)

Make sure you check out these resources as well.

* GitHub [Issues Tracker](https://github.com/kandanapp/kandan/issues)
* Twitter [@kandanapp](https://twitter.com/kandanapp)
* [Kandan Demo](http://kandan-demo.kandanapp.com/) (Yes we eat our own DogFood)

And here is the CHANGELOG for the 1.0 release.

*** 

### CHANGELOG

#### [v1.0]
 * [38f4875](http://github.com/kandanapp/kandan/commit/38f4875) Create CONTRIBUTING.md __(Tony Guntharp)__
 * [605c237](http://github.com/kandanapp/kandan/commit/605c237) Update README.md __(Tony Guntharp)__
 * [c42c82b](http://github.com/kandanapp/kandan/commit/c42c82b) Update README.md __(Tony Guntharp)__
 * [6c025a8](http://github.com/kandanapp/kandan/commit/6c025a8) Update README.md __(Tony Guntharp)__
 * [f5be2b4](http://github.com/kandanapp/kandan/commit/f5be2b4) Update README.md __(Tony Guntharp)__
 * [fadff2d](http://github.com/kandanapp/kandan/commit/fadff2d) Merge pull request #43 from fusion94/master __(James Gifford)__
 * [0646509](http://github.com/kandanapp/kandan/commit/0646509) Correctly set channel and user in bootstrapped messages thanks to @madx Fixes #32 __(Tony Guntharp)__
 * [46207f4](http://github.com/kandanapp/kandan/commit/46207f4) Merge pull request #41 from fusion94/master __(James Gifford)__
 * [809cf7b](http://github.com/kandanapp/kandan/commit/809cf7b) biggish commit on style. Fixes #13 #34 #36 #37 __(Tony Guntharp)__
 * [22a0816](http://github.com/kandanapp/kandan/commit/22a0816) Merge pull request #33 from kandanapp/update-paperclip __(Tony Guntharp)__
 * [75c4666](http://github.com/kandanapp/kandan/commit/75c4666) Updating paperclip, stage uno __(James Gifford)__
 * [8d4a9dd](http://github.com/kandanapp/kandan/commit/8d4a9dd) Merge pull request #30 from fusion94/master __(James Gifford)__
 * [a39ddbc](http://github.com/kandanapp/kandan/commit/a39ddbc) Moving from displaying email to displaying usernames, username is now required to register. Fixes #2 __(Tony Guntharp)__
 * [ae3f5a3](http://github.com/kandanapp/kandan/commit/ae3f5a3) Merge pull request #28 from amanelis/coverage __(Tony Guntharp)__
 * [40d3df8](http://github.com/kandanapp/kandan/commit/40d3df8) Added simplecov to spec helper __(Alex Manelis)__
 * [c74d2ed](http://github.com/kandanapp/kandan/commit/c74d2ed) Added coverage/ dir to gitignore __(Alex Manelis)__
 * [dcb131f](http://github.com/kandanapp/kandan/commit/dcb131f) Added simplecov to Gemfile __(Alex Manelis)__
 * [c6b9651](http://github.com/kandanapp/kandan/commit/c6b9651) Update README.md __(Tony Guntharp)__
 * [9bf68fa](http://github.com/kandanapp/kandan/commit/9bf68fa) Merge pull request #27 from jrgifford/upgrade-sass __(Tony Guntharp)__
 * [626cc2e](http://github.com/kandanapp/kandan/commit/626cc2e) updated to sass 3.2.5 __(James Gifford)__
 * [f762ba4](http://github.com/kandanapp/kandan/commit/f762ba4) Merge pull request #14 from jrgifford/local-installs __(Tony Guntharp)__
 * [69bed6a](http://github.com/kandanapp/kandan/commit/69bed6a) Fixes #8 __(James Gifford)__
 * [0c3e253](http://github.com/kandanapp/kandan/commit/0c3e253) added not pushing public/system/* to .gitignore. also set default channel to be named lobby. fixed #9 __(Tony Guntharp)__
 * [d112c8b](http://github.com/kandanapp/kandan/commit/d112c8b) Modified two things:   - travis.yml   - gemfile.lock to remove the dependency on git-based jasmine __(James Gifford)__
 * [4d770f5](http://github.com/kandanapp/kandan/commit/4d770f5) Merge pull request #5 from amanelis/spec-updates __(James Gifford)__
 * [253a030](http://github.com/kandanapp/kandan/commit/253a030) Fixes issue #6 __(Tony Guntharp)__
 * [350dde9](http://github.com/kandanapp/kandan/commit/350dde9) Merge remote branch kandan/master __(Alex Manelis)__
 * [7965928](http://github.com/kandanapp/kandan/commit/7965928) ci-skip added build status to readme __(James Gifford)__
 * [50e0e38](http://github.com/kandanapp/kandan/commit/50e0e38) Added travis.yml. __(James Gifford)__
 * [bf80a5e](http://github.com/kandanapp/kandan/commit/bf80a5e) correcting typo on a URL in README __(Tony Guntharp)__
 * [b453b72](http://github.com/kandanapp/kandan/commit/b453b72) adding links to UPDATE section of README __(Tony Guntharp)__
 * [f529046](http://github.com/kandanapp/kandan/commit/f529046) added an UPDATE section of the README __(Tony Guntharp)__
 * [291884a](http://github.com/kandanapp/kandan/commit/291884a) updating links in README __(Tony Guntharp)__
 * [3c47fcb](http://github.com/kandanapp/kandan/commit/3c47fcb) oops a typo __(Tony Guntharp)__
 * [dcb016e](http://github.com/kandanapp/kandan/commit/dcb016e) potential width fix __(Tony Guntharp)__
 * [840525f](http://github.com/kandanapp/kandan/commit/840525f) width issues __(Tony Guntharp)__
 * [d3131dd](http://github.com/kandanapp/kandan/commit/d3131dd) resolving file attachment issues __(Tony Guntharp)__
 * [628138f](http://github.com/kandanapp/kandan/commit/628138f) Removed rails default images, all tests pass :green_heart: __(Alex Manelis)__
 * [2ad13e5](http://github.com/kandanapp/kandan/commit/2ad13e5) Changed up when not authenticated __(Alex Manelis)__
 * [5409535](http://github.com/kandanapp/kandan/commit/5409535) Re wrote a few expects in model specs __(Alex Manelis)__
 * [827cde1](http://github.com/kandanapp/kandan/commit/827cde1) Changed up the before blocks, calling methods to many times __(Alex Manelis)__
 * [6c790fa](http://github.com/kandanapp/kandan/commit/6c790fa) Added faker gem for a few testing purposes __(Alex Manelis)__
 * [c712a4f](http://github.com/kandanapp/kandan/commit/c712a4f) Line for intialize on precompile found twice :trollface: __(Alex Manelis)__
 * [6e6ec3b](http://github.com/kandanapp/kandan/commit/6e6ec3b) Don't need to require factory_girl __(Alex Manelis)__
 * [89a59fa](http://github.com/kandanapp/kandan/commit/89a59fa) Added db cleaner to spec config __(Alex Manelis)__
 * [987a39a](http://github.com/kandanapp/kandan/commit/987a39a) Added db cleaner and a few other handy development gems __(Alex Manelis)__
 * [452962e](http://github.com/kandanapp/kandan/commit/452962e) Whitespace __(Alex Manelis)__
 * [a8a9442](http://github.com/kandanapp/kandan/commit/a8a9442) Slight modification to how the api controller spec is structured __(Alex Manelis)__
 * [4d81157](http://github.com/kandanapp/kandan/commit/4d81157) Removed rack-mini-profiler, decided wasn't worthy right now __(Alex Manelis)__
 * [46fa134](http://github.com/kandanapp/kandan/commit/46fa134) More factory girl updates to deprication __(Alex Manelis)__
 * [c572837](http://github.com/kandanapp/kandan/commit/c572837) Updated factory deprication for next __(Alex Manelis)__
 * [c94a8ee](http://github.com/kandanapp/kandan/commit/c94a8ee) Added some better gems for development __(Alex Manelis)__
 * [bc8e10d](http://github.com/kandanapp/kandan/commit/bc8e10d) Was already using sqlite locally :trollface: __(Alex Manelis)__
 * [84ea429](http://github.com/kandanapp/kandan/commit/84ea429) Added rvmrc to the gitignore file __(Alex Manelis)__
 * [000ea1f](http://github.com/kandanapp/kandan/commit/000ea1f) Merge pull request #36 from bielefeldt/master __(Sean Grove)__
 * [dead52c](http://github.com/kandanapp/kandan/commit/dead52c) README change with Heroku S3 integrations __(response)__
 * [baa502c](http://github.com/kandanapp/kandan/commit/baa502c) Update Readme __(Kev Zettler)__
 * [ba2c630](http://github.com/kandanapp/kandan/commit/ba2c630) Removed Cloudfuji references from readme __(Kev Zettler)__
 * [5b8bb9b](http://github.com/kandanapp/kandan/commit/5b8bb9b) Merge pull request #34 from jrgifford/master __(Kev Zettler)__
 * [5606ea4](http://github.com/kandanapp/kandan/commit/5606ea4) :heart: Guard, fixed specs to work with latest factory girl. __(James Gifford)__
 * [6978925](http://github.com/kandanapp/kandan/commit/6978925) Merge pull request #33 from jrgifford/master __(Kev Zettler)__
 * [a1fd6f9](http://github.com/kandanapp/kandan/commit/a1fd6f9) Updated rails to avoid ActionPack vuls. __(James Gifford)__

