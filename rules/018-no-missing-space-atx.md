---
title: MD018 - No space after hash on atx style header
tags:  [headers, atx, spaces]
alias: no-missing-space-atx
---

This rule is triggered when spaces are missing after the hash characters
in an atx style header:

    #Header 1

    ##Header 2

To fix this, separate the header text from the hash character by a single
space:

    # Header 1

    ## Header 2

