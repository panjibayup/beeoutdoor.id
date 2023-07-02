<template>
  <section>
    <div class="hero" style="margin-top: 100px">
      <div class="row justify-content-center mt-4 hero-satu">
        <div class="col-md-6" data-aos="fade-left" data-aos-duration="1500">
          <img src="../assets/images/hero.png" class="hero-img" style="width: 100%" />
        </div>

        <div class="col-md-6" data-aos="fade-right" data-aos-duration="1500">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2 class="hero-text">
                <strong>Sewa Kursi Lipat & Alat Outdoor,</strong>
                <br />di <span>Bee Outdoor</span> aja
              </h2>
              <router-link class="btn btn-lg mt-4 online" to="/menu" data-aos="fade-down" data-aos-duration="2000"> <i class="bi bi-cart-plus"></i> Pesan Sekarang </router-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "hero",
};
</script>
<style scoped>
h2 {
  font-weight: 600;
}
.btn {
  width: 270px;
  font-weight: 600;
}
.online {
  margin-left: 20px;
  background-color: gold;
}
h2 span {
  font-weight: 700;
  color: orange;
  border-bottom: 2px solid #000;
}
@media (max-width: 767.98px) {
  .hero {
    text-align: center;
  }
  .hero-satu {
    padding: 20px;
  }

  .tombol {
    width: 100%;
  }
  .online {
    width: 100%;
    margin-left: 0;
    margin-bottom: 40px;
  }
}
</style>
