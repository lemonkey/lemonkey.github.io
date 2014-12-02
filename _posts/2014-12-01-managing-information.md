---
layout: post
title: Managing Information
author: Ari Braginsky
category: "development"
tags: ""
excerpt: "Over time, managing information related to existing and new technologies can become an overwhelming burden.  Here are some of the tools and techniques that I've used over the years to help keep things sane."
---

As a software developer who has worked in many different environments using various technologies that have come and gone or those which are not yet ready for prime time, staying organized with respect to managing information has been key to my overall career.

The following is a brief list of some of the tools that I use to stay current with various technologies. Feel free to issue a pull request if you would like to add additional tools that you use and I would be glad to add it.

***

## iOS Apps

- iCloud Notes: I've tried many different tools over the years for keeping track of various notes that I take while reading articles, books, attending meetups, WWDC, etc. and the simplicity that the OS X Notes app provides in terms of syncing to all your devices is hard to beat. There are still a few things to watch out for if you plan on editing a note on one Mac and then continuing to edit on another.  Sometimes a duplicate note can be generated before things completely sync. However I never have issues with my notes syncing properly between a Mac and my iOS devices. Notes are ultimately stored in a non-standard binary format as HTML in "~/Library/Containers/com.apple.Notes/Data/Library/Notes/NotesV1.storedata-wal" (write ahead log). You can ultimately [recover lost notes](http://superuser.com/a/464688) by using the strings command line tool "strings ~/Library/Containers/com.apple.Notes/Data/Library/Notes/NotesV1.storedata-wal \| open -f". You can also access all of your notes [via the web](http://www.icloud.com/#notes). Evernote is also a popular tool, but I prefer to keep things under the same secure iCloud account on my devices.

- iBooks: eBooks are a preferred way of consuming up to the minute information as many publishers release electronic versions before the print versions are available. I like to use iBooks to organize various eBooks from Apple or PDFs that I download elsewhere.

- [Instapaper](http://appstore.com/instapaper): If you want to be able to save snippets of text from various blog posts and other sources, this tool allows you to save them in a centralized location, for handy recall later.

## Websites

- [Github Explore](https://github.com/explore): I highly recommend subscribing to Github's daily newsletter that shows what the top trending repositories are (see link at the bottom of the page).  There's no better way to keep your eye on popular frameworks, libraries and other projects that are trending.

- [Feedly](http://feedly.com): Previously I was a big fan of Google Reader, but since that is no more, I've moved on to using this comparable service to track and organize all of my RSS feeds related to various topics. I recommend marking specific blogs as "must read" so that they are included when Feedly compiles a list of the most popular posts for an overall group of RSS feeds.

- [Twitter](http://twitter.com): Once you're following a large number of people on Twitter, organizing them into lists or following lists themselves is a necessary tool to managing your overall Twitter stream.  I maintain an [iOS list](https://twitter.com/lemonkey/lists/ios) that allows me to quickly get the pulse of the top iOS news on Twitter, without all the distractions of the other people that I follow.

- [Google Alerts](http://google.com/alerts): I use Google Alerts to get a summarized listing of certain topics as they are mentioned anywhere that Google crawls.  Due to the random nature of the results, I recommend using this sparingly.

- [GMail](http://gmail.com): GMail is my preferred tool for mail mainly because of the label feature.  By consistently labeling incoming emails, you can help keep your inbox clear and things that need to be dealt with later organized.  You can also filter incoming emails to automatically have a label applied to them as well. Subscribing to mailing lists is another great way to avoid having to follow an individual RSS feed closely as many people do the hard work for you by publishing a weekly digest of the best articles.  Some great ones related to iOS development include [objc.io](http://www.objc.io), [iOS Dev Weekly](https://iosdevweekly.com), and [This Week in Swift](https://swiftnews.curated.co). 

- [Meetup.com](http://meetup.com): Meetups can be a great way to stay on top of new technologies and this site, once you've defined what your key interests are, allows you get email notifications whenever a meetup you're following has an upcoming event as well as when new meetups that match your interests are created. Being able to add the event to your calendar via iCal is also handy and I recommend creating a new calendar just for meetups so that you can share it with other people, whether you use iCloud or Google calendars.
