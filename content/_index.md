---
title: "Rules"
date: 2022-11-10T10:33:21-05:00
draft: false
---

{{ range $.Site.Data.jazz.bass }}
   {{ partial "artist.html" . }}
{{ end }}