---
title: MD001 - Header levels should only increment by one level at a time
tags:  [headers]
alias: header-increment
---

This rule is triggered when you skip header levels in a markdown document, for
example:

    # Header 1

    ### Header 3

    We skipped out a 2nd level header in this document

When using multiple header levels, nested headers should increase by only one
level at a time:

    # Header 1

    ## Header 2

    ### Header 3

    #### Header 4

    ## Another Header 2

    ### Another Header 3
