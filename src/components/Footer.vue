<template>
  <footer>
    <span>© 2022 PLASMET YAPI ÇÖZÜMLERİ, Tüm Hakları Saklıdır</span>
    <ul>
      <li><a href="">Kullanım Şartları</a></li>
      <li><a href="">Satış Şartları</a></li>
      <li><a href="">Şirket Şartları</a></li>
      <li><a href="">Gizlilik ve Tanımlama Bilgi Politikası</a></li>
    </ul>
  </footer>
</template>

<script setup></script>

<style lang="scss" scoped>
@import "../style/_variables.scss";

footer {
  width: 100%;
  height: 90px;
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  padding: 5px 40px;
  color: $light-text-color;

  ul {
    display: flex;
    align-items: center;
    justify-content: center;

    li {
      margin: 0 10px;
      font-size: 12px;
    }
  }
}
</style>
