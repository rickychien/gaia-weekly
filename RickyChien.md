## 09/21 ~ 09/25
[Build]
* [Bug 1211400](http://bugzil.la/1211400) - [TV][2.5] Preview an app on Marketplace
 * WIP patch has submitted, survey preview logic including install, uninstall and child window
* [Bug 1146713](http://bugzil.la/1146713) - [emulator] mach mochitest-remote fails: expected to find ssltunnel at .../gaia/b2g_sdk/39.0a1-2015-03-05-16-02-02/b2g/ssltunnel
 * Fixed. Find out problem in mochitest and let mochitest download mochitest by itself.
 * Follow-up clean work for correct mozinstall path, remove unused build log and file another bug for support latest b2g_sdk [Bug 1215437](http://bugzil.la/1215437)
* [Bug 1205257](http://bugzil.la/1205257) - Spark distro does not rebuild fine
 * Fixed. This is a spark build regression but it merely appear when triggering by ./build.sh
* Clean up review and needinfo queues

## 2015 Q4 Goals
1. Support TV 2.5 feature - Provide an ability to preview an app on Marketplace [[TV][2.5] Preview an app on Marketplace](https://bugzilla.mozilla.org/show_bug.cgi?id=1211400), as measured by implementation (completeness and stability of the feature)
2. To lift the restrictions for gaia developers to use third-party NPM packages, we'll continue the plan of [refactoring build system run-time to node.js](https://wiki.mozilla.org/Gaia/Build/RefactoringToNodejs), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
3. CI machines are able to run / switch multi-version node.js in order to support new gaia build (node.js v4.x) and testing framework (node.js v0.10.x), as measured by implementation progress. (This is a long term plan so this goal does not aim for shipping on this quarter.)
4. Investigate new Gaia build 2.0 - confidant with Gareth, as measured by planning progress.
5. Fix bugs of build system, as measured by blocker burn down and days of blocker turnarounds.

## 2015 Q3 Delivered
1. Investigated new configure of Gaia build 2.0 - confidant
2. Surveyed and do experiment for new Gaia build 2.0 - gaia-playground
3. Fixed bugs of build system
4. Fixed bugs of settings app and system app
5. Supported Academy NCU 2015 Program - Introduced Git, Github, Bugzilla, WebIDE and DevTools
