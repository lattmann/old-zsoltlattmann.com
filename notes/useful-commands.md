---
layout: "default"
title: Useful Commands
note: true
categories: [osx, shell, script]
desc: "A collection of useful commands"
---

[Home page](/)

# Reduce size of PDF

Assumes that `gs` - GhostScript is installed on your machine and available in the path.

```bash
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/ebook -dNOPAUSE -dQUIET -dBATCH -sOutputFile=small.pdf original.pdf
```
