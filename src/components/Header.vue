<template>
  <nav class="navbar">
    <div class="btn-container">
      <router-link to="/">
        <div class="nav-link">Anasayfa</div>
      </router-link>
      <router-link to="/services">
        <div class="nav-link">Hizmetlerimiz</div>
      </router-link>
      <router-link to="">
        <div class="nav-link">Referanslarımız</div>
      </router-link>
    </div>
    <img src="../assets/logo.png" alt="" />
    <div class="btn-container">
      <router-link to="">
        <div class="nav-link">
          Ürünlerimiz
          <img src="../assets/arrow-down.png" class="arrow-down" alt="" />
        </div>
      </router-link>
      <router-link to="/about">
        <div class="nav-link">Hakkımızda</div>
      </router-link>
      <router-link to="/request">
        <div class="request-product-btn nav-link">
          <img src="../assets/request-product-icon.png" alt="" />
          İletişim
        </div>
      </router-link>
      <router-link to="">
        <div class="nav-link">
          Dil
          <img src="../assets/arrow-down.png" class="arrow-down" alt="" />
        </div>
      </router-link>
    </div>
  </nav>
</template>

<script setup></script>

<style lang="scss" scoped>
@import "../style/_variables.scss";

.navbar {
  width: 100%;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 20px 50px;
  position: fixed;
  top: 0;
  z-index: 1;
  background: rgba(237, 242, 244, 0.1);
  backdrop-filter: blur(15px);
  box-shadow: rgba(0, 0, 0, 0.2) 0px 8px 24px;

  .btn-container {
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 40%;

    .nav-link {
      padding: 5px 20px;
      border-radius: 5px;
      margin: 0 5px;
      background-color: transparent;
      color: $light-text-color;
      font-size: 24px;
      font-weight: 500;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: 0.2s all ease-in-out;

      .arrow-down {
        margin-left: 10px;
      }

      &.request-product-btn {
        display: flex;
        align-items: center;
        justify-content: center;
        border: 2px solid $btn-bg-color;
        background-color: $btn-bg-color;
        transition: none;

        img {
          margin-right: 10px;
          transition: none;
        }

        &:hover {
          background-color: transparent;
          color: $btn-bg-color;

          img {
            filter: $filter-to-btn-bg-color;
          }
        }
      }

      &:hover {
        background-color: $light-text-color;
        color: $dark-text-color;

        img {
          filter: $filter-to-dark-text-color;
        }
      }
    }
  }
}
</style>
