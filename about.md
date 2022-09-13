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

There are [multiple pieces][pieces] that make it all work, not the least of
which is bitcoin and its lightning network that allows the frictionless
automation of micropayments.

[pieces]: {{ '/pieces' | absolute_url }}

> Podcasting really flipped the scarcity-based economy of radio broadcasting on
> its head.
>
> <cite>Adam Curry</cite>

[![Adam talking V4V @ BitBlockBoom 2022](/images/bitblockboom.jpg)](https://youtu.be/8RNsFNyCHL4?t=19964)

Watch the talk: [Adam Curry @ BitBlockBoom 2022](https://youtu.be/8RNsFNyCHL4?t=19964)

Want to get started? Follow one of the [guides]({{ '/guides' | absolute_url }})!
