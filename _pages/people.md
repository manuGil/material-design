---
title: Team Members
permalink: /people/
excerpt: "Foo Bar design system including logo mark, website design, and branding applications."
header:
  image: /assets/images/image-header.jpg
  teaser: /assets/images/teaser-header.jpg
# sidebar:
#   - title: "Role"
#     image: http://placehold.it/350x250
#     image_alt: "logo"
#     text: "PhD Candidate, Post-doctoral research"
#   - title: "Research Interests"
#     text: "material design, AI, compressible materials"
gallery:
    # make list to members home page
  - url: /assets/images/unsplash-gallery-image-1.jpg
    image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
  - url: /assets/images/unsplash-gallery-image-2.jpg
    image_path: assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
  - url: /assets/images/unsplash-gallery-image-3.jpg
    image_path: assets/images/unsplash-gallery-image-3-th.jpg
    alt: "placeholder image 3"
---

Aenean finibus hendrerit ex. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque viverra sit amet quam ac malesuada. Donec at mattis mauris, quis lacinia dolor. Proin eu elit nulla. 


<!-- {% include gallery caption="This is a sample gallery to go along with this case study." %} -->

{% for team_member in site.members %}
  <h2>
    <a href="{{ team_member.url }}">
      {{ team_member.name }} - {{ team_member.position }}
    </a>
  </h2>
{% endfor %}
