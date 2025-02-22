+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'

[params]
  author = '{{ .Site.Params.author }}'
+++

Article content.
