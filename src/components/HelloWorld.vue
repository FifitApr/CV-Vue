<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
    Software Developer
      <!-- Berbekal ilmu dari pendidikan SMK Taruna Bhakti jurusan Rekayasa Perangkat Lunak, saya akan mencoba membantu memajukan perusahaan yang Anda pimpin. 
Saya juga melampirkan pengalaman kerja saya untuk pertimbangan Anda. Dan untuk pengalaman kerja, saya melakukan web view design dan error debugging, dan melakukan tugas sesuai deadline. Saya memiliki keterampilan dalam desain Web, Bootstrap, Laravel, HTML / CSS / JavaScript / PHP. -->
      <p><a target="_blank" href="https://instagram.com/fifit_apryni?igshid=YmMyMTA2M2Y=">@fifit_apryni</a></p>
      <p><a target="_blank" href="https://github.com/FifitApr">FifitApr</a></p>
      <p><a target="_blank" href="/">fifitapr76@gmail.com</a></p>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
