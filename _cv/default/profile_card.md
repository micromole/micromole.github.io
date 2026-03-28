---
show: true
width: 6
date: 2025-01-05 00:01:00 +0800
---
<div class="p-4">
     <div style="text-align: right;">
       <img data-src="{{ 'assets/images/photos/AW_logo.jpg' | relative_url }}" alt="Arne Weinhold" class="lazy frame-img rounded-lg" 
           src="{{ '/assets/images/empty_300x200.png' | relative_url }}" data-toggle="tooltip" data-placement="top" title="Arne Weinhold" style="float: left; max-height: 295px; object-fit: cover; margin-right: 10px;">
           </div>
     <div class="card-body">
     <h4>Dr. Arne Weinhold</h4>
   <div class="text-profile-position">
   {% for position in site.data.profile.positions %}
    {% if position.logo %}
      <img src="{{ position.logo | relative_url }}" alt="Logo" class="inline-badge"/>
    {% endif %}
    {{ position.name }}<br/>
  {% endfor %}
</div>
  </div>
     </div>


