---
title: MD011 - Reversed link syntax
tags:  [links]
alias: no-reversed-links
---

This rule is triggered when text that appears to be a link is encountered, but
where the syntax appears to have been reversed (the `[]` and `()` are
reversed):

    (Incorrect link syntax)[http://www.example.com/]

To fix this, swap the `[]` and `()` around:

    [Correct link syntax](http://www.example.com/)

