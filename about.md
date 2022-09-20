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
{% assign sorted_pieces = site.pieces | sort: 'weight' %}
{% for piece in sorted_pieces limit: limit %}
  - **{{ piece.title }}:** {{ piece.content | markdownify | strip_html | truncatewords: 33 }} [[more]]({{ piece.url | relative_url }})
{% endfor %}

There are [multiple pieces][pieces] that make it all work, not the least of
which is bitcoin and its lightning network that allows the frictionless
automation of micropayments. One of the most important things to understand is
that information is _not_ scarce and thus has to be monetized and thought about
differently. It is a crucial mental switch that is quite difficult to make at
first: the switch from a mindset of scarcity to a mindset of abundance.

[pieces]: {{ '/pieces' | absolute_url }}

> Podcasting really flipped the scarcity-based economy of radio broadcasting on
> its head.
>
> <cite>[Adam Curry](https://youtu.be/8RNsFNyCHL4?t=19964)</cite>

---

[![Adam talking V4V @ BitBlockBoom 2022](/images/bitblockboom.jpg)](https://youtu.be/8RNsFNyCHL4?t=19964)

Watch the talk: [Adam Curry @ BitBlockBoom 2022](https://youtu.be/8RNsFNyCHL4?t=19964)

---

The V4V model provides a solution to the problem of selling information. A
solution that allows you to step away from the attention and surveillance
economy, towards an economy of _value_, openness, and abundance.

> The solution begins with acceptance. Selling digital content in the
> traditional, transactional way doesn't work, or at least doesn't work very
> well. A transaction involving a digital photograph of an apple is very
> different than a transaction involving a physical apple.
>
> <cite>[Gigi D.][busking]</cite>

[busking]: https://dergigi.com/2021/12/30/the-freedom-of-value/#accept-the-nature-of-information

Want to get started? Follow one of the [guides]({{ '/guides' | absolute_url }})!
