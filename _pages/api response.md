---
title: "API Response"
layout: home
nav_order: 3
permalink: /apires
---

{% include table-content %}

## Api Response

### content type

The response return a json dictionary.

### Sample out put
<code>
{"data":{"data":{"data":{"domainRating":91.0,"urlRating":48,"backlinks":5344372,"refdomains":71548,"dofollowBacklinks":93,"dofollowRefdomains":93},"signedInput":{"input":{"url":"firebase.google.com/","mode":"subdomains","validUntil":"2023-11-09T23:45:46Z"},"signature":"4954f08ada0d1d084055fb0e8c9699b861f247aea6797270bb4b790566bab62d"}},"list_res":["TopBacklinks",{"topBacklinks":{"backlinks":[{"anchor":"Firebase","domainRating":92,"edu":false,"gov":false,"httpCode":200,"redirectChain":[],"text":true,"textPost":"","textPre":"","title":"Download Android Studio & App Tools - Android Developers",
...
"urlToChainDestinationChanged":false,"urlToDelReasonTitle":"None","urlToDelReasonKey":"None","urlToHasDelReason":false,"lost_redirect_reason":"","del_reason":"","lost_redirect_source":"","lost_redirect_new_target":"","isLost":true}],"total":100}}]}}
</code>