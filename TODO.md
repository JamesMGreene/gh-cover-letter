# GitHub To-Do List

## Repos
 - Allow users to choose which branch is auto-hosted, i.e. don't restrict it to just "gh-pages".
 - Improve branch visualization, e.g. consider [**@ariya**][ariya/gh]'s
   [comments](http://ariya.ofilabs.com/2012/09/git-viewer-github-vs-google-code.html)
 - 


## Pull Requests
 - ?


## Issues
 - Add some sort of voting system (e.g. stars). However, it is my understanding that this feature used to be available
   and was removed. If that is indeed the case, then I'd love to learn more about why the feature was removed.
 - Add a special file (e.g. "NEW-ISSUE.md") that would suggest questions that are pertinent and should be addressed
   when filing a new issue, or provide the default text for the actual textbox when filing a new issue (like Google
   Code does). For example, for [ZeroClipboard](https://github.com/jonrohan/ZeroClipboard), I frequently reply to
   new issues by [asking which version of Flash the users have installed](https://github.com/jonrohan/ZeroClipboard/issues/85#issuecomment-12543512).
   The "CONTRIBUTING.md" file that we have today is nice but, IMHO, better suited for code/PR contributors rather than
   issue submitters.
 - Add some custom views for the issues list, e.g. Google Code's grid view [serves as a quick Kanban board substitute][ariya/blog-post]
 - Add issue relationships other than the plain ole "reference", such as a blocking relationship (i.e. "Issue #2 is
   blocked on Issue #1"). While I actually generally _disagree_ with [**@ariya**][ariya/gh]'s [example of using such
   a relationship as an umbrella issue][ariya/blog-post] &mdash; that's a great place to utilize milestones, IMHO
   &mdash; I do agree with him that supporting issue relationships does provide value, _especially_ the blocking relationship.


## Milestones
 - ?


## Activity Log/Charts
 - ?


## Gists
 - Allow users to name their Gists. The names don't necessarily need to be restricted to unique names as Gists
   already have unique numerical IDs; rather, the names would just to empower users to not be at the whim of
   the alphabetical order of the filename(s) in their Gist.
 - Gists are very easy add to HTML pages using the GitHub-provided script tags, e.g.:
      `<script src="https://gist.github.com/JamesMGreene/4371789.js"></script>`  
   However, I think we could make it even easier to embed Gists wherever GFM is supported with some custom syntax, e.g.:
      `[gist:JamesMGreene/4371789]`  
   To make the feature easier to use, we could also provide auto-complete help as they type (much like users get
   today when referencing issues by an ID number) &mdash; which would be even easier if users were allowed to name
   their Gists (see previous bullet).
 - _Bug fix:_ currently, [GitHub emojis](http://www.emoji-cheat-sheet.com/) don't work on Gists.


## Increasing Popularity
 - We can help more projects migrate to GitHub by providing more streamlined import processes.
   For example, I migrated the Issue Tracker for the [PhantomJS](https://github.com/ariya/phantomjs) project
   from [Google Code](http://code.google.com/p/phantomjs/issues/list) to [GitHub](https://github.com/JamesMGreene/phantomjs-issues)
   by using [**@technoweenie**](https://github.com/technoweenie)'s
   [GitHub-internal import process](https://gist.github.com/7f75ced1fa7576412901/006a7c69f57521e026be85937c9641e861e81802)
   coupled with some Node.js modules of my own \([gc2gh-issue-migrator](https://github.com/JamesMGreene/gc2gh-issue-migrator)
   and [gcph-client](https://github.com/JamesMGreene/node-gcph-client)\) to make the process even easier.
   
   With regard to migrating from Google Code in particular, their [public Issue Tracker API](http://code.google.com/p/support/wiki/IssueTrackerAPI)
   will be [shutdown on June 14, 2013](http://googleblog.blogspot.com/2012/12/winter-cleaning.html), so time is
   of the essence if we want to capitalize and migrate more projects from there.


[ariya/gh]: https://github.com/ariya
[ariya/blog-post]: http://ariya.ofilabs.com/2012/11/issue-tracker-github-vs-google-code.html
