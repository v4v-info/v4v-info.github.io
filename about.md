---
title: The V4V Philosophy
layout: page
description: About
bodyClass: page-about
---

Value4Value is more than meets the eye. It's a monetization model, a content
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

Listen to Adam talk V4V on [TFTC RIP #409](https://tftc.io/tftc-podcast/409-discussing-value-4-value-with-the-podfather-adam-curry/):
[![Adam talking V4V on TFTC](/images/409-Adam-Curry.png)](https://youtu.be/meAO2plwnXw)

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

More and more creators are discovering the V4V model for themselves:

> The skill, time, and talent/personality employed to create artistic expressions
> are valuable, and their supply cannot be easily reproduced/replicated even
> though the individual manifestations of them (the works of art) can be. This is,
> ultimately, what creators must figure out how to monetize if they are to make
> their work economically sustainable.
> [...]
> [Nostr][nr] and [Bitcoin][br] give creators of every type of content the opportunity to
> directly own and control the distribution and monetization of their time, skill,
> and talent, more so than any other service or platform on the Internet.
>
> <cite>[corndalorian][corn]</cite>

[busking]: https://dergigi.com/2021/12/30/the-freedom-of-value/#accept-the-nature-of-information
[corn]: https://habla.news/corndalorian/thoughts-on-v4v
[nr]: https://nostr-resources.com/
[br]: https://bitcoin-resources.com/

Want to get started? Follow one of the [guides]({{ '/guides' | absolute_url }})!
