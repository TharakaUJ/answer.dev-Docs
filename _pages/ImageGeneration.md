---
title: "Image Generation"
layout: default
parent: API usecases
permalink: /image-generation/
---

{% include table-content %}

# Using API to generate images
Send a POST request to, **https://api.midj.app/api/generate** with your API token for the Authorization key in the header. In the body specify your prompt in json format.

### Using the API with "postman"
Create a POST request to **https://api.midj.app/api/generate**.
In the request header specify the Authorization key with the value of your API token.
![header>Autharization](/../_images/postman-header.png "Postman")


Then in the body of the request, select raw body and json file format. Then specify your prompt as below and send the request.
![prompt](/../_images/post-body-prompt.png "request body")

Then you will recieve a success message with trigger Id as below.
![success message](/../_images/success message-image generation.png "success message")


Then head over to your webhook service and wait until image results back. You can visit the generated images via the url link in the request.

![image generated](/../_images/generated immages step 1.png "image generated")

You also can select the prefered image among the given images and [upscale](/upscaling/).


## fast generation