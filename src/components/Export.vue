<template>
  <div class="panel">
    <h4 class="title">Скачать данные в csv формате</h4>
    <a class="link" :href="$provider.exportUrl(30)">30 дней</a>&nbsp;|&nbsp;
    <a class="link" :href="$provider.exportUrl(7)">7 дней</a>&nbsp;|&nbsp;
    <a class="link" :href="$provider.exportUrl(1)">1 день</a>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.panel {
  overflow: hidden;
  position: absolute;
  top: 29px;
  right: 0;
  z-index: 1000;
  background: rgba(255, 255, 255, 0.9);
  padding: 10px;
  border: 5px solid #e0e0e0;
}
.title {
  font-size: 14px;
  margin: 10px;
}
.link {
  color: #54bcda;
}
</style>
