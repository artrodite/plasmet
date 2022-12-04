<template>
  <div class="contact-container">
    <div class="contact">
      <div class="contact-email">
        <div class="logo-container">
          <img src="../assets/contact-logo.png" alt="" />
        </div>
        <div class="email-container">
          <span class="email-input-text"
            >E-mail listemize katılarak en yeni gelişmelerden haberdar
            olun!</span
          >
          <div class="input-container">
            <input type="text" placeholder="E-mail" class="email-input" />
            <div class="email-input-btn">Katıl</div>
          </div>
          <span class="mini-desc"
            >E-postanızı paylaşarak Teklif Koşullarımızı, Hizmet Koşullarımızı
            ve Gizlilik Politikamızı kabul etmiş olursunuz.</span
          >
        </div>
      </div>
      <ContactRoutes></ContactRoutes>
    </div>
  </div>
</template>

<script setup>
import ContactRoutes from "./ContactRoutes.vue";
</script>

<style lang="scss" scoped>
@import "../style/_variables.scss";

.contact-container {
  width: 100%;
  padding: 0 40px;
  .contact {
    height: 391px;
    border-top: 2px solid #fff;
    border-bottom: 2px solid #fff;
    display: flex;

    .contact-email {
      width: 40%;
      height: 100%;

      .logo-container {
        margin: 80px 0;
      }

      .email-input-text {
        font-size: 20px;
        font-weight: 400;
        color: $light-text-color;
      }

      .mini-desc {
        font-size: 16px;
      }

      .input-container {
        display: flex;
        align-items: center;
        margin: 20px 0 10px 0;

        .email-input {
          width: 60%;
          border-radius: 10px;
          background-color: #dde1e3;
          border: none;
          padding: 10px 20px;
          margin-right: 15px;
          font-weight: 500;

          &:focus {
            outline: none;
          }
        }
        .email-input-btn {
          background-color: $btn-bg-color;
          padding: 5px 30px;
          border-radius: 10px;
          font-size: 16px;
          width: 20%;
          text-align: center;
          color: #fff;
          cursor: pointer;
        }
      }
    }
  }
}
</style>
