---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 295px
images:
- src: assets/images/etc/cat1.jpg
  title: Photo 1
  desc: Description 1.
  link: assets/images/etc/cat1.jpg
- src: https://picsum.photos/seed/second22/800/800
  title: Photo 2
  desc: Description 2
- src: https://picsum.photos/seed/third33/800/800
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
