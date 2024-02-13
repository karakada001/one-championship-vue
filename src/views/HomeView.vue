<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.info("we", {
  autoClose: 1500,
  position:toast.POSITION.TOP_CENTER
})



</script>

<template>
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
