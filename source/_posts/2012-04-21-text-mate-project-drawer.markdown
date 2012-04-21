---
layout: post
title: "TextMate and AckMate"
date: 2012-04-21 13:18
comments: true
categories: [productivity, text editors]
---

I really want to learn Vim, but for now I'll stick with TextMate while me learning curves are so steep on all the other Rails competencies.

One very helpful command to bring up text mate with the current project loaded *and* the project drawer open is this: 
```
cd my_rails_project
mate .
```

The "mate" tells the command line to open TextMate and the "." tells it to open to *this* directory. 

Once I have my project drawer open, how do I search within my project (not just within the file I have open)? Edit > Find > Find in Project generates search results that are ridiculously hard to interpret. 
{% img [screen_shot] /images/textmate-find-in-project.png [300] [300] [TextMate] [TextMate search results] %}

Enter Ackmate. 

AckMate is a TextMate plugin for running Ack in a Cocoa window. It runs on Mac OS X 10.5 and above. Ackmate can be downloaded on [GitHub](https://github.com/protocool/AckMate/downloads). If you like it and use it, donate!

Ackmate lets me search in my project and see the results in a lovely and easy-to-understand way. Mate dot into your project and hit Ctrl + Option + Splat + F and give it a try!

{% img [screen_shot] /images/ackmate.png [300] [300] [AckMate] [AckMates lovely search results] %}

