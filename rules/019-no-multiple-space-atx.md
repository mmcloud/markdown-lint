---
title: MD019 - Multiple spaces after hash on atx style header
tags:  [headers, atx, spaces]
alias: no-multiple-space-atx
---

This rule is triggered when more than one space is used to separate the
header text from the hash characters in an atx style header:

    #  Header 1

    ##  Header 2

To fix this, separate the header text from the hash character by a single
space:

    # Header 1

    ## Header 2

