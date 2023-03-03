---
title: "{{ replace .Name "-" " " | title }}"
# summary: "文章总结"
# categories: ["Post","Blog",]
tags: ["文章","未分类"]
# externalUrl: ""
# showSummary: true
# date: {{ .Date }}
date: {{ .Date | time.Format "2006-01-02" }}
draft: false
---

