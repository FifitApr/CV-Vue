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
        <h2>Tentang Saya</h2>
        <h4>
        Berbekal ilmu dari pendidikan SMK Taruna Bhakti jurusan Rekayasa Perangkat Lunak, saya akan mencoba membantu memajukan perusahaan yang Anda pimpin. 
    Saya juga melampirkan pengalaman kerja saya untuk pertimbangan Anda. Dan untuk pengalaman kerja, saya melakukan web view design dan error debugging, dan melakukan tugas sesuai deadline. Saya memiliki keterampilan dalam desain Web, Bootstrap, Laravel, HTML / CSS / JavaScript / PHP.
        </h4>
        <h2>Pengalaman Saya</h2>
        <h3>2021</h3>
        <div class="prg1"><p>Uji Level</p></div>
        <p>- Membuat CRUD dengan PHP</p>

        <h2>Pengalaman Saya</h2>
        <h3>2022</h3>
        <div class="prg1"><p>Uji Level</p></div>
        <p>- Membuat CRUD dengan Laravel 8</p>
        <p>- Membuat Login</p>
        <p>- Membuat relasi antar tabel di Laravel 8</p>
      </div>



    </template>
    
    <style scoped>
    h4 {
      font-size: 1.2rem;
      margin-top: 25px;
      font-family: 'Times New Roman', Times, serif;
      color: black;
    }
    .greetings h4{
      position: relative;
    }
    .prg1 p{
      color: black;
    }
    .greetings h1,
    .greetings h3 {
      color: black;
      margin-bottom: 5px;
    }
    
    @media (min-width: 1024px) {
      .greetings h1,
      .greetings h3 {
        text-align: left;
      }

      .greetings h2{
        color: black;
        margin: 10px 0;
      }
    }
    </style>