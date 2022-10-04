---
title:  Tableau Worksheets and Dashboards
tags:
  - Data Visualization
  - Tableau


images:
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/1.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/2.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/3.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/4.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/5.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/6.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/7.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/8.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/9.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/10.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/11.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/12.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/13.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/14.png
  - https://hj-1304143905.cos.ap-shanghai.myqcloud.com/15.png
---

Data visualization shows charts made with Tableau for business insights.

<!--more-->

Histograms, line charts, doughnut charts, tree charts, symbolic maps, funnel charts, bubble charts, waterfall charts, and radar charts are drawn with parameters, calculated fields, and table calculations.

Worksheets and dashboards are shown here.



<div class="card-columns">
    {% for img in page.images %}
    <div class="card" data-toggle="modal" data-target="#exampleModal" data-img="{{ img }}">
        <img class="card-img-top" src="{{ img }}" />
    </div>
    {% endfor %}
</div>
<div class="modal fade" id="exampleModal">
  <div class="modal-dialog modal-lg modal-dialog-centered">
    <div class="modal-content">
      <div class="modal-body">
        <img class="modal-img w-100" />
      </div>
    </div>
  </div>
</div>

<script type="text/javascript">
  $(document).ready(function() {
    $('#exampleModal').on('show.bs.modal', function (event) {
      var button = $(event.relatedTarget)
      var img = button.data('img')
      var modal = $(this)
      modal.find('.modal-img').attr('src', img)
    })
  })
</script>


