---
show: true
width: 6
date: 2025-01-05 00:01:00 +0800
---
<div class="p-4" style="display: flex; gap: 10px; align-items: flex-start; flex-wrap: wrap;">
  
  <!-- Profile Image -->
  <img 
    data-src="{{ 'assets/images/photos/Cora_logo.jpg' | relative_url }}" 
    alt="Arne Weinhold" class="lazy profile-img rounded-lg" 
    src="{{ '/assets/images/empty_300x200.png' | relative_url }}" 
    data-toggle="tooltip" data-placement="top" title="Arne Weinhold"
    style="max-height: 295px; object-fit: cover; flex-shrink: 0;">

  <!-- Text Content -->
  <div style="flex: 1;">
    <h4>Dr. Arne Weinhold</h4>
      
    <div class="text-profile-position">
      {% for position in site.data.profile.positions %}
        {% if position.logo %}
          <img src="{{ position.logo | relative_url }}" alt="Logo" class="inline-badge"/>
        {% endif %}
        {{ position.name }}<br/>
      {% endfor %}
      <!-- <p>optional text here</p> -->
      <p> During my PhD I did six research trips to Utah (USA) for field work on plant-microbe-herbivore interactions. At Freie Universität Berlin I shifted my focus on insect-microbe symbiosis and started working with butterflies as postdoctoral researchert at the Collaborative Research Center (CRC 973). I work now as a researcher at Ludwig-Maximilians-Universität München (LMU Munich) on pollinator-microbe interactions, with special interest on solitary pollinators.</p>
    </div>
   </div>
  </div>
