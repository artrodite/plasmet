<template>
  <div class="routes">
    <div class="routes-container">
      <div class="route-links">
        <ul>
          <li><a href="">Anasayfa</a></li>
          <li><a href="">Hizmetlerimiz</a></li>
          <li><a href="">Referanslarımız</a></li>
          <li><a href="">Hakkımızda</a></li>
          <li><a href="">İletişim</a></li>
        </ul>
      </div>
      <div class="products">
        <span class="title">Ürünlerimiz</span>
        <ul>
          <li><a href="">Doğal Aydınlatma Sistemleri</a></li>
          <li><a href="">Doğal Havalandırma Sistemleri</a></li>
          <li><a href="">Duman Tahliye Sistemleri</a></li>
        </ul>
      </div>
      <div class="socials">
        <span>Sosyal Medya</span>
        <ul>
          <li><a href="">Instagram</a></li>
          <li><a href="">Twitter</a></li>
          <li><a href="">Facebook</a></li>
          <li><a href="">Linkedin</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
@import "../style/_variables.scss";
.routes {
  width: 60%;
  height: 100%;
  display: flex;
  align-items: center;

  .routes-container {
    width: 100%;
    display: flex;
    justify-content: space-around;
  }

  li {
    margin: 5px 0;
  }

  a {
    border-bottom: 1px solid transparent;

    &:hover {
      border-bottom: 1px solid $light-text-color;
    }
  }

  span {
    font-weight: 700;
  }
}
</style>
