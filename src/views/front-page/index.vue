<template>
  <div class="dashboard-container">
    <div><h5>Hello World</h5></div>
    <div><h5>你好世界</h5></div>
    <div><h5>नमस्ते दुनिया</h5></div>
    <div><h5>Hola Mundo</h5></div>
    <div><h5>Bonjour le monde</h5></div>
    <div><h5>مرحبا بالعالم</h5></div>
    <div><h5>ওহে বিশ্ব</h5></div>
    <div><h5>Привет мир</h5></div>
    <div><h5>Olá Mundo</h5></div>
    <div><h5>Halo Dunia</h5></div>
    <div><h5>ہیلو ورلڈ</h5></div>
    <div><h5>Hallo Welt</h5></div>
    <div><h5>こんにちは世界</h5></div>
    <div><h5>Salamu, Dunia</h5></div>
    <div><h5>हॅलो वर्ल्ड</h5></div>
    <div><h5>హలో వరల్డ్</h5></div>
    <div><h5>Selam Dünya</h5></div>
    <div><h5>வணக்கம் உலகம்</h5></div>
    <div><h5>헬로월드</h5></div>
    <div><h5>Chào thế giới</h5></div>
    <div><h5>Sannu Duniya</h5></div>
    <div><h5>Ciao mondo</h5></div>
    <div><h5>สวัสดีชาวโลก</h5></div>
    <div><h5>હેલો વર્લ્ડ</h5></div>
    <div><h5>سلام دنیا</h5></div>
    <div><h5>Hello Mundo</h5></div>
  </div>
</template>

<script>
import { mapGetters } from 'vuex'

export default {
  name: 'Dashboard',
  computed: {
    ...mapGetters([
      'name'
    ])
  }
}
</script>

<style lang="scss" scoped>
.dashboard {
  &-container {
    margin: 30px;
  }
  &-text {
    font-size: 30px;
    line-height: 46px;
  }
}
</style>
