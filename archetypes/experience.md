---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
params:
    location: 'Experience Location'
    start: '{{ time.Now | time.Format "Jan 2006" }}'
    end: 'Present'
draft: true
---

Placeholder