---
title: "{{ replace .Name "-" " " | title }}"
description: ""
summary: "" #displayed in post list
tags: ["blakoe"]
author: "Me"
publishDate: {{ .Date }}
lastmod: {{ .Date }}
# weight: 1
# aliases: ["/first"]
# author: ["Me", "You"] # multiple authors

draft: true #STATUS

searchHidden: false #enable to exclude page/post from search results
showToc: false
TocOpen: false

hidemeta: false
comments: false

disableHLJS: true # to disable highlightjs
disableShare: false

hideSummary: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---