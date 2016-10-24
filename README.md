# JIRA tamper

A few simple [Tampermonkey](https://tampermonkey.net/) userscripts to tweak [JIRA](https://www.atlassian.com/software/jira) display and operation. They install in any good browser, but you'll get the best experience by:

1. Installing [Tampermonkey](https://tampermonkey.net/) to manage userscripts
2. Then just browse to a raw *.user.js file like [jira-lo-res-reports.user.js](https://raw.githubusercontent.com/m-rk/jira-tamper/master/jira-lo-res-reports.user.js)

## [GWT](https://github.com/m-rk/jira-tamper/blob/master/jira-gwt.user.js)

JIRA has limited options for formatting text and inserting symbols in issue content. This userscript provides auto-formatting for given-when-then (GWT) text in JIRA issue pages (description and comments):

- **stylised arrows**: the "->" arrows used in shorthand "given -> when -> then" sentences are stylised (replaced with "→" character, coloured and padded)

## [Lo-Res](https://github.com/m-rk/jira-tamper/blob/master/jira-lo-res-reports.user.js)

Thicker lines for JIRA reports (burndown, burnup, etc.) for nicer display at lower resolutions (e.g. screencaps).
