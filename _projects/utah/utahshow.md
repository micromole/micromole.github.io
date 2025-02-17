---
show: true
width: 4
date: 2016-06-12 00:01:00 +0800
height: 295px
images:
- src: assets/images/photos/cover1.jpg
  title: desert
  desc: from great basin.
  link: assets/images/photos/cover1.jpg
- src: assets/images/photos/cover1.jpg
  title: Photo 2
  desc: season 2014
- src: assets/images/photos/cover1.jpg

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
