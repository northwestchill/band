+++
title = 'Events'
slug = 'events'
image = 'images/bg.jpg'
description = 'Donec eget ex magna. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque venenatis dolor imperdiet dolor mattis sagittis magna etiam.'
disableComments = true
+++

{{ range .Site.RegularPages.ByDate.Reverse }}
  {{ if eq .Section "post" }}
    * [{{ .Title }}]({{ .Permalink }}) - {{ .Date.Format "January 2, 2006" }}
  {{ end }}
{{ end }}
