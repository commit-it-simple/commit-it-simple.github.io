---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: Home
nav-order: 0
---

## Summary

All commit messages should be of the general style:
    
    <type>: <description>

`<type>`: one of `fix`, `feat`, `build`, `ci`, `docs`, `style`, `refactor`, `perf`, or `test`  
`<description>`: a plain-text message.

## Introduction

Git commit messages, like the comments that we _should_ be adding to our code, are means of putting the abstract and conceptual into easily relatable words. A good commit log can be the difference between the success or failure of understanding your own intentions six-months ago, understanding someone else's intentions a year ago, or a hot-fix to production code at an inconvenient hour of the night.

A light-weight structure to write commit messages around is a simple tool that can add great clarity to the thoughts and intentions of a software programmer.

Git-Conga is designed first to be **helpful**, secondly **simple**, and thirdly **beautiful**. In that order.

Adopting new concepts, techniques, or tools come at an investment cost. If the result is not benefitial, the change-over isn't worth it. Computers and the software that run on them is as inherently complex as the humans that design and use them. Programmers need tools to make life simpler - this should be one of them. Software engineering is a creative endevour at its heart and - like a beautifully created artwork - should bring joy to its beholder. 

## Specification

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

Git-Conga messages SHALL be written in the format below:

    [OPTIONAL breaking ]<type>[ OPTIONAL (<scope>)]: <description>

    [OPTIONAL body]

### Breaking

Life is hard, changes can be tough, sometimes to move forward one must break with the past. This has can have negative consequences but these can be greatly reduced if you know what the consequences are and how to work around them.

If you've made a change that breaks an external piece of code, a physical resource, or a human-machine interaction, flag it with the keyword `breaking` so that others are aware of the change. Make sure to adequately document the alteration in the `<description>` and provide advice on other systems can adapt to the breaking change.

### Type

The `<type>` describes the nature of the commit, and is one of the two compulsory parameters.
It is RECOMMENDED to be one of:

* `build`
* `ci`
* `docs`
* `feat`
* `fix`
* `perf`
* `refactor`
* `style`
* `test`

Other types may be used instead, particularly for projects that are not of a programming nature, eg: books, documents, Latex reports, system-definitions, use-your-imagination. What is suggested, is that the list of types cover a wide range of functional aspects of the project and are limited to a maximum of ten for appropiate re-useability within a project.

Creators of tools based on Git-Conga SHOULD take the fallibility of humans into account. As such, variations on the spellings of types like `feat`, `feature`, and `features`, or `doc`, and `docs` SHOULD be treated as being equal. Be slow to anger and quick to forgive.

For a good summary of what the types above mean, please see [Understanding Semantic Commit Messages Using Git and Angular](https://nitayneeman.com/posts/understanding-semantic-commit-messages-using-git-and-angular/).

### Scope

Denoting the `<scope>` of a change is OPTIONAL, but can be a useful method of grouping commits that alter a common piece of code. A module, file, or folder name is often appropiate.

### Description

A one-liner that provides a brief overview of the change that has been made. Keep it short and to the point. Start the `<description>` by using a doing-word. See what I did there? Like that.

### Body

This is the body of the commit message and where all the important details live. Remember, _what_ you've changed is already part of the commit, what other developers (and future you) need to know is _why_ you made the change, or made the change in the way you did.

### Capitalisation

Capitalisation can be a tricky, but many might find it helpful to stick to lowercase. The important part is to keep it consistent within a repositiory. Remember: helpful, simple, beautify.

## Examples

_To be added._

## Inspired by

* [SemVer](https://semver.org/)
* [Angular Commit Message Format](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit)
* [Auto Changelog](https://github.com/Michael-F-Bryan/auto-changelog)
* [Understanding Semantic Commit Messages Using Git and Angular](https://nitayneeman.com/posts/understanding-semantic-commit-messages-using-git-and-angular/)
* [git_commits.py](https://gist.github.com/simonw/091b765a071d1558464371042db3b959#file-get_commits-py)
<!-- * [Commit Message Emoji](https://github.com/dannyfritz/commit-message-emoji) -->


<!-- ## Emoji

Adding the --emoji flag will add emoji after each heading in the changelog. Below is the list of emoji that are used:

* Docs 📝
* Features ✨
* Fixes 🐛
* Performance ⚡️
* Refactorings ♻️
* Other 🃏 -->
