---
show: true
width: 4
date: 2022-10-12 00:01:00 +0800
height: 295px
images:
- src: assets/images/etc/cat1.jpg
  title: moth
  desc: from forest tour.
  link: assets/images/etc/cat1.jpg
- src: assets/images/etc/cat2.jpg
  title: Photo 2
  desc: season 2
- src: assets/images/etc/cat2.jpg

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
