<template>
  <main>
    <div class="container">
      <div class="text-container">
        <h1>Daha iyi bir geleceğe açılan pencereler.</h1>
        <span>13 yıldır güvenle.</span>
        <a href="">
          <div class="request-product-btn">
            <img src="../assets/request-product-icon.png" alt="" />
            Ürün Talep
          </div>
        </a>
      </div>
      <div class="btn-container">
        <a href="">
          <div class="btn blue">
            <img src="../assets/ventilation-icon.png" alt="" />
            <span>Doğal Havalandırma Sistemleri</span>
          </div>
        </a>

        <a href="">
          <div class="btn yellow">
            <img src="../assets/lighting-icon.png" alt="" />
            <span>Doğal Aydınlatma Sistemleri</span>
          </div>
        </a>

        <a href="">
          <div class="btn red">
            <img src="../assets/evacuation-icon.png" alt="" />
            <span>Duman Tahliye Sistemleri</span>
          </div>
        </a>
      </div>
    </div>
  </main>
</template>

<script setup></script>

<style lang="scss" scoped>
@import "../style/_variables.scss";

.container {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  .text-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin-top: 125px;
    max-width: 500px;
    text-align: center;

    h1 {
      font-size: 64px;
      letter-spacing: 10px;
      line-height: 64px;
      font-weight: 500;
    }

    span {
      margin-top: 30px;
      font-size: 24px;
      letter-spacing: 8px;
    }
    a {
      width: 100%;
      .request-product-btn {
        background-color: $btn-bg-color;
        border: 2px solid $btn-bg-color;
        text-align: center;
        display: flex;
        align-items: center;
        justify-content: center;
        border-radius: 5px;
        font-size: 20px;
        padding: 5px 0;
        color: #fff;
        margin-top: 20px;
        img {
          margin-right: 10px;
        }

        &:hover {
          background-color: transparent;
          color: $btn-bg-color;
          img {
            filter: $filter-to-btn-bg-color;
          }
        }
      }
    }
  }

  .btn-container {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 80px;

    a {
      .btn {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 250px;
        width: 350px;
        font-size: 24px;
        border-radius: 10px;
        color: #fff;
        transition: 0.2s all ease-in-out;

        img {
          height: 103px;
        }

        &.yellow {
          margin: 0 150px;
          color: #fdc921;
        }
        &.blue {
          color: #1f9aff;
        }
        &.red {
          color: #ef233c;
        }

        &:hover {
          color: #fff;
          img {
            filter: brightness(0) saturate(100%) invert(100%) sepia(3%)
              saturate(229%) hue-rotate(240deg) brightness(121%) contrast(100%);
          }
          &.yellow {
            background-color: #fdc921;
          }
          &.blue {
            background-color: #1f9aff;
          }
          &.red {
            background-color: #ef233c;
          }
        }
      }
    }
  }
}
</style>
