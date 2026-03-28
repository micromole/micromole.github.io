---
show: true
width: 6
date: 2025-01-05 00:01:00 +0800
---
<div class="p-4" style="display: flex; gap: 10px; align-items: flex-start; flex-wrap: wrap;">
  
  <!-- Profile Image -->
  <img 
    data-src="{{ 'assets/images/photos/AW_logo.jpg' | relative_url }}" 
    class="lazy frame-img rounded-lg" 
    src="{{ '/assets/images/empty_300x200.png' | relative_url }}" 
    data-toggle="tooltip" data-placement="top" title="Arne Weinhold"
    style="max-height: 295px; object-fit: cover; flex-shrink: 0;">

  <!-- Text Content -->
  <div class="card-body" style="flex: 1;">
    <h4>Dr. Name</h4>
    
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
