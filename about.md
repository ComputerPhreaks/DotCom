---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## Under Construction 

You'll notice the site is pretty bare, this is because we are setting up a CI pipeline to allow us to easily update the site and find typos and other silly things, but we also have a responsibility to our clients and so attend to their needs before our own.

This site proudly uses open source tools and leverages providers that allow free use for open source projects in the spirit of sharing information to allow people to improve their lives and be better at their jobs by seeing how things work.

Ethan Spoelstra is the main guy doing DevOps/Infrastructure/Client Support/etc, and he's not much of a creative type, so the site will be a pretty simple setup until he finds time to hire a designer to spruce things up.

</div>
