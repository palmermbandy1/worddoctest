# worddoctest

**Overview**

This repo is to test using a DVCS like Git to track changes in Word documents.
Distributed version control can have especially useful applications for
important text documents that are shared between multiple parties. Even
individuals who do not share documents but want to keep a detailed history of
changes they make (e.g., for grad students writing a thesis/dissertation) can
benefit from DVCS.

**Setup**

Install [Pandoc](https://pandoc.org/) and add the following to your git
configuration settings:

```
diff.pandoc.textconv=pandoc --to=markdown
diff.pandoc.prompt=false
merge.tool=opendiff
alias.wdiff=diff --word-diff=color --unified=1
```
**Steps**

''
