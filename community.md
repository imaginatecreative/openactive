---
title: Community
permalink: "/community/"
position: 5
is_main_navigation: true
layout: page-hero
thumbnail_image: "/uploads/iStock-501777666_optimised.png"
strapline: Innovation through Collaboration
---

{::options parse_block_html="true" /}




<!-- <article markdown="0" class="hero--sub"> -->

<!-- <i class="line-graphic">{% include slim-line-graphic.svg %}</i> -->

<!-- <div> -->

<!-- <h1>Community</h1> -->
<!-- <p>Innovation through Collaboration</p> -->


<!-- </div> -->
<!-- <figure> -->
<!-- <div style="background: url({{ site.url }}/openactive/assets/images/sideplank.jpg)center center / cover no-repeat;"></div> -->
<!-- </figure> -->

<!-- </article> -->

<article>
<div class="one">

### Who’s involved?

OpenActive’s collaborative community includes ambitious start-ups supported through our Accelerator programme, members of the OpenActive Champions programme of masterclasses, who are using peer-to-peer networking to transform the sector using open data, and the skilled technical community of developers working to improve data knowledge and engagement.

Explore the dashboard to learn more about our community and the datasets already published.

[Status Dashboard](http://status.openactive.io/){:target="_blank"}{: .primary_cta}


+ Graphics and icons to represent the number of
    + Community Members
    + Accelerator Start ups
    + Data-sets Published
    + OpenActive Champions

</div>
</article>



<article>
<div class="one">

### The Community
Our community is dynamic and self-supporting, allowing us to tap into an ever growing base of engaged individuals and organisations across the sector to support activities nationwide. Building the data revolution in the sport and physical sector is a collaborative effort between consumers, organisations, and innovative start-ups, designed to support and benefit the industry at all levels.


+ Events Feed
    + Show upcoming events to users
    + [Events]( {{ site.baseurl }}{% link event-page.md %})    
    + [Event Detail]( {{ site.baseurl }}{% link _events/event-one.markdown  %})   

</div>
</article>

<article class="post-list title-row">
<h2 class="sub-heading-two"> Community News</h2>
{% for post in site.posts limit:2 %}
{% if post.categories contains "Community" %}
<div class="two" id="post-{{ forloop.index }}">
<figure role="group">
<img src="{{post.thumbnail_image | relative_url}}" alt="{{ post.title | escape }}-post-thumbnail">
</figure>
<h3>{{ post.title | escape }}</h3>
<div class="subgrid brand-one-b">
<div class="two twoleft">

{{ post.excerpt }}

<a class="button-primary" href="{{ post.url | relative_url }}">Read Post</a>
</div>

<div class="two twoleft">
{% include share-page.html %}
{{post.date}}
{{post.author}}
</div>
</div>
</div>
{% endif %}
{% endfor %}
</article>



<article>
<div class="one">

### Featured Videos 
+ A Featured Video from the community
    + Meetings
    + Publicity
    + Explanation 

</div>
</article>

<article>
<div class="one">

### Resources
+ Links to resources on the developer page
    + [Developer]( {{ site.baseurl }}{% link developer.md %})  

</div>
</article>

<article>
<div class="one">

### Meet the Community

OpenActive’s open-invitation community is continuing to grow. To discover who has joined us so far, visit our directory and meet the organisations shaping the future of the sector.

+ A section to showcase community members (5)
    + Title / Snippet / Logo 
    + Links to a directory of all community members. 
    
    
[All Members]( {{ site.baseurl }}{% link community-members.md %})  

</div>
</article>

<article>
<div class="one">

### OpenActive Champions

OpenActive Champions is a programme of masterclasses, designed to encourage peer-to-peer problem solving and networking that supports the work of people already using data to transform the sector. The programme supports individuals and organisations working to innovate within their areas, and use data to help people get more active.

The ODI is connecting Champions to experts, and supporting them to develop new solutions, skills, and approaches to increase the impact of the work they undertake locally.

To discover who’s already joined us as an OpenActive Champion, visit our directory and meet our featured Champions. 

[Discover More]( {{ site.baseurl }}{% link members-page.md %})  

</div>
</article>

<article>
<div class="one">
### FAQ's 
+ Showcasing of common FAQ's (10)
+ Links to full FAQ's [FAQ's]( {{ site.baseurl }}{% link faqs.md %})  

</div>
</article>