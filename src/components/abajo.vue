<script setup>
import Item from './Item.vue'
</script>

<template>
  <Item>
  <div class="text-2xl" style="margin: 30px 10px 10px 100px">
    <h1>¿Que proyectos realizamos?</h1>
    <h3>Nuestro laboratorio está pensado para <a class="text-amber-600"><b>programadores</b></a> por lo que los productos que creamos se categorizan como software. 
      <br>
    El software puede encajar en alguna de estas posibilidades:</h3>
  </div>
  </Item>

  <Item>
<div class="cards" style="margin: 0px 10px 10px 250px">
  <div class="max-w-sm rounded overflow-hidden shadow-lg bg-amber-600 border border-black " style="margin: 30px 10px 10px 0px">
  
  <div class="px-6 py-4">
    <img src="./assets/sitweb.svg" alt="sitio web" class="w-36 float-left mr-5">
    <div class="font-bold text-xl mb-2 text-cyan-900">Sitios Web</div>
    <p class="text-base text-cyan-900">
      <b>Los sitios web son lo que conocemos comúnmente por "página web".</b>
    </p>
  </div>
  <div class="listaa" style="margin: 10px 10px 10px 0px">
  Es la solución adecuada para:

  <li>Promover servicios o productos </li>
  <li>Presentar contenidos o información al público </li>
  <li>Promover un negocio </li>
  </div>
  </div>

    <div class="max-w-sm rounded overflow-hidden shadow-lg bg-amber-600 border border-black" style="margin: 30px 10px 10px 0px">
  
  <div class="px-6 py-4">
    <img src="./assets/sitweb.svg" alt="sitio web" class="w-36 float-left mr-5">
    <div class="font-bold text-xl mb-2 text-cyan-900">Aplicaciones Web</div>
    <p class="text-base text-cyan-900">
      <b>Son como los sitios web, pero estos además pueden manipular datos.</b>
    </p>
  </div>
  <div class="listaa" style="margin: 10px 10px 10px 0px">
  Es la solución adecuada para:

  <li>Registrar usuarios</li>
  <li>Mostrar información que cambia con el tiempo</li>
  <li>Realizar cálculos con la información de los usuarios</li>
  </div>
  </div>
</div>
  </Item>
</template>

<style type="text/css">
  .cards{
    display: inline-flex;

  }
</style>
