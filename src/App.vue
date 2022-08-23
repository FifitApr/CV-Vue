<script setup>
import { RouterLink, RouterView } from 'vue-router'
import "./style.css"
</script>

<template>
  <div class="container">
    <div class="navbar">
      <ul>
        <li>
          <a href=""><RouterLink to="/">Home</RouterLink></a>
          <a href=""><RouterLink to="/about">About</RouterLink></a>
        </li>
      </ul>
    </div>
  
   <header>
    <img alt="foto CV" class="foto" src="@/assets/foto1.jpg" width="125" height="125" />
    <div class="text">
        <h3>
        Software Developer
          
        </h3>
        <h5>
        <p>Kp. Kalimanggis Rt. 01/04 Kel. Harjamukti Kec. Cimanggis Kota Depok</p>
        <p>089501145766</p>
        <p><a target="_blank" href="/">fifitapr76@gmail.com</a></p>
        <p><a target="_blank" href="https://instagram.com/fifit_apryni?igshid=YmMyMTA2M2Y=">@fifit_apryni</a></p>
          <p><a target="_blank" href="https://github.com/FifitApr">FifitApr</a></p>
          
        </h5>
    </div>
    

    <div class="wrapper">
      

      <!-- <nav>
        
      </nav> -->
    </div>
    
   </header>

   <RouterView />
  </div>
</template>


