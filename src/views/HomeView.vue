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
        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
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
        <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
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
        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      </div>
      <div class="card-footer">
        <small class="text-body-secondary">Last updated 3 mins ago</small>
      </div>
    </div>
  </div>
</div>
</template>
