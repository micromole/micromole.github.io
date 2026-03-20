---
show: true
width: 4
date: 2025-01-05 00:01:00 +0800
---
<div>
     <div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 1px;">
       <img data-src="{{ 'assets/images/photos/AW_logo.jpg' | relative_url }}" alt="Arne Weinhold" class="lazy w-100 rounded-lg" 
           src="{{ '/assets/images/empty_300x200.png' | relative_url }}" data-toggle="tooltip" data-placement="top" title="Arne Weinhold" style="max-height: 295px; width: 100%; object-fit: cover;">
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


