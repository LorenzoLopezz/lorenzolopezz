<template>
  <header>
    <ul>
      <li><a href="#aboutme">Sobre mí</a></li>
      <li><a href="#habilities">Habilidades</a></li>
      <li><a href="#experiences">Experiencias</a></li>
      <li><a href="#contactme">¡Contácteme!</a></li>
    </ul>
  </header>
</template>

<style>
header {
  padding: 20px;
  text-align: center;
  background: rgba(255,255,255, 0.2);
  backdrop-filter: blur(1rem);
  position: fixed;
  width: 100%;
}
ul > li {
  margin-right: 60px;
  font-weight: bold;
  font-size: 1.1rem;
  list-style: none;
  display: inline-block;
}
ul li a {
  text-decoration: none;
  color: #003D4A;
}
ul > li:last-child {
  margin-right: 0 !important;
}
</style>

<script>
export default {
  name: 'Header'
}
</script>
