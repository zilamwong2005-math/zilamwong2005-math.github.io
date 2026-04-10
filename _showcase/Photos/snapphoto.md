---
show: true 
width: 12
date: 2020-01-12 00:01:00 +0800
images:
- src: /assets/images/etc/Photo7.jpg
- src: /assets/images/etc/Photo9.jpg
---

<style>
  .equal-height-row {
    display: flex;
    align-items: stretch;
  }
  .equal-height-col {
    display: flex;
    flex-direction: column;
  }
  .equal-height-col .card,
  .equal-height-col .carousel,
  .equal-height-col .carousel-inner,
  .equal-height-col .carousel-item,
  .equal-height-col img {
    height: 100%;
  }
  .carousel-inner img {
    object-fit: cover;
    width: 100%;
    height: 600px;
  }
  .right-card img {
    object-fit: cover;
    width: 100%;
    height: 600px;
  }
</style>

<div class="row equal-height-row">
  <!-- 左侧：轮播图，宽度 8 -->
  <div class="col-12 col-md-8 equal-height-col">
    {% include widgets/carousel.html id=page.id images=page.images height="600px" %}
  </div>
  
  <!-- 右侧：Photo8 内容，宽度 4 -->
  <div class="col-12 col-md-4 equal-height-col">
    <div class="card h-100 right-card">
      <img src="{{ '/assets/images/etc/Photo8.jpg' | relative_url }}" class="card-img-top rounded-xl" style="height: 420px; object-fit: cover;">
    </div>
  </div>
</div>