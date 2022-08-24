<script setup>
import { RouterLink, RouterView } from 'vue-router'
import "./style.css"
import Footer from './components/Footer.vue';
</script>

<template class="bg">
  <div class="container">
    <div class="navbar">
      <ul>
        <li>
          <a href=""><RouterLink to="/">Personal</RouterLink></a>
          <a href=""><RouterLink to="/about">Skill</RouterLink></a>
        </li>
      </ul>
    </div>
  
   <header>
  

    <div class="card">
    <div class="card-box">
    <img src="@/assets/foto1.jpg" alt="">
    <h1>Fifit Apriyani</h1>
    <h4>Fornt End Developer</h4>
    <p>Kp. Kalimanggis Rt. 01/04 Kel. Harjamukti <p>Kec. Cimanggis Kota Depok</p> </p>
        <p>089501145766</p>
    <p><a href="fifitapr76@gmail.com">fifitapr76@gmail.com</a></p>
    <p><a href="https://instagram.com/fifit_apryni?igshid=YmMyMTA2M2Y">@fifit_apryni</a> | <a href="https://github.com/FifitApr">FifitApr</a></p>
    </div>
    <div class="card-box2">
    <RouterView />
    </div>
    </div>
    
   </header>
   <div class="btn-group">
    <button><a href="https://www.canva.com/design/DAFJdAWgqjI/a7BrNAplN7OGadHqZLaNLg/">Lihat CV Saya</a></button>
    </div>

  <Footer/>
  </div>
</template>


