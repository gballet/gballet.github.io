---
layout: home
---

I'm a software engineer building a decentralized world. I want to make life simpler and fairer.

I currently work on [Go-ethereum](https://github.com/ethereum/go-ethereum). I focus on bridging research and development. I made the first prototype of the merge, and I am now spending most of my time working on [verkle trees](https://verkle.info).

My favorite languages are Assembly, Zig and Ruby. I use [FreeBSD](https://freebsd.org) and [helix](https://helix-editor.com). Other than that, I love improv comedy, space and discussing weird ideas.

**Articles**

{% for article in site.articles %}
 * [{{article.title}}]({{ article.eurl }})
{% endfor %}
