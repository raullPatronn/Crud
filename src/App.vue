<script setup>
import inicio from './components/inicio.vue'
import abajo from './components/abajo.vue'
</script>

<template>
  <header class="bg-blue-300">
    
    <img alt="ISCLAB Logo" class="logo w-1/4 h-24" src="./assets/isclab.png"/>

    <nav class="menu  ">
    <ul>
    <li><a href="#" class="hover:-translate-y-1 hover:scale-110 duration-300">Principal</a></li>
    <li><a href="#" class="hover:-translate-y-1 hover:scale-110 duration-300">Ver Proyectos</a></li>
    <li><a href="#" class="hover:-translate-y-1 hover:scale-110 duration-300">Contacto</a></li>
    </ul>
    </nav>
  </header>

  <main class="bg-cyan-900">
    <inicio/>
  </main>
  <aside class="bg-gray-200">
    <abajo/>
  </aside>

  <footer>
    
  </footer>
</template>

<style scoped>
header {
  line-height: 1.5;
}
.menu li {
  display: inline-flex;
  margin-left: 80px;
  font-size: 20px;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
