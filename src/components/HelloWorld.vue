<template>
  <div class="hello">
    <div class="modal">
      <img src="../assets/logo.png" alt="">
      <h2>เงื่อนไขการใช้งาน</h2>
      <p class="terms">
        ไลฟ์แบล็คสุริยยาตร์กับดัก พาร์ตเนอร์โครนาแอลมอนด์แพนงเชิญ กรีน สแตนดาร์ดเทวาโรแมนติค สหรัฐวอฟเฟิลน้องใหม่ชนะเลิศเปโซ
      </p>
      <button type="button" class="accept-button">ตกลง</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.hello{
  width: 100%;
  height: 100%;
  margin: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.modal {
  width: 80%;
  padding: 1rem 2rem;
  -webkit-backdrop-filter: blur(10px);
  backdrop-filter: blur(10px);
  background-color: rgba(255, 255, 255, 0.4); 
  border-radius: 0.5rem;
}

.accept-button {
  background-color: #00b894;
  color: #fff;
  border-radius: 0.25rem;
  padding: 0.5rem 1rem;
  border: none;
  outline: none;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
