# Open JIRA Issues from Selection 

Version 1
https://github.com/abradner/jira_automator

## Introduction

Use this script when you want to open one or more JIRA issue from issue keys found in a text selection

The script allows you to select text, like "DC2C-14, DC2C-15, DC2C-17 and that other broken one was DC2C-18", and directly open the JIRA issues.

**Important:** This only works on a mac.

## Installation

1.  Download the following zip [https://github.com/abradner/jira_automator/zipball/master]
2.  Unzip the file to ~/Library/Services using a command similar to the following (this should move in a new version and clean up the download):
```
unzip -o ~/Downloads/abradner-jira_automator-*.zip
cp -r ~/Downloads/abradner-jira_automator-*/ ~/Library/Services/
rm -r ~/Downloads/abradner-jira_automator-*/
rm ~/Downloads/abradner-jira_automator-*.zip
```
     

# In use

1.  Highlight a block of text that contains at least JIRA issue key and number you would like to open in JIRA. For example, if you want to open DC2C-49, select and highlight the text that includes the full issue key. Extra text and duplicate issues will be ignored.
2.  Right-click and select "Open JIRA Issue" or "Services > Open JIRA Issues in Selection"

The unique JIRA issues will be open in a new tabs.

## Todo

*   If no issues are selected, just launch JIRA
*   If lots of issues are selected then convert the issue codes to a JIRA search string and only open a single tab to that search.

## Contribution

Please modify this if you want to make it more awesome. Ideally send me pull requests on github and I'll update accordingly

### License
This work by Alex Bradner is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License. (http://creativecommons.org/licenses/by-sa/3.0/)
