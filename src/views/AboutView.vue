<template>
  <div class="about">
    <div class="about-text">
      <h2>Hakkımızda</h2>
      <span
        >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iure
        voluptates minima vitae eaque. Est at ipsum mollitia eaque. Fugiat
        magnam, saepe quidem dolorum porro, rem odit autem quasi officiis id
        eligendi optio ex fugit laboriosam consectetur praesentium veritatis et
        excepturi in architecto blanditiis culpa! Dolor eum alias at ipsam quia
        perferendis, quidem officia doloremque obcaecati adipisci asperiores
        corporis laboriosam illo rem mollitia maxime consequuntur nobis labore
        est itaque sapiente, iure a. Veritatis ipsam adipisci optio quasi
        recusandae error exercitationem unde voluptate voluptates cum nisi
        dignissimos accusantium eos ea repellendus animi, natus, neque molestias
        molestiae nulla beatae modi dolor? Aspernatur esse, quia libero, nostrum
        reprehenderit dolor corrupti debitis nulla veritatis corporis
        accusantium. Voluptate, beatae. Laudantium sit dolorum minus ex
        repellendus possimus!</span
      >
    </div>
    <img src="../assets/about-bg.png" class="about-bg" alt="" />
  </div>
</template>

<script></script>

<style lang="scss" scoped>
@import "../style/_variables.scss";

.about {
  height: 100vh;
  // background-image: url("../assets/about-bg.png");
  // background-position: top right;
  // background-repeat: no-repeat;
  padding: 0 110px;
  .about-bg {
    position: fixed;
    right: 0;
    top: 50%;
    transform: translateY(-50%);
  }
  .about-text {
    width: 500px;
    margin-top: 247px;
    color: $light-text-color;

    h2 {
      font-size: 48px;
      font-weight: 700;
      letter-spacing: 4px;
    }

    span {
      font-size: 20px;
      font-weight: 400;
    }
  }
}
</style>
