<template>
  <section class="main__saving">
    <div class="main__arrivals-title">
      <span class="main__arrivals-span"></span>
      <h2 class="main__arrivals-text">Big Saving Zone</h2>
    </div>
    <br />

<div class="main__saving-block">
<MainCard
      class="main__saving-card-item"
      :cards="cards"
      
    />
</div>
    
  </section>
</template>

<script>
import MainCard from "./MainCard.vue";

export default {
  setup() {
    const cards = [
      {
        title: "Hawaiian <br> Shirts",
        descr: "Dress up in summer vibe",
        dsc: "UPTO 50% OFF",
        image: "/src/assets/img/hawai.png",
      },
      {
        stock:"Limited Stock",
        title: "Printed <br> T-Shirt",
        descr: "Move with style & comfort",
        dsc: "UPTO 50% OFF",
        image: "/src/assets/img/print.png",
      },
      {
        title: "Cargo <br> Joggers",
        descr: "New Designs Every Week",
        dsc: "UPTO 40% OFF",
        image: "/src/assets/img/cargo.png",
      },
      {
        title: "Urban <br> Shirts",
        descr: "Live In Confort",
        dsc: "FLAT 60% OFF",
        image: "/src/assets/img/urban.png",
      },
      {
        title: "Oversized<br>T-Shirts",
        descr: "Street Style Icon",
        dsc: "FLAT 60% OFF",
        image: "/src/assets/img/oversize.png",
      },
    ];
    return {
      cards,
    };
  },
  components: { MainCard },
};
</script>

<style lang="scss" scoped></style>
