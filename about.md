---
title: The V4V Philosophy
layout: page
description: About
bodyClass: page-about
---

Value-for-value is more than meets the eye. It's a monetization model, a content
format, and a way of life. It is about freedom and openness, connection and free
speech, sound money and censorship resistance.

{% assign limit = 3 %}
{% for piece in site.pieces limit: limit %}
  - **{{ piece.title }}:** {{ piece.content | markdownify | strip_html | truncatewords: 33 }} [[more]]({{ piece.url | relative_url }})
{% endfor %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin ac nibh ultrices,
volutpat turpis id, volutpat purus. Nulla facilisi. Etiam lobortis urna aliquet
nibh dapibus hendrerit. Vivamus vel hendrerit neque. Aliquam fringilla odio eget
sapien aliquet pharetra. Suspendisse rutrum metus justo, volutpat bibendum nisl
auctor efficitur. Fusce cursus, dolor et dignissim euismod, eros enim vestibulum
lectus, euismod tincidunt ipsum arcu sed quam. Etiam in nunc eget lectus rhoncus
dignissim ac vel nibh. Maecenas leo erat, tincidunt a velit at, faucibus
malesuada quam. Curabitur quis interdum est. Vivamus sollicitudin justo eget
eleifend placerat. Nunc sagittis ipsum libero, et aliquet elit imperdiet id.

> Podcasting really flipped the scarcity-based economy of radio broadcasting on
> its head.
>
> <cite>Adam Curry</cite>

[![Adam talking V4V @ BitBlockBoom 2022](/images/bitblockboom.jpg)](https://youtu.be/8RNsFNyCHL4?t=19964)

Watch the talk: [Adam Curry @ BitBlockBoom 2022](https://youtu.be/8RNsFNyCHL4?t=19964)

Get started with Podcasting 2.0: [value4value.io](http://value4value.io)
