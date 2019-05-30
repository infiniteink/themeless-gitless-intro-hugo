---
## Important: If this is a draft, next line should NOT begin with #
# draft: true
title: {{ replace .Name "-" " " | title }}
date: {{ dateFormat "2006-01-02" .Date }}
## below are user-defined parameters (lower case keys recommended)
subtitle:
tags:
  - tag1
  - tag2
---

