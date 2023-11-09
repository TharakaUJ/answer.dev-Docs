---
title: "API Request"
layout: home
nav_order: 2
permalink: /apireq
---

{% include table-content %}

# How to use the API

## Parameters

### Headers
These are the additional headers you should specify for these api requests.

1. X-Berserker-Token
- value: Your authentication token. Tokens can be found [here](https://answr.dev/token).
2. Content-Type
- value: application/json

### Body
1. Json dictionary containing the domain.
- key: "url"
- value: "domain-url"
- example:-
> {"url": "google.com"}

## Examples

### Curl command
<pre>curl --location 'https://api.answr.dev/ahrefs/' \
--header 'X-Berserker-Token: effec3ab-cf33-48ac-974b-297ac946d244' \
--header 'Content-Type: application/json' \
--data '{
    "url":"firebase.google.com"
}'</pre>

### Postman
1. Headers

![Postman Headers](/../_images/postman-headers.png "postman-headers")
 **Note:** Notice that some headers are just the default headers.
 - X-Berserker-Token
 - Content-Type 

 are headers that assigned specifically.



2. Body

![Postman Body](/../_images/postman-body.png "postman-body")
