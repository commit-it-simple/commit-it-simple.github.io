---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Home
nav-order: 0
---

## Summary

All commit messages should be of the general style:
    
    <type>: <description>

Where `<type>` is one of `fix`, `feat`, `build`, `ci`, `docs`, `style`, `refactor`, `perf`, or `test` and `<description>` is a plain-text message.

## Introduction

Wax lyrically to the point.

## Inspired by

* [SemVer](https://semver.org/)
* [Angular Commit Message Format](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit)
* [Auto Changelog](https://github.com/Michael-F-Bryan/auto-changelog)
* [git_commits.py](https://gist.github.com/simonw/091b765a071d1558464371042db3b959#file-get_commits-py)

## Whathappened Commit Message Format

Whathappened expects git commit messages in the format outlined below:

    [optional breaking ]<type>[ optional (<scope>)]: <description>

    [optional body]

`<type>` is recommended to be one of:

    fix
    feat
    build
    ci
    docs
    style
    refactor
    perf
    test

Variations on these types like `feat, feature, features`, or `doc, docs` are seamlessly grouped together.

`<scope>` is recommended to be a module, file, or folder name as appropiate.

For a nice summary of `type`s and what they mean, please see [Understanding Semantic Commit Messages Using Git and Angular](https://nitayneeman.com/posts/understanding-semantic-commit-messages-using-git-and-angular/).

## Emoji

Adding the --emoji flag will add emoji after each heading in the changelog. Below is the list of emoji that are used:

* Docs 📝
* Features ✨
* Fixes 🐛
* Performance ⚡️
* Refactorings ♻️
* Other 🃏
