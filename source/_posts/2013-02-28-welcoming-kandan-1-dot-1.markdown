---
layout: post
title: "Welcoming Kandan 1.1"
date: 2013-02-28 11:01
comments: true
categories: [Open Source, Ruby on Rails, HipChat, Kandan]
---
The Kandan Team is pleased to announce the Official 1.0 release of [Kandan](https://github.com/kandanapp/kandan) an Open Source alternative to HipChat.

What is Kandan? Kandan is a private chat service for your company or team. You can invite colleagues to share ideas and files in a persistent group chat room or rooms.

Unlike HipChat or other alternatives, Kandan is completely Open Source and can be hosted internally or externally by your organization or by a third party.
<!-- more -->

### What's New in 1.1
These are the major changes that are now in 1.1

 * Added an Adminstrative Console. This is very basic at the moment but will allow any admin to set the max number of rooms, set a Kandan installation as public or private, and will perform basic user management. 
 	* {% img /images/kandan_1.1_admin.png %}
 * Room names have been added as unique. An error is now shown if a user tries to create a room with a name that's already in use. 
 	* {% img /images/kandan_1.1_rooms.png %}
 * We've extended the emoticon plugin to support the full [emoji set](http://www.emoji-cheat-sheet.com/) 
 	* {% img /images/kandan_1.1_emojis.png %}
 * Added Desktop notifications. This will work out of the box with Chrome or Safari. If you're using Firefox you will need to install [HTML Desktop Notifications](https://addons.mozilla.org/en-us/firefox/addon/html-notifications/) 
 	* {% img /images/kandan_1.1_notifications.png %}
 * We've added support for @mentions.
 	* {% img /images/kandan_1.1_mentions.png %}	
 * Added plugin suport for [Vimeo](http://vimeo.com) 
 	* {% img /images/kandan_1.1_vimeo.png %}
 * Added & tested [installation instructions](https://github.com/kandanapp/kandan/wiki/Installation#wiki-appfog) for [AppFog](https://www.appfog.com/).

### Get Involved
Since Kandan is a fully open-source app, we would appreciate if you dive in and start adding features, fixing bugs (what bugs?), and cleaning up the code.

To find out how to best contribute please read our [Contributing Guidelines](https://github.com/kandanapp/kandan/blob/master/CONTRIBUTING.md).

For a full list of changes please take a look at the [CHANGELOG](https://github.com/kandanapp/kandan/blob/master/CHANGELOG.md)