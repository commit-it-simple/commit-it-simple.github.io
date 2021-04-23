---
layout: page
nav-order: 5
---

## Automation

### Changelogs

You've done the hard work, now reap the rewards! Why manually make a changelog for your users with each version update, when a script can do it for you?

Some automatic changelog creators are linked below:

* [Whathappened](https://github.com/Rollcloud/whathappened)
* [Auto Changelog](https://github.com/Michael-F-Bryan/auto-changelog)

An example of what is possible from the [Whathappened](https://github.com/Rollcloud/whathappened) changelog:

	## v0.2.0 (2020-10-18)
	
	### Docs
	
	* Changelog - update for v0.2.0
	* Readme - add command-line indicator to installation instructions
	* Readme - add commit message examples
	* Readme - add more details about message types
	* Readme - link badges to sensible destinations
	
	### Features
	
	* Add command line script
	* Detect and handle breaking changes
	* Group commits by version [BREAKING]
	* Group commits in each version by type
	
	### Fixes
	
	* Add appropriate capitalisation to changelog items
	* Only display user-relevant commits types in the changelog
	* Remove extra line at end of changelog

### Reviews

Commit messages can be easily reviewed using an automatic changelog. This helps to prevent the situation below from occurring - resulting in better quality code.

[![Uninformative commit messages](https://imgs.xkcd.com/comics/git_commit.png "Merge branch 'asdfasjkfdlas/alkdjf' into sdkjfls-final")](https://xkcd.com/1296/)
