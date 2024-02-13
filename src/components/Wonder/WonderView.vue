<template>
<div id="carouselExample" class="carousel slide">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://cdn.onefc.com/wp-content/uploads/2022/05/Rodtang-Jitmuangnon-Jacob-Smith-ONE157-1920X1280-1.jpg" class="card-img-top" height="650px" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://cdn.onefc.com/wp-content/uploads/2019/11/Nong-O-Gaiyanghadao-VS-Saemapetch-Fairtex-at-ONE-EDGE-OF-GREATNESS-YK4_0508.jpg" class="card-img-top" height="650px" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://cdn.onefc.com/wp-content/uploads/2022/03/Superbon-Singha-Mawynn-Marat-Grigorian-ONE-X-1920X1280-56.jpg" class="card-img-top" height="650px" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-4 mb-5 justify-content-md-start" v-for="item in allWonders" :key="item.id">
                <div class="card shadow p-0" style="height:330px">
                    <img :src="item.imageUrl" class="card-img-top" height="320px" alt="wonders">
                    <div class="card-body">
                        <h5 class="card-title">{{ item.name }}</h5>
                        <p class="card-text">Location - {{ item.location }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import axios from 'axios'
import { onMounted,ref } from 'vue';

const allWonders = ref([]);

onMounted(() => {
    axios.get(`https://one-championship-server.onrender.com/ONE-Championship`)
        .then((response) => {
            // console.log(response.data)
            allWonders.value = response.data
        })
})

</script>

<style lang="scss" scoped></style>