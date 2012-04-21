---
layout: post
title: "Monday Chores"
date: 2012-04-20 17:13
comments: true
categories: [persistence, brew, maintenance, upgrading]
---
This past Monday, when pairing with [Ivan](http://ivanoats.com), I learned that I should get into the habit of doing my chores on a particular day. How about Monday?

There is nothing worse than slogging through upgrade hell, so why not stay up to date, working through problems as they arise?

Every Monday, I pledge to do the following:

First, Brew Chores (system wide).


Get the latest version of brew.
```
brew update
```

Next, tell brew to find out what is outdated on my system.
```
brew outdated
```

Finally, tell brew to upgrade what's outdated.
```
brew upgrade
```


Once my system is up to date, then I update my apps.
Go into my app
```
bundle update
```

Tell git to tell me of any major version changes
```
git diff
```

Now, go read the release notes of the major version changes and make sure I really want the new versions. If I do, 
```
bundle install
```

Very lastly, run rake to ensure all my tests pass
```
Rake
```