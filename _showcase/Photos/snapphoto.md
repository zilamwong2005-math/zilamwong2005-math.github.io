---
show: true 
width: 6
date: 2020-01-12 00:01:00 +0800
images:
- src: /assets/images/etc/Photo7.jpg
- src: /assets/images/etc/Photo9.jpg
---

<div class="row">
  <!-- 左侧：轮播图 -->
  <div class="col-12 col-md-6">
    {% include widgets/carousel.html id=page.id images=page.images height=page.height %}
  </div>
  
  <!-- 右侧：Photo8 内容 -->
  <div class="col-12 col-md-6">
    <div class="card h-100">
      <img src="{{ '/assets/images/etc/Photo8.jpg' | relative_url }}" class="card-img-top rounded-xl" >
      <div class="card-body text-center">
        <p class="card-text">My Attempts/Scripts at <strong>Visualizing Math</strong>.</p>
      </div>
    </div>
  </div>
</div>