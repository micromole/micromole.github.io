---
show: true
width: 8
date: 2017-05-12 00:01:00 +0800
---

<div class="p-4">
    <h2>Plant Microbiome Function</h2>
    <hr />
   <img data-src="{{ 'assets/images/photos/IMG_2714m.jpg' | relative_url }}" class="lazy rounded" style="width: 48%; height: auto;margin: 2px;" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">
 <img data-src="{{ 'assets/images/photos/IMG_4270m.jpg' | relative_url }}" class="lazy rounded" style="width: 48%; height: auto;margin: 2px;" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">
    <hr />
    <p>
        My work at the Max Planck Institute for Chemical Ecology had the focus on the function of plant-microbe-interactions. I tested heterologous expression of antimicrobial peptides to manipulate a plants’ microbiome in the field. Here I gained a lot of experience in field work during several field trips into the Great Basin Desert of Utah (USA). I applied molecular methods to answer ecological questions in plant-microbe and plant-herbivore interactions.
        {% for post in site.posts %}
  {% if post.show %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endif %}
{% endfor %}
    </p>
    <p>
       This work was generously supported by:
    </p>
      <img src="/assets/logo/logo64_ICE.png" alt="Image 3" class="rounded-sm img-fluid logo-img">
     <img src="/assets/logo/logo64_JSMC.png" alt="Image 3" class="rounded-sm img-fluid logo-img"> 
     <img src="/assets/logo/logo64_ILRS.png" alt="Image 1" class="rounded-sm img-fluid logo-img">
    <img src="/assets/logo/logo64_Leip.png" alt="Image 1" class="rounded-sm img-fluid logo-img">
</div>
