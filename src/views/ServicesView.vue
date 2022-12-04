<template>
  <div class="services">
    <div class="services-text">
      <h2>Hizmetlerimiz</h2>
      <div class="service-text">
        <h3>Montaj</h3>
        <span
          >Anahtar teslim projelerimizde tüm sertifikasyon eğitimlerini
          tamamlamış uzman ekiplerimiz iş güvenliği tedbirlerini alarak mümkün
          olan en kısa sürede sızdırmazlık garantisi, kaliteli işçilik
          sunmaktadır.</span
        >
      </div>
      <div class="service-text">
        <h3>Projelendirme & Danışmanlık</h3>
        <span
          >Deneyimli mühendis ekibimiz projenize uygun olarak ihtiyaçlarınızı
          doğru belirlemek, gereksiz masraflar yapılmasını önlemek için
          hizmetinizde.</span
        >
      </div>
      <div class="service-text">
        <h3>Süpervizörlük ve Devreye Alma</h3>
        <span
          >Uygulama sırasında yapılan hataların maliyeti tahmin edildiğinden çok
          fazla olabilir. Hataları minimuma indirmek için deneyimli
          mühendislerimiz yanınızda.</span
        >
      </div>
      <div class="service-text">
        <h3>Bakım</h3>
        <span
          >Periyodik bakım gereken ürünler için uygun takvim çerçevesinde bakım
          hizmetimizden yararlanabilirsiniz.</span
        >
      </div>
    </div>

    <div class="insurance">
      <h2>Ürün ve hizmetlerimiz güvence altında.</h2>
      <span>Üretimden montaja her aşamada üretici sorumluluğu.</span>
      <div class="insurance-text-container">
        <div class="insurance-text">
          <img src="../assets/insurance-icon.png" alt="" />Sızdırmazlık
          garantisi
        </div>
        <div class="insurance-text">
          <img src="../assets/insurance-icon.png" alt="" />Darbeye dayanım
          garantisi.
        </div>
        <div class="insurance-text">
          <img src="../assets/insurance-icon.png" alt="" />Açkı mekanizması
          garantisi.
        </div>
      </div>
    </div>
  </div>
</template>

<script></script>

<style lang="scss" scoped>
.services {
  background-image: url("../assets/services-bg.png");
  background-position: top right;
  background-repeat: no-repeat;
  padding: 0 110px;
  letter-spacing: 4px;

  h2 {
    font-size: 48px;
    font-weight: 700;
  }

  h3 {
    font-size: 32px;
    font-weight: 500;
  }
  span {
    font-size: 20px;
  }

  .services-text {
    margin-top: 247px;
    width: 840px;

    .service-text {
      margin-bottom: 35px;
    }
  }

  .insurance {
    margin-top: 90px;
    margin-bottom: 200px;

    .insurance-text {
      display: flex;
      align-items: center;
      margin: 30px 0;
      font-size: 24px;
      img {
        margin-right: 50px;
      }
    }
  }
}
</style>
