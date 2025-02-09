---
show: true
width: 4
date: 2014-06-12 00:01:00 +0800
height: 295px
images:
- src: assets/images/etc/cat1.jpg
  title: desert
  desc: from great basin.
  link: assets/images/etc/cat1.jpg
- src: assets/images/etc/cat2.jpg
  title: Photo 2
  desc: season 2014
- src: assets/images/etc/cat2.jpg

---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
