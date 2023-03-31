---
title: "NWC at Beer Vault Gig Harbor"
date: 2023-03-30T14:59:56-07:00
images: /static/images/nwcbandpic.jpg
resources:
    - src: /static/images/nwcbandpic.jpg
      title: "A band picture"
draft: false
---

{{ $image := .Resources.GetMatch "/static/images/nwcbandpic.jpg" }}
<img src="{{ $image.RelPermalink }}" width="{{ $image.Width }}" height="{{ $image.Height }}">