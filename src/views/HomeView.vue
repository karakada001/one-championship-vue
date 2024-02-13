<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.info("we", {
  autoClose: 1500,
  position:toast.POSITION.TOP_CENTER
})



</script>

<template>
<div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://cdn.onefc.com/wp-content/uploads/sites/5/2023/11/231222-BKK-OFF46-1800x1200px.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://cdn.onefc.com/wp-content/uploads/sites/5/2022/02/221118-OPV4-1800x1200px-1.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://cdn.onefc.com/wp-content/uploads/sites/5/2021/06/220326-web-1800x1200px.jpeg" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
  <div class="row row-cols-1 row-cols-md-3 g-4">
  <div class="col">
    <div class="card h-100">
      <img src="https://cdn.onefc.com/wp-content/uploads/sites/5/2024/02/240216-BKK-OFF52-1800x1200px-1536x1024.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">One Championship</h5>
        <p class="card-text">(FRI) 16 FEB 19:30 น. ตามเวลาไทย
สนามมวยเวทีลุมพินี, กรุงเทพฯ
ONE ลุมพินี 52</p>
      </div>
      <div class="card-footer">
        <small class="text-body-secondary">Last updated 3 mins ago</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="https://cdn.onefc.com/wp-content/uploads/sites/5/2024/01/240217-OFN19-1800x1200px-1536x1024.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">One Championship</h5>
        <p class="card-text">(SAT) 17 FEB 08:00 น. ตามเวลาไทย
สนามมวยเวทีลุมพินี, กรุงเทพฯ
ONE Fight Night 19: โจนาธาน vs ฟิลิปเป</p>
      </div>
      <div class="card-footer">
        <small class="text-body-secondary">Last updated 3 mins ago</small>
      </div>
    </div>
  </div>
  <div class="col">
    <div class="card h-100">
      <img src="https://cdn.onefc.com/wp-content/uploads/sites/5/2023/12/240301-DOH-ONE166-1800x1200px-1-1536x1024.jpg" class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">One Championship</h5>
        <p class="card-text">(FRI) 1 MAR 19:30 น. ตามเวลาไทย
ลูเซล สปอร์ตส์ อารีนา, ลูเซล
ONE 166: Qatar</p>
      </div>
      <div class="card-footer">
        <small class="text-body-secondary">Last updated 3 mins ago</small>
      </div>
    </div>
  </div>
</div>
</template>
