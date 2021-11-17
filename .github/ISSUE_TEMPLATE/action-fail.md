---
name: "Action failed"
about: Raised when a GitHub action fails
title: '[Test action failed] {{ date | date('MMMM Do YYYY, h:mm:ss a') }}'
labels: action failed
assignees: ''

---

A scheduled test has failed: {{ date | date('MMMM Do YYYY, h:mm:ss a') }}.
